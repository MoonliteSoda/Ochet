# Для коррректной работы следует установить необходимый инструментарий.
# sudo apt install git # установка git
# sudo apt install apt-transport-https ca-certificates curl software-properties-common
# curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
# sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
# sudo apt install docker-ce -y # непосредственно установка docker
# sudo apt-get install docker-compose # установка docker-compose
# git clone https://github.com/MoonliteSoda/card2.git # создание копии репозитория по ссылке на сервере
# cat > card2/Dockerfile # напишем dockerfile, текст прикреплен в корне
# docker build -t cardc1 /card2/. # создание docker image с уазанием адреса
# docker image ls # выведет список образов
# docker run -it cardc1 # запуск контейнера
