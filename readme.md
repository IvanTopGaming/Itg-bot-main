Проект архивирокан. Некоторые коги могут не работать и вызывать ошибки. Для запуска требуется python 3.8 и выше. 


Что бы запустить бота необхоимо установить необходимые пакеты. Все они содержатся в файле requirements.txt



pip install -r requirements.txt (Windows)

pip3 install -r requirements.txt (Linux, Mac OS)



Далее необходимо указать токен бота в файле config.py. Его можно найти на https://discord.com/developers/applications
и токен аккаунта OpenAI. Его прийдется либо купить, либо зарегестрировать новый аккаунт на сайте https://chat.openai.com/


После запускаем файл start.bat



-----ДЛЯ РАЗРАБОТЧИКОВ-----

Что бы удаленно управлять minecraft сервером есть rcon. В файл server.propereties нужно включить rcon, указать пароль, ip и порт и все эти же данные занести в файл config.py в боте
Так же для бот поддерживает аддоны, путем добавления новых когов в папку cogs. Используемый api библитоека для discord это disnake. 
При использовании dianake парралельно с discord невозможно из-за конфликтов. (Один и тот же токен не можент использоваться одновременно)


# ----- ENGLISH


Archivirocan project. Some cogs may not work and may cause errors. To run the bot you requires at least python 3.8 or higher. 


To run the bot you need to install the necessary packages. All of them are contained in the file requirements.txt.


##
pip install -r requirements.txt (Windows)

pip3 install -r requirements.txt (Linux, Mac OS)
##


Next, you need to specify the bot token in the config.py file. It can be found at https://discord.com/developers/applications
and OpenAI account token. You will have to either buy it or register a new account at https://chat.openai.com/.


After we run the file named : start.bat



----- FOR DEVELOPERS-----

To remotely control minecraft server there is a rcon. In the file server.propereties need to include rcon, specify a password, ip and port and all the same data put in the file config.py in the bot
Also for the bot supports addons, by adding new cogs to the cogs folder. Used api biblitoek for discord is disnake. 
When using dianake paralleled with discord is not possible due to conflicts. (The same token cannot be used at the same time).


# ----- FRENCH

Projet Archivirocan. Certains paramètres peuvent ne pas fonctionner et provoquer des erreurs. Pour faire fonctionner le bot, il faut au moins python 3.8 ou plus. 
Pour faire fonctionner le bot, vous devez installer les librairies nécessaires. Elles sont toutes contenus dans le fichier requirements.txt.

##
pip install -r requirements.txt (Windows)

pip3 install -r requirements.txt (Linux, Mac OS)
##


Ensuite, vous devez spécifier le jeton du bot dans le fichier config.py. Il se trouve sur le discord developpers https://discord.com/developers/applications
et le jeton de compte OpenAI. Vous devrez soit l'acheter, soit créer un nouveau compte sur https://chat.openai.com/.



Après, exécuter le fichier start.bat



----- POUR LES DEVELOPPEURS-----


Pour contrôler à distance le serveur minecraft, il y a un rcon. Dans le fichier server.propereties il faut inclure le rcon, spécifier un mot de passe, l'ip et le port et toutes les mêmes données mises dans le fichier config.py dans le bot.
Le bot supporte également les addons, en ajoutant de nouveaux cogs dans le dossier cogs. L'api biblitoek utilisée pour discord est disnake. 
L'utilisation de disnake en parallèle avec discord n'est pas possible en raison de conflits. (Le même jeton ne peut pas être utilisé en même temps).

