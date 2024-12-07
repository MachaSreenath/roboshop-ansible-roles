### while working with this roles, we given variable name in main.yaml and we have to pass the variable value at the execution time, like:

" ansible-playbook -i inventory.ini -e ansible_user=centos -e ansible_password=DevOps321 -e component=mongodb main.yaml "