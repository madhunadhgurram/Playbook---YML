TAGS: by default ansible will execute all tasks sequentially in a playbook.
we can use tags to execute a specific tasks or to skip a specific tasks.

SINGLE TAG: ansible-playbook madhu.yml --tags d

MULTI TAGS: ansible-playbook madhu.yml --tags b,c


NOTE: BY DEFAULT ANSIBLE WILL EXECUTE PLAYBOOK ON SEQUENTIAL.

IF TASK-3 GOT FAILED IT WILL STOP EXECUTING REMAING TASKS. 
Put ignore_errors: true IT WILL IGNORE THE FAILED TASK AND RUN REMAINING TASKS.
