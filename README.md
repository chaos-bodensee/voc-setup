 Video Streaming - Ansible Setup
====================================
Ansible Setup for the VOC *(Video Operation Center)* from the [Toolbox Bodensee e.V.](https://toolbox-bodensee.de).

Ansible is a radically simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. [Weitere Infos](https://de.wikipedia.org/wiki/Ansible) | [Learn more](https://www.ansible.com/overview/how-ansible-works)

 Usage:
-------
This git repository contains git submodules. To see our complete setup you have to clone them too!
```
# Clone the Git
git clone https://github.com/ToolboxBodensee/toolbox-voc_ansible.git

# Clone the Submodules 
cd ansible
git submodule update --init --recursive
```


 Playbooks:
------------
+ ``streaming_setup.yml``: Setup voctocore on video encoder pc.

 Setup
-------

We will say how we build our streaming setup in the wiki at [tbbs.me/streaming](https://tbbs.me/doku.php?id=streaming:start).

