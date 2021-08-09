# ACM Observability playbooks

The goal of this playbook is automate the observability
in RHACM. In this case, the playbook will manipulate a 
OCP cluster with ACM 2.2 created in RHPDS.

Modify extra-vars-example.yml with OCP URL and credentials.
Bucket name can be specified in extra-vars.yml as well.


## Usage:

```
ansible-playbook acm_setup_observability.yml -e @extra_vars.yml
```

## Variables

These variables are set as extra vars.

- `acm_host`: OpenShift API URL, the same used in `oc` command
- `acm_user`: admin-user
- `acm_pass`: admin-pass
- `aws_region`: us-east-1
