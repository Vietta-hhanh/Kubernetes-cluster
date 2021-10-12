# Kubernetes-cluster
В директории What's behind this? представлено полное описание поставленной задачи проекта, тонкости реализации и условия выполнения.  
  
Перед запуском нужно предварительно установить: Minikube, Kubectl и VirtualBox. Приведу вариант установки для MacOS через HomeBrew:  
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" - установка HomeBrew  
brew install kubectl - установка kubectl  
brew install --cask virtualbox- установка VirtualBox  
brew install minikube - установка Minikube  
  
Если возникла необходимость в альтернативном варианте установки:  
Инструкция по установке для всех платформ: https://kubernetes.io/ru/docs/tasks/tools/install-minikube/  
  
Сборку кластера можно запустить командой: bash setup.sh  
minikube dashboard - после окончания сборки можно открыть интерфейс для работы с кластером  
!!! Сборка длится 10 - 15 минут !!!  
  
192.168.99.150 - Nginx  
192.168.99.150/phpmyadmin или 192.168.99.150:5000 - PhpMyAdmin (логин hhanh, пароль hhanh)  
192.168.99.150/wordpress или 192.168.99.150:5050 - WordPress  
192.168.99.150:3000 - Grafana (логин admin, пароль admin)  
minikube delete - удалить собранную сборку  
