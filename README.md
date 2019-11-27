 Video Streaming - Ansible Setup
====================================
Ansible Setup for the VOC-Setup *(Video Operation Center)* from the [Toolbox Bodensee e.V.](https://toolbox-bodensee.de/).

![Toolbox VOC](.github/toolbox-voc.svg "Toolbox Video Operation Center")

Ansible is a radically simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. [Weitere Infos](https://de.wikipedia.org/wiki/Ansible) | [Learn more](https://www.ansible.com/overview/how-ansible-works)

 Usage:
-------
This git repository contains git submodules. To see our complete setup you have to clone them too!
You need [git-lfs](https://git-lfs.github.com/) to clone all parts of this repository!

```
# Clone the Git with submodules
git clone --recursive https://github.com/ToolboxBodensee/toolbox-voc_ansible.git
git submodule update --init --recursive
```


 Playbooks:
------------
+ ``site.yml``: Setup voctocore ans obs on video encoder pc.

 How does our Setup work?
-------
We try to explain it in the "[overview/](https://github.com/chaos-bodensee/voc-setup/blob/master/overview/README.md)" Folder. Including a simplified getting-started guide.

 Questions about this setup?
------------------------------
L3D will explain it to you if you invite him to a [Tschunk](https://entropia.de/Tschunk).<br/>
or ask the awesome c3voc. They developed it! They are awesome!
<!-- Why moved away from toolbox github repo? Toolbox decided to force everyone to move to gitlab. ALL commits on github where forcefully overwritten. Github is only a Mirror and no master. It was a very stressful situation and this repo is now moved away to keep its history! -->
