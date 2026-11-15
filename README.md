# Cisco Packet Tracer Labs

Лабораторные работы по сетевым технологиям Cisco в Packet Tracer: конфиги, топологии (`.pkt`), скриншоты проверок и разбор типовых поломок.

## Структура

```
basics/      базовые лабы, с которых стоит начинать
  01-vlan/
  02-router-on-a-stick/
advanced/    комплексные проекты
  hsrp-etherchannel-gre-ipsec/
```

В каждой лабе одинаковый набор: `README.md` (цель, адресация, команды, проверка), `topology.pkt`, `configs/`, `screenshots/`.

## Базовые лабы

| # | Тема | Что отрабатывается |
| :-- | :-- | :-- |
| [01](basics/01-vlan/) | VLAN и 802.1Q Trunk | access-порты, транк между двумя коммутаторами, поломка и починка `allowed vlan` |
| [02](basics/02-router-on-a-stick/) | Router-on-a-Stick | маршрутизация между VLAN через подинтерфейсы `dot1Q` |

## Продвинутые проекты

| Проект | Что внутри |
| :-- | :-- |
| [HSRP + EtherChannel + GRE over IPsec](advanced/hsrp-etherchannel-gre-ipsec/) | отказоустойчивый шлюз HSRP, агрегированный L2-транк, DHCP, site-to-site туннель между штабом и филиалом |

## Как открыть

Файлы `topology.pkt` открываются в Cisco Packet Tracer. Конфиги в `configs/` можно прочитать как обычный текст.
