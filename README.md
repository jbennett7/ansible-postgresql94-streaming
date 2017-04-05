# ansible-postgresql94-streaming-rhel7

roles:
-  ansible-ec2-testinstance
-  ansible-postgresql94-server
-  primary
-  backup

`ansible-playbook -i inventory pg_streaming.yml --tags deploy`
