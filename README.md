# ansible-project-skeleton
This repository doesn't have any real code but only empty playbooks to show ansible repository file structure.

** as a summary this repository manages a 2 projects with some web servers and database servers 

** it needs to ben run like;

ansible-playbook playbooks/main.yml -e env=[test/acc/prod] --ask-vault-pass

hosts file grouping at logic at the main.yml chooses correct host file across different environmets
