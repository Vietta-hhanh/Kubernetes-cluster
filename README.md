# Kubernetes-cluster
В директории What's behind this? представлено полное описание поставленной задачи проекта, тонкости реализации и условия выполнения.

Перед запуском нужно предварительно установить: Docker, Minikube, Kubectl и VirtualBox. Приведу вариант установки для MacOS через HomeBrew:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" - установка HomeBrew
brew cask install docker - установка Docker
brew install kubectl - установка kubectl
brew install --cask virtualbox- установка VirtualBox
brew install minikube - установка Minikube

Если возникла необходимость в альтернативном варианте установки:
Инструкция по установке Docker для всех платформ: https://docs.docker.com/desktop/
Инструкция по установке всего остального для всех платформ: https://kubernetes.io/ru/docs/tasks/tools/install-minikube/

Сборку кластера можно запустить командой: bash setup.sh
После окончания сборки можно открыть интерфейс для работы с кластером minikube dashboard

!!! Сборка длится 10 - 15 минут !!!
