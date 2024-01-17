Ce projet permet de monitorer votre connexion internet dans votre domicile depuis votre raspberry. Il est tiré de cette [article](https://blog.eleven-labs.com/fr/monitorer-son-debit-internet/)

## Getting started

Brancher le raspberry. Connectez-vous en SSH sur votre raspberry. Connectez-vous à votre réseau wifi.
Vous aurez besoin d'installer docker sur votre raspberry.

Mettre en place la crontab.

Faire en sorte que le service soit lancer au démarrage du raspberry.

```bash
$ docker-compose up -d
```
