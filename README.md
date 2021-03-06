
# Vagrant Nginx

A Vagrant box based containing Ubuntu linux and Nginx. Provisioned with puppet and ready to deploy. 

Fork us:   
[https://github.com/obihann/vagrant-nginx/](https://github.com/obihann/vagrant-nginx/)

Download the latest box:   
[https://atlas.hashicorp.com/obihann/boxes/nginx/](https://atlas.hashicorp.com/obihann/boxes/nginx/)

Install the latest box:   
```$ vagrant init obihann/nginx; vagrant up --provider virtualbox```

## Useful Info

### Software Versions

- Ubuntu 12.04 LTS
- puppet 3.8.7
- git 1.7.9.5
- python 2.7.3
- perl 5.14.2
- ruby 1.8.7
- nginx 1.1.19

### Base Image

- [hashicorp/precise64](https://atlas.hashicorp.com/hashicorp/boxes/precise64)

### Puppet Modules

- [puppetlabs/puppetlabs-apt](https://github.com/puppetlabs/puppetlabs-apt)
- [puppetlabs/puppetlabs-stdlib](https://github.com/puppetlabs/puppetlabs-stdlib/)

##License
This tool is protected by the [GNU General Public License v2](http://www.gnu.org/licenses/gpl-2.0.html).

Copyright [Jeffrey Hann](http://jeffreyhann.ca/) 2016
