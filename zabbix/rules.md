---
title: Принципы работы
layout: default
parent: Интеграция Zabbix
nav_order: 1
---
**NetStare** работает с системой Zabbix на следующих принципах:
{: .important-title }
> Принципы
>
> 1. Работа на основе ID
> 2. Для блока Устройств обрабатываются только непустые группы
> 3. Для блока Проблем обрабатываются только проблемные группы
> 4. Фильтрация узлов и элементов данных производится по наличию тега 'netstare': 'true'
![screenshot](../images/host-tag.png)
![screenshot](../images/item-tag.png)