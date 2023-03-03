# Collection of Ansible playbooks

## Installation

```bash
git clone https://github.com/gszasz/ansible-workspace
```

### Fedora 37 Dependencies

```bash
$ sudo dnf install -y ansible-core ansible-collection-community-general
```

## Playbooks

### Upgrade

Ansible playbook to correctly upgrade all my servers and desktops.

#### Usage

```bash
$ cd ansible-workspace/upgrade
$ ansible-playbook site.yml
```


### ESO Chile Printers

Ansible playbook to setup printers for all sites at ESO Chile on local computer.

#### Usage

```bash
$ cd ansible-workspace/eso-chile-printers
$ ansible-playbook site.yml
```


### E152

Asible playbook to setup ESO 1.52-m telescope UNIX controller

#### Usage

```bash
$ cd ansible-workspace/e152
$ ansible-playbook site.yml
```


### Insights

Ansible playbook to setup Red Hat Insights on a RHEL server.

#### Usage

```bash
$ cd ansible-workspace/insights
$ ansible-playbook ros_install_and_set_up.yml
```
