╰─$ ANSIBLE_ACTION_WARNINGS=False ansible -i test.ini  all --module-name shell --args 'yum info nginx'

Store Ansible's output in a File using this command
ANSIBLE_ACTION_WARNINGS=False ansible -i test.ini  all --module-name shell --args 'yum info nginx' > output.txt