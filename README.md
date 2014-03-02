openstack-deb-builder
=====================

Script to automatically build OpenStack packages from source

Based on [xiaoquqi's script](https://github.com/xiaoquqi/vagrant-build-openstack-deb/blob/master/scripts/build.sh)

## Prerequistics
### Ubuntu Cloud Archive
Some build dependencies only exists there.
```
sudo add-apt-repository cloud-archive:havana
sudo apt-get update
```

### Build tools
```
sudo apt-get install -y debootstrap equivs schroot devscripts build-essential checkinstall sbuild \
  dh-make bzr bzr-builddeb git python-setuptools
```

### pip & pbr
```
sudo apt-get install -y python-pip
sudo pip install pbr
```

## TODO
* Build multiple packages
