## Script for installation and configuration of the X-ray kernel without a graphical interface
<br/>
UPD 24.04.2026:<br/>
Добавил блокировку распространённых RU доменов (яндексы, вк, максы, рутубы, госуслуги, банки и т.д.), при нужне зайти на эти сайты, добавляем в исключения в настройках Firefox/proxy switch omega, либо пользуемся отдельным браузером для RU сервисов.<br/>
По умолчанию маскировка настроена на www.dropbox.com (при желании можно поменять).<br/>
Vless xhttp reality с последними протоколами и всеми стандартами, включая сниффинг.<br/>
<br/>
<br/>
Скрипт-форк для автоматической установки чистого xray-core с авторазвёртыванием готового конфига vless xhttp reality + shadowsocks-2022 в одну команду и выводом оных готовой конфиг-ссылкой и qr-кодом.<br/>
Подходит в т.ч. для абсолютно голых только что купленных серверов (всё что нужно обновляет и ставит сам).
<br/>
<br/>
<img width="2040" height="1072" alt="www" src="https://github.com/user-attachments/assets/735030b3-916f-4afe-8322-5190a9db1e8c" />

## Установка VLESS XHTTP REALITY + SHADOWSOCKS
Установка производится следующей командой:
```sh
wget -qO- https://raw.githubusercontent.com/mormaus301/xray-xhttp-install/main/xhttp-xray-install | bash
```
<br/>
Команда link - выводит ссылки для подключения<br/>
<br/>
Файл с конфигурацией находится по адресу:<br/>
/usr/local/etc/xray/config.json<br/>
Команда для перезагрузки ядра xray (после каких-либо изменений в конфиг):<br/>
systemctl restart xray
<br/>
<br/>
Для подключения используем:<br/>
Windows/macOS/Linux: [Throne](https://github.com/throneproj/Throne/releases/latest)<br/>
Android: [v2rayNG](https://github.com/2dust/v2rayNG/releases/latest)<br/>
iOS: [Streisand](https://apps.apple.com/us/app/streisand/id6450534064) (возможно нужно будет изменить регион AppStore, например на США)<br/>
