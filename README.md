# Vagrant Boxes

Simple local stacks for developers using Vagrant and VirtualBox. 2 boxes. Same specifications, but you can use either Apache or NGINX.

Current box versions

LAMP : 1.0.0

LEMP : 1.0.0

## System Specifications

* CentOS
* Apache/NGINX
* MySQL
* PHP
* Ruby
* Node
* Git
* Composer
* NPM
* Bower
* Gulp
* Grunt
* Webpack
* Browserify
* Browsersync
* Yeoman
* PM2

## Instructions

You will want to make sure your system has the latest versions of VirtualBox and Vagrant installed before starting.

[Download VirtualBox](https://www.virtualbox.org/wiki/Downloads)

[Download Vagrant](https://www.vagrantup.com/downloads.html)

Then you can go ahead and clone the repository.

```
git clone https://github.com/jacobcalata/vagrant-boxes.git
```

cd into the repository directory then into the directory of the box you want to use.

```
cd <folder name>/<apache or nginx>
```

Remember to edit your Vagrantfile to match your directory structure.

Now you can boot up your machine

```
vagrant up
```

Then SSH into your server

```
vagrant ssh
```

## Notes

### IP : 192.168.33.10
### SSH password : vagrant
### Database password : vagrant

You can delete the box by running the following command

```
vagrant destroy
```

You can update the box by running the following command

```
vagrant box update
```

You can check the [documentation](https://docs.vagrantup.com/v2/getting-started/) if you have any Vagrant questions.
