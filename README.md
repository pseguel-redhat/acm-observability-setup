# ACM Observability playbooks

The goal of this playbook is automate the observability
in RHACM. In this case, the playbook will manipulate a 
OCP cluster with ACM 2.2 created in RHPDS.

Modify extra-vars-example.yml with OCP URL and credentials.

##Usage:

```
ansible-playbook acm_setup_observability.yml -e @extra_vars.yml
```
