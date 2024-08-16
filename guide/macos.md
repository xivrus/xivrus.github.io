---
layout: page
title: Инструкции для macOS
---

# Установка {#install}

Локализация является модпаком для плагина Penumbra. Установка выполняется в 3 шага:
1. [Установка и настройка неофициального лаунчера XIV&nbsp;on&nbsp;Mac](#install-xivonmac)
2. [Установка плагина Penumbra](#install-penumbra)
3. [Установка модпака](#install-modpack)

## 1. Установка и настройка XIV&nbsp;on&nbsp;Mac {#install-xivonmac}

### О лаунчере {#install-xivonmac-about}

![XIV&nbsp;on&nbsp;Mac logo](https://www.xivmac.com/sites/default/files/logo.png)

[**XIV&nbsp;on&nbsp;Mac**](https://www.xivmac.com/) --- это неофициальный лаунчер FINAL FANTASY XIV с открытым исходным кодом для macOS. Он направлен на улучшение в скорости работы по сравнению с официальным лаунчером. Его плюсы:
* Значительный прирост производительности игры
* Возможность использовать лицензию игры не только для Mac, но и для Windows и Steam
* Возможность запоминать пароль (вход по одноразовому паролю тоже поддерживается)
* Более быстрое обновление игры за счёт параллельной загрузки файлов патча (механизм XIVLauncher)
* Более быстрая починка файлов игры за счёт загрузки только испорченных файлов, а не всей игры
* Поддержка Dalamud --- система внутриигровых плагинов, которые улучшают и расширяют игровой процесс

Penumbra является как раз плагином для Dalamud, потому для игры на русском языке её нужно запускать через XIV&nbsp;on&nbsp;Mac.

Если у вас остались вопросы касательно XIVLauncher, обратитесь к [официальному сайту лаунчера](https://www.xivmac.com/).

Если вы уже используете XIV&nbsp;on&nbsp;Mac, то убедитесь в нём, что:
1. Игра стоит на английском языке
2. В настройках лаунчера включён Dalamud
3. **(Важно!)** Там же, рядом с Dalamud включён Entrypoint

После чего переходите сразу к [шагу 2](#install-penumbra).

### Инструкция {#install-xivonmac-guide}

**Шаг 1.** Перейдите на сайт XIV&nbsp;on&nbsp;Mac (<https://www.xivmac.com/>) и нажмите **Download - Beta \<версия\>**.

![Установка XIV&nbsp;on&nbsp;Mac - 01](/assets/img/macos/install-01.png)

**Шаг 2.** Будет скачан архив. Перейдите в Загрузки и откройте его.

![Установка XIV&nbsp;on&nbsp;Mac - 02](/assets/img/macos/install-02.png)

**Шаг 3.** Рядом с архивом появится `XIV on Mac.app` --- перетащите его в <<Программы>>.

![Установка XIV&nbsp;on&nbsp;Mac - 03](/assets/img/macos/install-03.png)

**Шаг 4.** Лаунчер появится в Launchpad в папке <<Игры>> --- запустите его.

![Установка XIV&nbsp;on&nbsp;Mac - 04](/assets/img/macos/install-04.png)

**Шаг 5.** Появится предупреждение от macOS --- согласитесь на запуск.

![Установка XIV&nbsp;on&nbsp;Mac - 05](/assets/img/macos/install-05.png)

Лаунчер будет открыт, он выглядит следующим образом:

![Установка XIV&nbsp;on&nbsp;Mac - 06](/assets/img/macos/install-06.png)

**Шаг 5.** Откройте настройки лаунчера через сочетание клавиш&nbsp;&nbsp;**⌘,**&nbsp;&nbsp;или выбрав в верхнем меню **XIV&nbsp;on&nbsp;Mac** > **Settings...**

![Установка XIV&nbsp;on&nbsp;Mac - 07](/assets/img/macos/install-07.png)

**Шаг 6.** Во вкладке **General** убедитесь, что язык игры стоит на **English**. Выберите желаемый тип лицензии и пометьте галочку **Free Trial**, если Вы ещё не купили игру.

**ВАЖНО для Steam!** Для лицензии Steam (в т.ч. Free Trial) требуется следующее:
* Совершить привязку аккаунта SQUARE ENIX к аккаунту Steam
  * Этот шаг **необходимо сделать на Windows** через официальный лаунчер
* Иметь Steam запущенным перед каждым запуском игры

![Установка XIV&nbsp;on&nbsp;Mac - 08](/assets/img/macos/install-08.png)

**Шаг 7.** Во вкладке **Plugins (Dalamud)** поставить галочки у **Enable Dalamud** и **Entrypoint**.

![Установка XIV&nbsp;on&nbsp;Mac - 09](/assets/img/macos/install-09.png)

**Шаг 8.** (опционально) Во вкладке **Advanced** выключить опцию **Quit XIV&nbsp;on&nbsp;Mac upon game exit** (<<Выходить из XIV&nbsp;on&nbsp;Mac после закрытия игры>>).

> **Для чего это может быть нужно?**
> * Для обновления перевода требуется перезапускать игру.
> * Dalamud позволяет перезапускать игру через команду `/xlrestart`. Такой перезапуск игры быстрый и не требует повторного входа, что особенно полезно, если стоит двухфакторная авторизация по одноразовому коду.
> * Когда опция <<Quit XIV&nbsp;on&nbsp;Mac upon game exit>> включена, перезапуск по такой команде не происходит, поскольку лаунчер закрывается.

![Установка XIV&nbsp;on&nbsp;Mac - 10](/assets/img/macos/install-10.png)

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
После этого выйдите из игры и удалите из системы XIV&nbsp;on&nbsp;Mac. Для этого перейдите в папку **Программы**, найдите там **XIV&nbsp;on&nbsp;Mac.app** и удалите его.

![Удаление XIV&nbsp;on&nbsp;Mac - 01](/assets/img/macos/uninstall-01.png)

**Готово, лаунчер удалён.**

Имейте в виду, что от этого **удаляется только лаунчер**. Сама **игра, настройки XIV&nbsp;on&nbsp;Mac, Dalamud и всех плагинов остаются**. Они находятся в `~/Library/Application Support/XIV on Mac`.\
Если Вы хотите удалить и это, то перейдите в папку `~/Library/Application Support`. Это можно сделать, например, вставив этот путь в Spotlight:

![Удаление XIV&nbsp;on&nbsp;Mac - 02](/assets/img/macos/uninstall-02.png)

Найдите папку <<XIV&nbsp;on&nbsp;Mac>> и удалите её.

![Удаление XIV&nbsp;on&nbsp;Mac - 03](/assets/img/macos/uninstall-03.png)

**Готово, игра и все связанные с ней и лаунчером настройки удалены.**