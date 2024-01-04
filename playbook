- name: Update web servers
  hosts: G1
  become: yes


  tasks:
  - name: Installing git
    yum:
      name: git
      state: present

  - name: Ensure app deployed
    git:
      dest: /var/www/html
      repo: https://github.com/Muralee1/ecomm.git


- name: Update web servers
  hosts: G2
  become: yes


  tasks:
  - name: Installing git
    yum:
      name: git
      state: present

  - name: Ensure app deployed
    git:
      dest: /var/www/html
      repo: https://github.com/Muralee1/ecomm.git
