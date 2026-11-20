# Подключение к Yandex Cloud Registry из сети Yandex Virtual Private Cloud без доступа в интернет

В этом руководстве вы развернете в Yandex Cloud облачную инфраструктуру для организации доступа к [реестру](https://yandex.cloud/ru/docs/cloud-registry/concepts/registry) Yandex Cloud Registry с ресурсов, которые размещены в облачной сети [Yandex Virtual Private Cloud](https://yandex.cloud/ru/docs/vpc/index) (VPC) и не имеют доступа в интернет.

Приватная сетевая связность ресурсов в облачной сети с сервисом Cloud Registry будет организована с использованием [сервисных подключений](https://yandex.cloud/ru/docs/vpc/concepts/private-endpoint) (_private endpoints_) Virtual Private Cloud.

Подготовка инфраструктуры для подключения к Cloud Registry из облачной сети VPC без доступа в интернет описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/routing/cloud-registry-via-pe/). Необходимые для развертывания инфраструктуры конфигурационные файлы (`cloud-registry-via-pe.tf` и `cloud-registry-via-pe.auto.tfvars`) расположены в этом репозитории.
