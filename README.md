# MERGE-BOT
### PR's Welcomed
<br>

![GitHub Repo stars](https://img.shields.io/github/stars/yashoswalyo/MERGE-BOT?color=blue&style=flat)
![GitHub forks](https://img.shields.io/github/forks/yashoswalyo/MERGE-BOT?color=green&style=flat)
![GitHub issues](https://img.shields.io/github/issues/yashoswalyo/MERGE-BOT)
![GitHub closed issues](https://img.shields.io/github/issues-closed/yashoswalyo/MERGE-BOT)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yashoswalyo/MERGE-BOT)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/yashoswalyo/MERGE-BOT)
![GitHub contributors](https://img.shields.io/github/contributors/yashoswalyo/MERGE-BOT?style=flat)
![GitHub repo size](https://img.shields.io/github/repo-size/yashoswalyo/MERGE-BOT?color=red)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/yashoswalyo/MERGE-BOT)

Un bot de Telegram por [Yash Oswal] (https://t.me/yashoswalyo) para fusionar múltiples videos en Telegram en un solo video. <br>
Los errores deben informarse en: [Telegram Group](https://t.me/yo_codes_support)

```diferencia
- TODO:
+ Agregar capacidad para editar metadatos de video exportado

- CARACTERISTICAS:
+ (nuevo) Opción para agregar múltiples pistas de audio al video de Telegram
+ (nuevo) Opción para agregar múltiples subtítulos al video de Telegram
+ Subir archivos a Drive (envíe su configuración de rclone al bot)
# 1. Envía tu configuración de rclone al bot.
# 2. Luego envíe videos para fusionar, después de tocar "Fusionar ahora", estará disponible la opción de cargar a la unidad.
+ El video combinado conserva todas las secuencias del primer video que envía (es decir, todas las pistas de audio/subtítulos)

+ Combina hasta 10 videos en uno
+ Subir como documento/video
+ Soporte de miniaturas personalizadas
+ Los usuarios pueden iniciar sesión en el bot usando una contraseña
+ El propietario puede transmitir mensajes a todos los usuarios
+ Log Channel para almacenar todos los videos combinados

```
## Tutorial de implementación:
[![Watch the video](https://img.youtube.com/vi/H-xVk_4zccs/hqdefault.jpg)](https://youtu.be/H-xVk_4zccs)

## Implementar (bajo su propio riesgo):
<p><a href="https://heroku.com/deploy?template=https://github.com/yashoswalyo/MERGE-BOT"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>

### OR
Goto `settings > actions > secret > New Repository Secret` <br>
Add `HEROKU_EMAIL` <br>
Add `HEROKU_API_KEY` <br>
Add `HEROKU_APP_NAME` <br>
Add `CONFIG_FILE_URL` <br>
Goto `Actions > Manual Deploy To Heroku > Run Workflow`

### O
Próximamente, en breve, pronto
## Tutorial para obtener la URI de MongoDB:
[![Watch the video](https://img.youtube.com/vi/OfQ7xxMylV4/hqdefault.jpg)](https://youtu.be/OfQ7xxMylV4)


## Variables del archivo de configuración:
1. `TELEGRAM_API`: cuenta de usuario Telegram API_ID, obténgalo de my.telegram.org
2. `API_HASH`: cuenta de usuario Telegram API_HASH, obténgalo de my.telegram.org
3. `BOT_TOKEN`: su token de bot de Telegram, consígalo de @Botfather XD
4. `PROPIETARIO`: Ingrese la identificación del propietario del bot
5. `OWNER_USERNAME`: nombre de usuario del propietario del bot
6. `DATABASE_URL`: Ingrese su URI mongodb
7. `CONTRASEÑA`: ingrese la contraseña para iniciar sesión en el bot
8. `LOGCHANNEL`: el canal de registro almacenará todos los videos combinados de los usuarios ("-100" + "ID del canal")
9. `USER_SESSION_STRING`: cadena de sesión de cuenta Premium para cargar hasta 4 GB (requiere `LOGCHANNEL`)


## Commands (add via @botfather) :
```
start - Iniciar el bot
extract - Extrae audios/subtítulos de Telegram Mediaa
showthumbnail - Muestra tu miniatura
deletethumbnail - Elimina tu miniatura
settings - Configuración de usuario para administrar diferentes modos
help - Cómo usar Bot
about - Sobre el bot
login - Access bot
ban - (admin only) Ban any user
unban - (admin only) Unban any user
log - (admin only) Get log file from server
broadcast - (admin only) Broadcast message to bot users
stats - (admin only) check bots stats
```

## Self Host
```sh
$ git clone https://github.com/yashoswalyo/MERGE-BOT.git
$ cd MERGE-BOT
$ sudo apt-get install python3 python3-pip ffmpeg
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
# <fill config.env correctly by looking at sample_config.env>
$ bash start.sh
```

## Licencia
```
Bot de combinación, Bot de combinación de video de Telegram
Derechos de autor (c) 2021 Yash Oswal <https://github.com/yashoswalyo>

Este programa es software libre: puedes redistribuirlo y/o modificar
bajo los términos de la Licencia Pública General GNU Affero publicada por
la Free Software Foundation, ya sea la versión 3 de la Licencia, o
(a su elección) cualquier versión posterior.

Este programa se distribuye con la esperanza de que sea útil,
pero SIN NINGUNA GARANTIA; sin siquiera la garantía implícita de
COMERCIABILIDAD o IDONEIDAD PARA UN FIN DETERMINADO. Ver el
Licencia pública general GNU Affero para obtener más detalles.

Debería haber recibido una copia de la licencia pública general GNU Affero
junto con este programa. Si no, consulte <https://www.gnu.org/licenses/>
```

## Credits

- [Me](https://github.com/yashoswalyo) for [Nothing](https://github.com/yashoswalyo/MERGE-BOT) 😬
- [Dan](https://github.com/delivrance) for [Pyrogram](https://github.com/pyrogram/pyrogram) ❤️
- [Abir Hasan](https://github.com/AbirHasan2005) for his wonderful [code](https://github.com/AbirHasan2005/VideoMerge-Bot) ❤️
- [Jigarvarma2005](https://github.com/Jigarvarma2005) and [SpechIDE](https://t.me/spechide) for helping me to fix bugs 🤓
