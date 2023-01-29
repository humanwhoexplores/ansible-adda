1.) Run this command 
    ansible -i test.ini  all -m shell -a 'yum info nginx'
    OR you can also use this
    ansible -i test.ini  all --module-name shell --args 'yum info nginx'   
The node name is stored in test.ini and the command follows.

2.) If we want to do it via a playbook and want to store the output of the playbook.
