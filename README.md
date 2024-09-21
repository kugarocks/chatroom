Mini Chat
=========

Terminal-style chat room created by Cursor.

![Demo](img/onepiece/demo.png)

Live Demo
---------

[https://minichat.kugarocks.com](https://minichat.kugarocks.com)

Features
--------

- [x] Multi-line messages.
- [x] Copy messages.
- [x] Resize chat area.
- [x] Themes: Minions(Default), OnePiece.

Setup
-----

Default theme is Minions.

```bash
go run main.go
```

Specify the theme:

```bash
go run main.go -theme onepiece
```

Use SSL:

```bash
go run main.go -ssl -cert ./cert.pem -key ./key.pem
```

Open `index.html` in browser.

Minions
--------

| Stuart                         | Kevin                         | Bob                         | Dave                         |
|:------------------------------:|:-----------------------------:|:---------------------------:|:----------------------------:|
| ![Stuart](img/minions/stuart.jpg) | ![Kevin](img/minions/kevin.jpg) | ![Bob](img/minions/bob.jpg) | ![Dave](img/minions/dave.jpg) |

| Jerry                         | Phil                         | Tim                         | Mark                         |
|:-----------------------------:|:----------------------------:|:---------------------------:|:----------------------------:|
| ![Jerry](img/minions/jerry.jpg) | ![Phil](img/minions/phil.jpg) | ![Tim](img/minions/tim.jpg) | ![Mark](img/minions/mark.jpg) |

ONPIECE
---------

| 路飞                         | 索隆                         | 娜美                         |
|:---------------------------:|:---------------------------:|:---------------------------:|
| ![路飞](img/onepiece/luffy.jpg) | ![索隆](img/onepiece/zoro.jpg) | ![娜美](img/onepiece/nami.jpg) |

| 乌索普                         | 山治                          | 乔巴                            |
|:----------------------------:|:----------------------------:|:------------------------------:|
| ![乌索普](img/onepiece/usopp.jpg) | ![山治](img/onepiece/sanji.jpg) | ![乔巴](img/onepiece/chopper.jpg) |

| 罗宾                         | 弗兰奇                           | 布鲁克                          |
|:---------------------------:|:-------------------------------:|:-----------------------------:|
| ![罗宾](img/onepiece/robin.jpg) | ![弗兰奇](img/onepiece/franky.jpg) | ![布鲁克](img/onepiece/brook.jpg) |
