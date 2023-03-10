# Инструкции

* [Как начать Vagrant](vagrant_quick_start.md)

## otus-linux

Используйте этот [Vagrantfile](Vagrantfile) - для тестового стенда.

## Что нужно сделать?

1. добавить в Vagrantfile еще дисков
1. сломать/починить raid
1. собрать R10
1. прописать собранный рейд в /etc/mdadm/mdadm.conf
1. создать GPT раздел и 5 партиций

Дополнительное задание:
1. Vagrantfile, который сразу собирает систему с подключенным рейдом и смонтированными разделами. После перезагрузки стенда разделы должны автоматически примонтироваться