---

- name: Creating MOTD
  vars:
   variable1: 'Ansible Managed node by vaacabang'
  ansible.builtin.template:
    src: /root/sysad2-2022/Prelim-exam/roles/ChangeMOTD/files/MOTD.j2
    dest: /etc/motd