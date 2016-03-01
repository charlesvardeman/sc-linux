# Vagrant Provisioning Environment for Smart Container Development.

Vagrant file for creating Ubuntu VM for Python Development. Ansbile requires docker role from Ansible Galaxy. The install_reqs.sh shell script will download docker role into Roles subdirectory. Script requires that Ansible be installed on the local machine. Smart Containers is also included as a git submodule. To initialize:

```bash
git submodule update --init
```
Will initialize the Smart Container Repository. The Vagrant up command will start the VM and vagrant ssh will connect to the VM.
