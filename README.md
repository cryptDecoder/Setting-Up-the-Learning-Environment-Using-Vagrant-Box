# Setting-Up-the-Learning-Environment-Using-Vagrant-Box

We are using Vagrant Box to configure our environment.
For our ansible training we are using the

---

### We are using following configuration

- Two Database Server (1 Ubuntu and 1 CentOS)
- One Web Server
- One Load Balancer

---

### Ansible Controller Configuration

- Host OS

| Distributor ID |       Ubuntu       |
| :------------: | :----------------: |
|  Description   | Ubuntu 20.04.2 LTS |

- ### Ansible Version
  ansible 2.9.6 <br />
  ansible python module location = /usr/lib/python3/dist-packages/ansible <br />
  executable location = /usr/bin/ansible <br />
  python version = 3.8.5 (default, Jan 27 2021, 15:41:15) [GCC 9.3.0]
  ***

## Working With Vagrant

Vagrant is a open source software product that we are using the building the our required the servers

### Vagrant Commands we are using

---

```
1. vagrant init : This command is used to initialize the vagrant box, it includes the networking, CPU and memory

```

---

```
2. Vagrant up : in order to get box up and running
```

---

```
3. vagrant ssh :  as per name suggest it will uses to make SSH connection to box.
```

---

```
4.  vagrant destroy : destroy the provisioned box.

```

for more details visit the <br />🔗 https://blog.ipswitch.com/5-vagrant-commands-you-need-to-know

🔚
