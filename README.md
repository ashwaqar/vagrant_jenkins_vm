# vagrant_jenkins_vm
Contains a VagrantFile which spins up VM with Jenkins and Java preinstalled.

- Once the VM is up do - 

```sh
vagrant ssh
cat /var/log/jenkins/jenkins.log | grep password -A 3
```
- This is to get the initial password for the Jenkins start.

- Then go to "http://192.168.33.10:8080/" on your browser to access Jenkins.
