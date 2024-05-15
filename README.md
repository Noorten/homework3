# homework3
Скачиваем
Vagrant up
далее делаем запрос vagrant ssh-config
от туда забираем информацию о порте и пути ключа
заменяем соотвествующую информацию в файле hosts по пути ./staging/hosts
запускаем плей ansibl-playbook nginx.yml
заходим на вм по ssh
проверяем что все работает curl http://192.168.11.150:8080
