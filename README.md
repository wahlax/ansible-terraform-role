# Terraform with Ansible

Role for installing Terraform

## Optional Parameters

 * `terraform_version` - Version of Terraform

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

Run the following from the test directory:

### Initial Install
```
vagrant up
```

### Reapply provisioning
```
vagrant provision
```
