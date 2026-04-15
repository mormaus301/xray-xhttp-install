## Script for installation and configuration of the X-ray kernel without a graphical interface
<br/>
Скрипт-форк для автоматической установки чистого xray-core с авторазвёртыванием готового конфига vless xhttp reality + shadowsocks-2022 в одну команду и выводом оных готовой конфиг-ссылкой и qr-кодом.<br/>
Подходит в т.ч. для абсолютно голых только что купленных серверов (всё что нужно обновляет и ставит сам).
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
P.S. Внести какие-то изменение в конфиг (например изменить сайт маскировки) естественно может каждый.<br/>
Файл с конфигурацией находится по адресу:<br/>
/usr/local/etc/xray/config.json<br/>
Команда для перезагрузки ядра xray (после каких-либо изменений в конфиг):<br/>
systemctl restart xray
