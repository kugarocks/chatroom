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
- [x] Themes: Minions(Default), ONEPIECE.

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

| Luffy                         | Zoro                         | Nami                         |
|:-----------------------------:|:----------------------------:|:----------------------------:|
| ![Luffy](img/onepiece/luffy.jpg) | ![Zoro](img/onepiece/zoro.jpg) | ![Nami](img/onepiece/nami.jpg) |

| Usopp                         | Sanji                          | Chopper                            |
|:-----------------------------:|:------------------------------:|:----------------------------------:|
| ![Usopp](img/onepiece/usopp.jpg) | ![Sanji](img/onepiece/sanji.jpg) | ![Chopper](img/onepiece/chopper.jpg) |

| Robin                         | Franky                           | Brook                          |
|:-----------------------------:|:--------------------------------:|:------------------------------:|
| ![Robin](img/onepiece/robin.jpg) | ![Franky](img/onepiece/franky.jpg) | ![Brook](img/onepiece/brook.jpg) |
