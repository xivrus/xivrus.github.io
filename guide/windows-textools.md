---
layout: page
title: Инструкции для Windows (TexTools)
---

Начиная с версии **0.5.8** формат модпака перешёл на Penumbra. На то были следующие причины:
* Такой метод установки мода не меняет игровые файлы
* Как следствие после обновления игры у вас нулевой шанс, что испортятся игровые файлы
* Не требуется устанавливать дополнительный софт, если вы уже используете XIVLauncher
* В модпаки Penumbra можно паковать любые игровые файлы --- это значит, например, что мы сможем менять текстуры интерфейса и даже озвучку
* Модпаки Penumbra на порядок проще и быстрее собираются, чем модпаки TexTools

Penumbra не идеальна. В отличие от TexTools у неё следующие минусы:
* Зависимость от Dalamud. При обновлении игры плагины некоторое время не работают, так как они должны быть обновлены под новую версию игры. Обычно на это уходит 1--3 дня, но вполне может быть и больше. Релиз новых версий перевода, как следствие, тоже будет задерживаться
* Процедура первой установки Penumbra немного сложнее. Однако если чётко следовать инструкции, то проблем не возникнет

В **TexTools 3.0** теперь есть поддержка модпаков Penumbra. Мы **не рекомендуем и не поддерживаем** такой способ установки и предоставляем его для тех, кто очень не хочет использовать неофициальный лаунчер или по каким-либо другим причинам.

> Отсутствие поддержки от нас означает, что **мы не будем помогать, если в результате ваших манипуляций или глюков самого TexTools что-то сломается**. Поскольку, в отличие от Penumbra, TexTools заменяет файлы наживую, в случае поломок может потребоваться проводить починку файлов игры через лаунчер, а в худшем случае и вовсе переустановить игру.

Также имейте в виду, что **строго не рекомендуется смешивать моды Penumbra и TexTools**. То есть во избежание проблем следует использовать либо Penumbra, либо TexTools.

# Установка {#install}

## Установка TexTools {#install-textools}

**Шаг 1.** Перейдите на сайт TexTools (<https://www.ffxiv-textools.net/>) и скачайте установщик по кнопке **Download TexTools**.

![Установка TexTools - 01](/assets/img/textools/install-01.png)

**Шаг 2.** Установите TexTools. Мастер установки стандартный и позволяет только выбрать место установки самого TexTools. Оно не имеет значение, его можно установить в любое место. Сами моды будут устанавливаться в папку игры.

![Установка TexTools - 02](/assets/img/textools/install-02.png)

**Шаг 3.** Запустите TexTools --- появится мастер первой настройки.

1. Укажите папку игры, нажав на **Select Folder** напротив **FFXIV Install**.\
   Если вы не меняли место установки FINAL FANTASY XIV, то по умолчанию путь следующий:
   * версия **Steam** --- `C:\Program Files (x86)\Steam\steamapps\common\FINAL FANTASY XIV Online`
   * версия **не Steam** --- `C:\Program Files (x86)\SquareEnix\FINAL FANTASY XIV - A Realm Reborn`
2. Убедитесь, что установлен **английский** язык игры. Русификатор работае за счёт замены именно английских файлов игры.
3. Напротив **I want to (Primarily)** выберите **Install or Use Mods**. Согласитесь с предупреждением, нажав **OK**.

![Установка TexTools - 03](/assets/img/textools/install-03.png)

Перевод предупреждения:

> _Пожалуйста, имейте в виду, что хоть TexTools и МОЖЕТ работать загрузчиком модов, это не является его главной целью._
>
> _Вы скорее всего обнаружите, что некоторый функционал, связанный с загрузкой модов, неудобен, по сравнению с другими загрузчиками модов (например, Penumbra)._

Обратите внимание, что сами разработчики TexTools **больше не рекомендуют использовать TexTools для установки модификаций** и больше позиционируют TexTools как инструмент для создателей модификаций. Мы в свою очередь тоже настоятельно рекомендуем на данном этапе ещё раз подумать об использовании Penumbra вместо TexTools. Инструкция по установке находится через Penumbra находится [здесь](/guide/windows).

![Установка TexTools - 04](/assets/img/textools/install-04.png)

После указания настроек нажмите **OK** и дождитесь, когда TexTools создаст свой кэш.

**TexTools установлен и готов к работе.**

## Установка модпака {#install-modpack}

**Шаг 1.** Скачайте модпак здесь: <https://xivrus.ru/download>.\
Далее в TexTools перейдите в **Mods** > **Import ModPacks**. В появившемся окне укажите на скачанный модпак.

![Установка модпака - 01](/assets/img/textools/modpack/install-01.png)

**Шаг 2.** Дождитесь загрузки содержимого модпака. Это займёт некоторое время.

![Установка модпака - 02](/assets/img/textools/modpack/install-02.png)

**Шаг 3.** В появившемся окне информации о модпаке нажмите **Import Files** и дождитесь окончания установки. Это займёт некоторое время.

![Установка модпака - 03](/assets/img/textools/modpack/install-03.png)

> Обратите внимание, что в Penumbra модпак устанавливается на порядок быстрее.

Готово. Модпак установлен, теперь игра на русском языке.

# Обновление {#update}



# Удаление {#uninstall}