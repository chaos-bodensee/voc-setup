 Video Streaming - Ansible Setup
====================================
Ansible Setup for the VOC-Setup *(Video Operation Center)* from the [Toolbox Bodensee e.V.](https://toolbox-bodensee.de/).

![Toolbox VOC](.github/toolbox-voc.svg "Toolbox Video Operation Center")

Ansible is a radically simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. [Weitere Infos](https://de.wikipedia.org/wiki/Ansible) | [Learn more](https://www.ansible.com/overview/how-ansible-works)

 Usage:
-------
This git repository contains git submodules. To see our complete setup you have to clone them too!
It is inspired by the awesome [C3VOC](https://c3voc.de) and their [content-management](https://github.com/voc/cm.git) Git Repository.

```
# Clone the Git with submodules
git clone --recursive https://github.com/ToolboxBodensee/toolbox-voc_ansible.git
git submodule update --init --recursive
```


 Playbooks:
------------
+ ``site.yml``: Setup voctocore on video encoder pc.


 How does our Setup work?
-------
We try to explain it in the "[overview/](https://github.com/chaos-bodensee/voc-setup/blob/master/overview/README.md)" Folder. Including a simplified getting-started guide.


 Questions about this setup?
------------------------------
L3D will explain it to you if you invite him to a [Tschunk](https://entropia.de/Tschunk).<br/>
or ask the awesome c3voc. They developed it! They are awesome!
<!-- Why moved away from toolbox github repo? Toolbox decided to force everyone to move to gitlab. ALL commits on github where forcefully overwritten. Github is only a Mirror and no master. It was a very stressful situation and this repo is now moved away to keep its history! -->

 How to understand the single part of this ansible?
---------------------------------------------------

The playbook is defined in the ``site.yml`` File. There are some ``roles`` defined, that will be executed.
More details what the roles do are usually documented in the single roles-README. The configuration of all roles are defined in the group_vars ans host_vars.

You can find the inventory in ``ansible/hosts.ini``!

 where is your votomix config?
------------------
Our voctomix - voctocore and voctogui config is stored in this git repository:

https://github.com/chaos-bodensee/voc-config.git

It is deployed via this ansible and is working together with some images and systemd-scripts that keep everything running smoothly together!
