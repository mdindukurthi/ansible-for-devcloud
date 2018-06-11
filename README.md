# ansible-repo

# Ansible command for spin the instance in devcloud
Ex:
ansible-playbook spininstace.yml --extra-vars "templateid=176 type=micro count=3"

# In above command templateid and type are  mandatory variables and count is optional, if not providing the number of machines count, it will take the default count value is 1
# Right now it will support only 3 types of instance, those are micro,medium and large
micro: 8GB Memory and 2 vcpus
medium: 16GB Memory and 2 vcpus
large: 32 GB memory and 8 vcpus


# Ansible command for get info for the instance in devcloud

Ex:
ansible-playbook vminfo.yml --extra-vars "vmid=7027"

# vmid is mandatory variable.
