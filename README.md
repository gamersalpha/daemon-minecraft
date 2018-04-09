# daemon-minecraft

source code : https://www.ctrl-alt-geek.fr/faire-tourner-un-serveur-minecraft-comme-un-service/

Je me suis basé sur le code ci-dessus avec quelque ajustement

Installation : 

cd
git clone https://github.com/gamersalpha/daemon-minecraft
cd daemon-minecraft

...
...
cp minecraft /etc/init.d/minecraft
chmod 755 /etc/init.d/minecraft
update-rc.d minecraft defaults
/etc/init.d/minecraft start

Attention le script est encors en modificaiton ne pas utiliser en PRODUCTION ou sinon à vos risque et peril


