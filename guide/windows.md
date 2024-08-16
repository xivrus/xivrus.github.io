---
layout: page
title: Инструкции для Windows
---

# Установка {#install}

Видео-инструкция от [Art Radio](https://www.youtube.com/@ArtRadio_FFXIV):

{% include youtubePlayer.html id = "G5VP2aVvb8E" %}

***

Локализация является модпаком для плагина Penumbra. Установка выполняется в 3 шага:
1. [Установка неофициального лаунчера XIVLauncher](#install-xivlauncher)
2. [Установка плагина Penumbra](#install-penumbra)
3. [Установка модпака](#import-modpack)

## 1. Установка XIVLauncher {#install-xivlauncher}

### О лаунчере {#install-xivlauncher-about}

![XIVLauncher logo](https://goatcorp.github.io/header.png)

[**XIVLauncher**](https://goatcorp.github.io/) --- это неофициальный лаунчер FINAL FANTASY XIV с открытым исходным кодом. Он направлен на улучшение в скорости работы по сравнению с официальным лаунчером. Его плюсы:
* Возможность запоминать пароль (вход по одноразовому паролю тоже поддерживается)
* Более быстрое обновление игры за счёт параллельной загрузки файлов патча
* Более быстрая починка файлов игры за счёт загрузки только испорченных файлов, а не всей игры
* Dalamud --- система внутриигровых плагинов, которые улучшают и расширяют игровой процесс

Penumbra является как раз плагином для Dalamud, потому для игры на русском языке её нужно запускать через XIVLauncher.

Если у вас остались вопросы касательно XIVLauncher, обратитесь к [FAQ](/faq).

Если вы уже используете XIVLauncher, то убедитесь в нём, что игра стоит на английском языке и Dalamud включён, после чего переходите сразу к [шагу 2](#install-penumbra).

### Инструкция {#install-xivlauncher-guide}

Перейдите на сайт XIVLauncher (<https://goatcorp.github.io/>) и нажмите **Download XIVLauncher**.

![Установка XIVLauncher - 1](/assets/img/windows/install-01.png)

Под списком изменений нажмите **Assets** и загрузите установщик **Setup.exe**.

![Установка XIVLauncher - 2](/assets/img/windows/install-02.png)

В появившемся окне требуется указать, куда установлена игра. Если вы не меняли место установки FINAL FANTASY XIV, то по умолчанию путь следующий:
* версия **Steam** --- `C:\Program Files (x86)\Steam\steamapps\common\FINAL FANTASY XIV Online`
* версия **не Steam** --- `C:\Program Files (x86)\SquareEnix\FINAL FANTASY XIV - A Realm Reborn`

Если у вас версия Steam, то нужно вдобавок пометить галочку **Включить интеграцию со Steam**.\
Нажмите **Далее**.

![Установка XIVLauncher - 3](/assets/img/windows/install-03.png)

Выберите обязательно **английский** язык игры и нажмите **Далее**. Локализация работает за счёт замены именно английских файлов игры.

![Установка XIVLauncher - 5](/assets/img/windows/install-04.png)

Поставьте галочку напротив **Включить Dalamud** и нажмите **Далее**.

![Установка XIVLauncher - 6](/assets/img/windows/install-05.png)

**XIVLauncher установлен.**

В поля **Username** и **Пароль** требуется ввести логин и пароль от вашего аккаунта SQUARE ENIX (не Steam!).\
Если хотите сразу входить в игру без ввода пароля, то поставьте галочку напротив **Автоматический вход**.\
Если вы используете двухфакторную авторизацию, то поставьте галочку напротив **Одноразовый пароль**.\
Если у вас Steam-версия, то нужно пометить галочку напротив **Аккаунт Steam**.

![Установка XIVLauncher - 7](/assets/img/windows/install-06.png)

Если вы не купили игру и играете во **Free Trial**, то нужно перейти в **Настройки** (значок шестерёнки). Оттуда перейдите во вкладку **Настройки игры**, поставьте галочку напротив **Using free trial account** и нажмите справа-внизу галочку для сохранения.\
После того, как купите игру, не забудьте убрать эту галочку, иначе всё равно будет запускаться Free Trial.

![Установка XIVLauncher - 8](/assets/img/windows/install-07.png)

Если вы в первый раз запускаете игру, купленную в Steam, то это нужно сделать сначала через официальный лаунчер, чтобы совершить привязку вашего аккаунта Steam к вашему аккаунту SQUARE ENIX.

Если вы хотите запускать XIVLauncher прямо из Steam, чтобы иметь оверлей Steam и чтобы Steam продолжал считать наигранные вами часы, то выполните шаги из FAQ разработчика: <https://goatcorp.github.io/faq/xl_troubleshooting#q-whats-the-deal-with-steam-support>.

## 2. Установка Penumbra {#install-penumbra}

{% include guide/penumbra.md %}

## 3. Установка модпака {#install-modpack}

{% include guide/modpack-install.md %}

# Обновление {#update}

---

{% include guide/modpack-update.md %}

# Удаление {#uninstall}

## Я хочу удалить только модпак {#uninstall-modpack}

{% include guide/modpack-uninstall.md %}

**После перезапуска игры она будет снова на английском языке.**

## Я хочу удалить всё {#uninstall-everything}

Удалите модпак по инструкции выше.\
После этого выйдите из игры и удалите в системе XIVLauncher.

![Удаление всего - 1](/assets/img/windows/uninstall-01.png)

Программа удаления спросит, хотите ли вы также удалить настройки XIVLauncher и плагинов, сами плагины и пароли --- сделайте выбор, нажав **Да** или **Нет**.

![Удаление всего - 2](/assets/img/windows/uninstall-02.png)

После этого **папка с модами сама не удаляется**, поэтому если вы хотите её тоже удалить, то **удалите её вручную**.

Если вы настраивали в Steam'е запуск игры через XIVLauncher, то просто очистите у игры опции запуска.

**Готово, модпак и всё, что связаны с ним, удалены.**

---

**Что-то не работает? Обратитесь к [FAQ](/faq).**