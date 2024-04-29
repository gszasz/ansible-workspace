_Copyright © 2022-2024 Gabriel Szász; see the end of the file for license
conditions._

# Collection of Ansible playbooks

## Installation

```bash
git clone https://github.com/gszasz/ansible-workspace
```

### Fedora 39 Dependencies

```bash
$ sudo dnf install -y ansible-core ansible-collection-community-general
```

### Ubuntu 22.04 Dependencies

```bash
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt update
$ sudo apt install ansible
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

# Note on copyright years

In copyright notices where the copyright holder is Gabriel Szász, then where a
range of years appears, this is an inclusive range that applies to every year in
the range.  For example: 2005-2008 represents the years 2005, 2006, 2007, and
2008.

# License conditions

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <https://www.gnu.org/licenses/>.
