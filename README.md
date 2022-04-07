Nom: Tp_cryptage
But: Crypter et decrypter un message qui peut etre lit a l'aide d'un cle
Auteur: Jabeer Aumeer

### Le principe du chiffrement asymétrique 

Pour comprendre on prend comme exemple: un message secrete doit etre envoyer a un base millitaire Russie , sans que les espions peuvent lire le message.. On doit génèrer  deux clés de chiffrement:

- une clé publique , qu'on doit envoyer au base Russie  et qui permettra à les officier  de chiffrer les messages qu'il enverra en retours. 
- une clé privée, qu'il conserve précieusement pour lui, et qui lui permettra de déchiffrer les messages chiffrés par les officiers  avec sa clé publique.

La clee publique peut etre distribue  à autant de personne qu'il le souhaite, cette clé ne sert qu'à chiffrer les messages !


## Installer le module Crypto


### installer python

```sh
sudo apt-get install python3
```
	sudo apt-get install python3


### installer crypto

```sh
sudo apt-get install python3-crypto
```
		

## Quelque details a suivre 


### git le projet 


```sh
git clone https://github.com/ialy501/crypto_project.git
```

### installer des fichier dans crypto_project

aller dans le dossier crypto_project
```sh
cd crypto_project/
```

installer les 5 fichiers(tocrypt, crypted, todecrypt, decrypted, key)
```sh
mkdir tocrypt
mkdir todecrypt
mkdir decrypted
mkdir todecrypt
mkdir key
```

### Mettre le message coder sur le dossier tocrypt

aller dans le fichier tocrypt
```sh
cd crypto_project/tocrypt
```

creer un fichier text (ex: mess.txt)
```sh
touch mess.txt
```
ecrire le message dans le fichier text (mess.txt)


### Donner les droit d'execution au script

aller dans le fichier source (src)
```sh
cd crypto_project/src
```
droit d'execution:
```sh
chmod +x crypt.sh
chmod +x decrypt.sh
```


## execution du module cryto 


### Donner les droit d'execution au script

aller dans le fichier crypto_project
```sh
cd crypto_project/
```

droit d'execution:
```sh
chmod +x install.sh
chmod +x unstall.sh
```

### INSTALL

Commencer le cryptage du message
```sh
cd crypto_project/
./install.sh
```


### cryptage de message


verifier le cryptage est effectue
command:

```sh
sudo systemctl status crypt.sh.service
```


### decryptage de message


verifier le decryptage est effectue
command:

```sh
sudo systemctl status decrypt.service
```

## UNSTALL

```sh
cd crypto_project/
./unstall.sh
```

