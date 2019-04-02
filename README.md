# Appli météo avec Ionic

## Géolocalisation

Dans la page settings, bouton "Me géolocaliser".
Au clic, utilisation du module Ionic Geolocation https://ionicframework.com/docs/native/geolocation.
Grâce au module, récupération de la latitude et la longitude de l'utilisateur.
Pour récupérer la ville de l'utilisateur, requête sur l'API :
- https://api-adresse.data.gouv.fr/reverse/?lat=XXXX&lon=XXXXXX
Donc possible enregistrement de la ville dans le storage.
