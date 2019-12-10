# enable-auto-node-cert-renewal

This playbook runs the enable_bootstrap_config task from the openshift-ansible installer.
Your inventory must have `openshift_master_bootstrap_auto_approve` set to true.
Running of this playbook is not required if `openshift_master_bootstrap_auto_approve` was set to true during the cluster deploy.



## License

BSD

## Author Information
Brian Jarvis (bjarvis@redhat.com)
