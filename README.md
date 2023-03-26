```
ansible-playbook -i hosts.ini deploy_playbook.yml [ -e "elk_version=7.7.0|6.6.2" ] [ -e "filebeat_output_type=logstash|file" ] [ --vault-password-file vault.txt ]
```
