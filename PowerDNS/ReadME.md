Данный шаблоны основаны на следующих проектах:
https://zabbix.org/wiki/PowerDNS_Authoritative_Server и https://github.com/kometchtech/Zabbix_Template_PowerDNS_recursor 

Шаблон тестировался на FreeBSD 10.2 и Zabbix 2.4.6 

Мной были внесены следующие изменения:

1) Мониторинг процесса pdns_recursor и тригер, сообщающий о том, что процесс не доступен

2) Создан график, отображающий колличество запросов "всего" и из кэша 

3) Мониторинг процесса pdns и тригер, сообщающий о том, что процесс не доступен


Описание размещено на https://forum.cz6.ru/viewtopic.php?f=24&t=199
