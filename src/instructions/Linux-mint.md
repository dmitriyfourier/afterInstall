---
layout: post
title: Что делать после установки Linux Mint 
desc: Инструкция по версии Димы Фурье
date: 2023-11-13
update: 2024-02-05
url: linux-mint
cover: "horizontal-mgmt-OG.png"
permalink: "/instructions/{{ url | slug }}/"
main-page: "https://linuxmint.com/"
distrowatch: "https://distrowatch.com/table.php?distribution=mint"
---

## Шаг 1

```bash
sudo apt update && sudo apt upgrade -y
```

## Шаг 2 Установить кодеки
```bash
sudo apt install mint-meta-codecs -y
```


## Шаг 3 Установка FlatHub
https://flathub.org/

```bash
sudo apt-get install flatpak -y
```
```bash
sudo add-apt-repository ppa:flatpak/stable
sudo apt update
sudo apt install flatpak
```

## Шаг 4

## шаг 5