Д3 №1
Настройка prometheus и exporters + CMS

Описание
В репозитории находится структура файлов настроек prometheus для VM/Baremetal вариантов установки.
Весь стек: nginx + MySql + php-fpm + BoltCMS. Экспортеры: blackbox, nginx, mysql, node, php-fpm

Структура каталогов

/etc/systemd/system - unit-файлы с настройками для запуска exporter в качестве службы
/etc/prometheus/ - папка с настройками prometheus и дополнительными конфигурационными файлами для exporter
