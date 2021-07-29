# ansible-docker
Template for creating Docker containers and add the to netbox

# Usage

run once with `--skip-tags` poststartup tag to start the container

`ansible-playbook -Kb --ask-vault-password docker-container.yml --skip-tags poststartup`

afterwards run it again to add missing data to netbox

`ansible-playbook -Kb --ask-vault-password docker-container.yml`