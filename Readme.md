## Installation of Spark Cluster Using Ansible

## Requirements
* vagrant

## Notes*
```
OpenJDK8 will used by default.
```
## To Start
* **STEP-1**
```
vagrant up
```

* **STEP-2**
```
vagrant ssh controller
```

* **STEP-3**
```
cd /home/vagrant/projects/playbooks
```

* **STEP-4**
```
ansible-playbook -i hosts/cluster.ini spark-cluster.yml
```

# Supported/Tested OS
* CentOS 7
* RedHat 7