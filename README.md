# zabbix_template_memcached

memcached Template for Zabbix ~> 3.4.

Necessary "Dependent Item". Put userparameter_memcached.conf in Include-UserParameter's Directory.

- ZABBIX 3.4用 memcachedのテンプレートです。
- UserParameterのワインライナーでstatsをJSON化して、依存アイテムで各値を入れてます。アイテムに設定してないのもあります。
- telnetでmemcachedたたいているので、CentOSとかは入れてください。
- FreeBSD11/CentOS7.1以上で動きます。

このテンプレートはMIT Licenseです。
