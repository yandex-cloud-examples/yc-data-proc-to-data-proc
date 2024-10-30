# Совместная работа с таблицами в Yandex Data Processing с использованием Metastore

Вы можете сохранять данные из кластера [Yandex Data Processing](https://yandex.cloud/ru/docs/data-proc) в бакет [Yandex Object Storage](https://yandex.cloud/ru/docs/storage) с помощью отдельного кластера Hive Metastore для хранения метаданных таблиц. Это позволит работать с сохраненными данными другому кластеру Yandex Data Processing, имеющему доступ к бакету и подключенному к тому же кластеру Metastore. Подготовка инфраструктуры для Yandex Data Processing и Object Storage через Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/data-proc/tutorials/dataproc-to-dataproc), необходимый для настройки конфигурационный файл [dataproc-to-dataproc.tf](dataproc-to-dataproc.tf) расположен в этом репозитории.
