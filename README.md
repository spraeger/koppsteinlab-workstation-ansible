# koesterlab-workstation-ansible

This ansible playbook configures the workstations in koesterlab to become a usable working environment.
It assumes that Fedora Linux and ansible (`dnf install ansible`) has been already installed.

The playbook can be executed as

```bash
curl https://github.com/koesterlab/koesterlab-workstation-ansible/raw/main/playbook.yml | ansible-playbook /dev/stdin
```
