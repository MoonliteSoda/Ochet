# Для коррректной работы следует установить необходимый инструментарий.
# sudo apt install git # установка git
# sudo apt install apt-transport-https ca-certificates curl software-properties-common # установка транспортного протокола для корректной работы docker
# curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - # загрузка ключа 
# sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" # добавление репозитория docker в систему
# sudo apt install docker-ce -y # непосредственно установка docker
# sudo apt-get install docker-compose # установка docker-compose
# git clone https://github.com/MoonliteSoda/card2.git # создание копии репозитория по ссылке на сервере
# cat > card2/Dockerfile # напишем dockerfile, текст прикреплен в корне
# docker build -t cardc1 /card2/. # создание docker image с уазанием адреса
# docker image ls # выведет список образов
# docker run -it cardc1 # запуск контейнера
вот тут у меня вылезла ошибка и дальше дело не пошло( почему-то одна из зависимостей не сработала.(не удалось найти модуль)
#HEAD 80/tcp # проверка порта 80/tcp в который должен выходить контейнер
#docker stop [id_conteiner] # остановка контейнера
ссылка на репозиторий проекта https://github.com/MoonliteSoda/card2

