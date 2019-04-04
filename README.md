# vagrant-docker-terraform
Simple vagrantconfig with ubuntu bionic beaver, docker and terraform

have vagrant and virtual box installed and do these

```bash
git clone git@github.com:Marantle/vagrant-docker-terraform.git
cd vagrant-docker-terraform
vagrant up
# wait while it downloads and installs
vagrant ssh
```

You are now inside your ubuntu machine with git, terraform and the following docker commands available
`docker, docker-compose, docker-init, docker-proxy, dockerd, dockerd-ce`

The machine is also exposed to your host machine at ip 192.168.33.10
