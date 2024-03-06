# Зеркала Vagrant
  
https://hashicorp-releases.yandexcloud.net/vagrant/  
https://hashicorp-releases.mcs.mail.ru/vagrant/  
  
### Vagrantfile
Указать зеркало нужно в переменной VAGRANT_SERVER_URL  

VAGRANT_SERVER_URL="https://hashicorp-releases.yandexcloud.net/vagrant/"

### Пример Vagrantfile:


```
# -*- mode: ruby -*-
# vi: set ft=ruby :
```
ENV['VAGRANT_SERVER_URL']="https://hashicorp-releases.yandexcloud.net/vagrant/"
```
Vagrant.configure("2") do |config|
  # config.vm.box = "ubuntu/xenial64"
  # ... ну и так далее -- ваша конфигурация
end
```
