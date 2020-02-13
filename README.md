# Repos used for the Ansible Automates Paris 2020 Demos

To use this you need a Tower deployement with 3 isolated instance groups (one in azure, one in aws and one [container group](https://docs.ansible.com/ansible-tower/latest/html/administration/external_execution_envs.html#container-groups)  on an openshift cluster).

Some Tower credentials are expected, I'll eventually get around to automate the deployment of the environement so watch this space ;) 
 
This is all demo code and can obviously be vastly improved.

## Roles

- Configure an MSSQL instance on RHEL to be used by an EAP Install:
[https://github.com/automaticdavid/eap\_mssql/tree/automates\_paris\_2020](https://github.com/automaticdavid/eap_mssql/tree/automates_paris_2020)


- Configure EAP Instances (HA or not):
[https://github.com/automaticdavid/eap/tree/automates\_paris\_2020](https://github.com/automaticdavid/eap/tree/automates_paris_2020)

- Provision EC2 environement and VMs
[https://github.com/automaticdavid/ec2/tree/automates\_paris\_2020](https://github.com/automaticdavid/ec2/tree/automates_paris_2020)

- Provision Azure environement and VMs
[https://github.com/automaticdavid/azure/tree/automates\_paris\_2020](https://github.com/automaticdavid/azure/tree/automates_paris_2020)


## Demo Playbooks

These provide the `stack.yml`playbook used in the Tower templates:

- [https://github.com/automaticdavid/demo\_eap\_azure/tree/automates\_paris\_2020](https://github.com/automaticdavid/demo_eap_azure/tree/automates_paris_2020)
- [https://github.com/automaticdavid/demo\_eapv_aws/tree/automates\_paris\_2020](https://github.com/automaticdavid/demo_eap_aws/tree/automates_paris_2020)
- [https://github.com/automaticdavid/demo\_eap\_ocp/tree/automates\_paris\_2020](https://github.com/automaticdavid/demo_eap_ocp/tree/automates_paris_2020)