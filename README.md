# packer-centos-7

## requirements:
1. https://www.vagrantup.com/ 
2. https://www.packer.io/
3. https://www.virtualbox.org/

## run

1. `packer-io inspect packer-virtualbox-centos-6_4-64.json` 
1. `packer-io build packer-virtualbox-centos-6_4-64.json # virtualbox build` 
1. `packer-io build packer-vmware-centos-6_4-64.json # vmware build` 

## debuging

1. `PACKER_LOG=1 packer-io build packer-virtualbox-centos-6_4-64.json`

## Debugging each individual step
1. `packer-io -d build packer-virtualbox-centos-6_4-64.json`
