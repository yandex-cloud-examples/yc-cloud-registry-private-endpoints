# Подключение к Yandex Cloud Registry из сети Yandex Virtual Private Cloud без доступа в интернет

Разверните в Yandex Cloud облачную инфраструктуру для организации доступа к реестру Cloud Registry с ресурсов, которые размещены в облачной сети Virtual Private Cloud (VPC) и не имеют доступа в интернет.

Приватная сетевая связность ресурсов в облачной сети с сервисом Cloud Registry будет организована с использованием сервисных подключений (private endpoints) VPC.

Настройка описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/routing/cloud-registry-via-pe/). В репозитории хранятся конфигурационные файлы для развертывания инфраструктуры с помощью Terraform.
