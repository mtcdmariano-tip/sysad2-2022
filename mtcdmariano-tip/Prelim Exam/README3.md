@@ -0,0 +1,21 @@
---

- hosts: all
  become: true
  roles:
    - Python

- hosts: all
  become: true
  roles:
    - Java

- hosts: all
  become: true
  roles:
    - ChangeMOTD

- hosts: all
  become: true
  roles:
    - Create_User 