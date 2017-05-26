# packer-centos-7

## requirements:
1. https://www.vagrantup.com/ 
2. https://www.packer.io/
3. https://www.virtualbox.org/

## run

### Inspect the json
1. `packer-io inspect packer-virtualbox-centos-6_4-64.json` 

### Build Virtualbox vagrant box
`packer-io build packer-virtualbox-centos-6_4-64.json`

### Build VMware vmdk
`packer-io build packer-vmware-centos-6_4-64.json` 

## debuging

`PACKER_LOG=1 packer-io build packer-virtualbox-centos-6_4-64.json`

## Debugging each individual step
`packer-io -d build packer-virtualbox-centos-6_4-64.json`
