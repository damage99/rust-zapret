# ГАЙД для тех у кого не заходит на некоторые сервера Rust

* Скачиваем zapret с github [https://github.com/Flowseal/zapret-discord-youtube](https://github.com/Flowseal/zapret-discord-youtube) и распаковываем в папку `zapret`
* Запускаем `service.bat`
* Выбираем `4. Game Filter`
* Выбираем `1. TCP and UDP`
* Копируем любой удобный `general (ALT...).bat` стратегию которая у вас работает или создаем отдельную
* Добавляем туда `--filter-tcp=443 --hostlist="%LISTS%list-rust-domains.txt" --dpi-desync=fake --dpi-desync-repeats=6 --dpi-desync-fooling=md5sig,badsum --new ^`
* Создаем файл `list-rust-domains.txt` и кладем его в папку `zapret/lists`
* В файл `list-rust-domains.txt` добавляем следующий список

```text
maps.rustmaps.com
*.maps.rustmaps.com
rustmaps.com
facepunch.com
*.facepunch.com
playrust.com
steamcommunity.com
steam.com
steampowered.com
easyanticheat.com
eac.com
www.easy.ac
easy.ac
rustmaps.com
www.rustmaps.com
www.battlemetrics.com
maps.rustmaps.com
maps.0b0.sw
cdn.rastamaps.com
```

* Сохраняем и запускаем наш `.bat` файл (*отредактированный или новый*)

# PNI https://discord.gg/rQf6cBgkY
