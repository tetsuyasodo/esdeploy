# esdeploy

```
# export http_proxy=http://xxx:8080
# export https_proxy=http://xxx:8080

# yum update -y
# yum install -y epel-release ssh-pass ansible git

# ssh-keygen -t rsa
# ssh-copy-id localhost

# git clone https://github.com/tetsuyasodo/esdeploy.git
# git clone https://github.com/elastic/ansible-elasticsearch.git
# cd esdeploy/roles
# ln -s ~/ansible-elasticsearch elasticsearch

# ansible-playbook -i hosts site.yml

# yum install -y kibana logstash
# /usr/share/kibana/bin/kibana-plugin install x-pack
# systemctl restart kibana
```
