Hetzner automated installation with Ansible
===========================================

This playbook is based on playbooks provided by Marcel Wiget: https://github.com/mwiget/hetzner-ansible.

First set the Hetzner webservice robot credentials. Aftwards run the playbook to install a server.

.. code::

   $ ansible-playbook -i your-fancy-server, playbook.yml
   Type 'CONFIRMATION' to confirm the installation: CONFIRMATION

   PLAY ***************************************************************************

   TASK [check confirmation] ******************************************************
   skipping: [your-fancy-server]

   TASK [get ip address of inventory_hostname] ************************************
   changed: [your-fancy-server -> 127.0.0.1]

   ...
