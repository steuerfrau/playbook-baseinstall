playbook-baseinstall
=========
Ansible playbook with basic installation steps.

Important Variables
------------
This playbook utilizes

```
git clone https://github.com/steuerfrau/playbook-skeleton.git new-repo-name
cd new-repo-name
git remote set-url origin https://github.com/steuerfrau/playbook-baseinstall.git
git remote add upstream https://github.com/<new-repo-uri>
git push origin master
git push --all
```

Used Roles
--------------

License
-------
GNU General Public License v3.0

Author Information
------------------
Melanie Desaive
m.desaive@mailbox.org
