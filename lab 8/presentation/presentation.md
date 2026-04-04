---
## Front matter
lang: ru-RU
title: Администрирование локальных сетей
subtitle: Лабораторная работа №8
author:
  - Абдуллахи Абдул Вахид
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 27 февраля 2026

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Цель 

## Цель лабораторной работы 

Освоение практических навыков настройки динамического распределения IP-адресов с использованием протокола DHCP (Dynamic Host Configuration Protocol) в локальной вычислительной сети.

# Выполнение лабораторной работы

## Схема сети

![топология сети](1-1.PNG){ width=75% }

## Настройка IP-адреса DNS-сервера

![Настройка IP-адреса DNS-сервера](2.PNG){ width=75% }

## Настройка DNS-сервиса

![Настройка DNS-сервиса](3.PNG){ width=75% }

## Настройка DHCP на маршрутизаторе

![Настройка DHCP на маршрутизаторе](4.PNG){ width=75% }

## получение IP-адреса по DHCP

![получение IP-адреса по DHCP](5.PNG){ width=75% }

## Проверка сетевой доступности

![Проверка сетевой доступности](6.PNG){ width=75% }

## Информация о пулах DHCP

![Информация о пулах DHCP](7.PNG){ width=75% }

## Таблица выданных DHCP-адресов

![Таблица выданных DHCP-адресов](8.PNG){ width=75% }

## DHCP Discover

![DHCP Discover](9.PNG){ width=75% }

## DHCP Offer

![DHCP Offer](10.PNG){ width=75% }

## DHCP Request

![DHCP Request](11.PNG){ width=75% }

## DHCP Acknowledgment (ACK)

![DHCP Acknowledgment (ACK)](12.PNG){ width=75% }

## Процесс обмена DHCP-сообщениями в режиме симуляции

![Процесс обмена](13.PNG){ width=75% }

# Вывод 

## Вывод 

В ходе работы был настроен DHCP-сервер на маршрутизаторе msk-donskaya-aabdullakhi-gw-1, созданы пулы адресов для четырёх подсетей. Оконечные устройства успешно получили IP-адреса динамически, а проверка ping подтвердила связность между подсетями. Процесс обмена сообщениями DHCP (Discover, Offer, Request, ACK) изучен в режиме симуляции.










