🔼 ATTENTION Node.js 🔼
Si Node.js n'est pas installé sur votre ordinateur
veuillez le télécharger et l'installer depuis le site officiel https://nodejs.org/en/download avant de procéder à l'installation du backend. 
Une fois que Node.js est installé
vous pouvez continuer avec les étapes d'installation du backend en suivant les instructions fournies dans le terminal.

🔼 ATTENTION Expo App 🔼
Si Expo Go n'est pas installé sur votre téléphone, veuillez le télécharger et l'installer depuis Google Play Store ou App Store.

ÉTAPE 1/2 DÉMARRER LE BACKEND
-> commande dans le terminal

1) cd backend
2) yarn install
3) nodemon
✅ Le backend a démarré


ÉTAPE 1/2 DÉMARRER LE FRONTEND
-> commande dans le terminal

1) cd frontend
2) yarn install
3) yarn start
4)
Après avoir exécuté yarn start, un code QR s'affichera avec le message "Metro waiting on exp://<votre adresse IP>". 
Copiez l'adresse IP après "exp://". 
Allez dans frontend/screens/SnapScreen.tsx et, à la ligne 13
remplacez l'adresse du backend par l'adresse IP que vous venez de copier. 
Collez l'adresse IP et changez le nombre après les deux-points par :3000. 
Ça devrait ressembler à ceci: 
const BACKEND_ADDRESS = 'http://<votre adresse IP>:3000';

5)Appuyez sur la touche r dans votre terminal pour redémarrer l'application.
6)Prenez votre téléphone, utilisez votre caméra pour scanner le code QR.
✅ Le frontend a démarré