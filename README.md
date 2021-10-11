Aptitude Mirror

```
Ubuntu 20.04 Focal Fossa
In Ubuntu 20.04, you can use the mirror by adding the following to the /etc/apt/sources.list file:

# Packages and Updates from the Hetzner Ubuntu Mirror
deb http://mirror.hetzner.com/ubuntu/packages focal           main restricted universe multiverse
deb http://mirror.hetzner.com/ubuntu/packages focal-updates   main restricted universe multiverse
deb http://mirror.hetzner.com/ubuntu/packages focal-backports main restricted universe multiverse
deb http://mirror.hetzner.com/ubuntu/packages focal-security  main restricted universe multiverse
Ubuntu 18.04 Bionic Beaver
In Ubuntu 18.04, you can use the mirror by adding the following to the /etc/apt/sources.list file:

# Packages and Updates from the Hetzner Ubuntu Mirror
deb http://mirror.hetzner.com/ubuntu/packages bionic           main restricted universe multiverse
deb http://mirror.hetzner.com/ubuntu/packages bionic-updates   main restricted universe multiverse
deb http://mirror.hetzner.com/ubuntu/packages bionic-backports main restricted universe multiverse
deb http://mirror.hetzner.com/ubuntu/packages bionic-security  main restricted universe multiverse
Ubuntu 16.04 Xenial Xerus
In Ubuntu 16.04, you can use the mirror by adding the following to the /etc/apt/sources.list file:

# Packages and Updates from the Hetzner Ubuntu Mirror
deb http://mirror.hetzner.de/ubuntu/packages xenial           main restricted universe multiverse
deb http://mirror.hetzner.de/ubuntu/packages xenial-updates   main restricted universe multiverse
deb http://mirror.hetzner.de/ubuntu/packages xenial-backports main restricted universe multiverse
deb http://mirror.hetzner.de/ubuntu/packages xenial-security  main restricted universe multiverse
Entry in preseed files
You can configure the Hetzner mirror in the preseed files as follows: (You can replace debian with ubuntu):

d-i mirror/http/hostname string mirror.hetzner.com
d-i mirror/http/directory string /debian/packages
```
