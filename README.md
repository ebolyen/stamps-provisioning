
https://docs.ansible.com/ansible/latest/scenario_guides/guide_vagrant.html

Install:
  - Vagrant 1.7+
  - Ansible
  - Oracle VirtualBox


The Vagrantfile will automatically downloaded Ubuntu 18.04,
which will take a while the first time you run it.

Future invocations will not download the entire image again.


# Instructions to test [TODO]:

```
vagrant up
```

Then go to `localhost:8080/rstudio/` or `locahost:8080/jupyter/` (not done)
