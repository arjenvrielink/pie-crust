Pie Crust
=========
Infrastructure project to test different configuration management frameworks in combination with Vagrant

Setup
-----
You need `Vagrant`, `ansible` and `ansible-vagrant` to get up and running::

    sudo gem install vagrant
    sudo gem install vagrant-ansible
    sudo pip install ansible

Add this repository to your codebase and run vagrant::

    git sub-module add https://github.com/arjenvrielink/pie-crust
    vagrant up

Now you should be good to go with an up and running Debian 7 server running nginx, gunicorn / tilestache, redis
