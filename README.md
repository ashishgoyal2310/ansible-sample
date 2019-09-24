ansible-playbook -i inventory-hosts site.yml --ask-sudo-pass --check

ansible-playbook -i inventory-hosts site.yml --ask-become-pass

ansible-playbook -i inventory-hosts site.yml --ask-sudo-pass
