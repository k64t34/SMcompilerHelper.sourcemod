# MySMcompiler.2
==================

Помощник для компиляции SourceMod плагинов.

SourceMod compiler helper.

```sh

<folder>
 ├── game<plugin_folder>       # ``
    ├── addons
       ├── sourcemod
 └── mycmp.ini                 # `параметры компилятора`
```

##Changelog 
* Unreleased 
- fix rcon bug
* 1.0.5.3  
-  Autoclose app 
* 1.0.5.0  
 - Added.двойные кавычки в пути -D.  
* 1.0

Use hard datetime format in datetime.inc to prevent locale isses  like "Map_Elections" (╨Я╤В, 15.╨░╨┐╤А.2016 16:00:14) by KOM64T. 
Установлен жесткий формат даты и времени для избежания проблем с форматом локализации.

Add parameter MapReload. If MapReload=true, then server will _restart after plugin copy to server. 

В ini добавлен параметр MapReload. Если MapReload установить в true, то сервер будет перезагржен после копирования плагина на сервер.  

Add show plugin info after restart plugin in server.

* 0.3 1st Realese


##Plans

- [x] Удалять datetime.inc после компиляции
- [ ] Добавить в INI пункт сохранять или удалаять .err
- [ ] Добавить фильтр для исключения файлов для копирования на сервер
- [ ] Распозонвание простой структуры плагина
- [ ] need test  Наладить распознование абсолютных и относительных путей 
- [ ] Отображать как абсольные так и относительные пути
- [ ] Получать лог с сервера для слежения за плагинами 
- [ ] Добавить консоль сервера
- [x] При отсутствии действий в окне - закрыть через таймаут
- 


 
https://help.github.com/articles/basic-writing-and-formatting-syntax/
http://keepachangelog.com/ru/
Added для новых функций.
Changed для изменений в существующей функциональности.
Deprecated для функциональности, которая будет удалена в следующих версиях.
Removed для функциональности, которая удалена в этой версии.
Fixed для любых исправлений.
Security 
