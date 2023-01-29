1.) Run this command 
    ansible -i test.ini  all -m shell -a 'yum info nginx'
    OR you can also use this
    ansible -i test.ini  all --module-name shell --args 'yum info nginx'   
The node name is stored in test.ini and the command follows.

2.) If we want to do it via a playbook and want to store the output of the playbook.
I have written a playbook get-package-info.yml. It prints the info for all the versions. 

3.) Generic way : wrote a playbook to run any bash script.
