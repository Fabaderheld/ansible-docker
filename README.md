# ansible-docker
Template for creating Docker containers and add the to netbox

# Features

* Looks up next free ip in docker VLAN from Netbox
* Adds VM in Netbox
* Creates container based on docker_compose file
* Adds Docker Mac to Netbox VM
* Adds internal DNS to PiHole
* (Optional) Adds external DNS Record to hetzner


# Usage

`ansible-playbook -Kb --ask-vault-password docker-container.yml`

# Update repo from templae

```
git remote add template git@github.com:Fabaderheld/ansible-docker.git
git fetch --all
git merge template/main  --allow-unrelated-histories 
```

