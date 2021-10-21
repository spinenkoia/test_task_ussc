# Тестовое задание USSC

Необходимо разработать парсер протокола [Browser](browser.pcap)(часть SMB)

Пример вывода:
```text
src_mac: 00:0a:f7:18:5f:43
dst_mac: ff:ff:ff:ff:ff:ff
src_ip: 192.168.15.3
dst_ip: 192.168.15.255
src_port: 138
dst_port: 138
source_name: ARM2<00>
destination_name: <01><02>__MSBROWSE__<02><01>
domain: WORKGROUP
```

Разбирать протокол необходимо с учетом устройства протокола.
Все возможные варианты парсинга учитывать не нужно (как в RFC), 
только достаточные для разбора pcap файла.
