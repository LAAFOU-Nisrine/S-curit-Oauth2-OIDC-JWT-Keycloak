# S-curit-Oauth2-OIDC-JWT-Keycloak

Activité Pratique N°7 : Sécurité Oauth2, OIDC, JWT, Keycloak
Travail à faire (Voir vidéo : https://www.youtube.com/watch?v=vNKVm2vTL2Q):
Partie 1 : (Traiter uniquement les 49 premières minutes de la vidéo)
1. Télécharger Keycloak 23
2. Démarrer Keycloak
3. Créer un compte Admin
4. Créer une Realm
5. Créer un client à sécuriser
6. Créer des utilisateurs
7. Créer des rôles
8. Affecter les rôles aux utilisateurs
9. Avec PostMan :
    - Tester l'authentification avec le mot de passe
    - Analyser les contenus des deux JWT Access Token et Refresh Token
    - Tester l'authentification avec le Refresh Token
    - Tester l'authentification avec Client ID et Client Secret
    - Changer les paramètres des Tokens Access Token et Refresh Token

Partie 2 :
 Développer et sécuriser une application basée sur les micro-services en utilsant Oauth 2, OIDC, Keycloak :
   - Invenroty-service
   - Frontend Tymeleaf
   - Frontend Angular

 Vidéos :
    1- https://www.youtube.com/watch?v=zI0Xr-O3sqM&authuser=0
    2- https://www.youtube.com/watch?v=YbCooJDUtOM&authuser=0
    3- https://www.youtube.com/watch?v=aSPWnRSteTk&authuser=0
    4- https://www.youtube.com/watch?v=NnzoM08CvgA&authuser=0
    5- https://www.youtube.com/watch?v=LrqRjokK5dY&authuser=0


démmarage de keycloak : 
<img width="960" alt="Capture d'écran 2024-01-13 193529" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/10e0bd13-e93b-4193-9d31-3c18efb0082c">

création de Realm (wallet-realm) :
<img width="960" alt="Capture d'écran 2024-01-13 193756" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/48089d3b-1a03-4a40-9024-cd0d74c08c91">

création de client (wallet-client) :
<img width="960" alt="Capture d'écran 2024-01-13 194318" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/bb61dd9e-0b7c-4357-a1ac-4bca916501b6">

création des utilisateurs (user1 ) :
<img width="960" alt="Capture d'écran 2024-01-13 195105" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/7dcf96a2-51cd-4c60-a00b-19c2684a0ed5">

teste d'authentification avec le mot de passe (avec Postman) et analyser avec Jwt.io :
<img width="960" alt="Capture d'écran 2024-01-13 195825" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/1c03b4ad-1fff-41a7-8f10-dbe08bb73367">

<img width="960" alt="Capture d'écran 2024-01-13 200218" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/3a7a46ab-ab67-4fef-b470-d58ba6818b53">

<img width="960" alt="Capture d'écran 2024-01-13 200230" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/2171845c-248d-4f4e-b92d-3c03b943673d">

 test d'authentification avec le Refresh Token (avec postman) :
<img width="960" alt="Capture d'écran 2024-01-13 202131" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/ae98781d-3728-4f04-ad40-e6be9f9cef2c">

test  d'authentification avec Client ID et Client Secret (avec postman) :
<img width="960" alt="Capture d'écran 2024-01-13 202743" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/95dc9409-ae3e-4abe-b08e-c82d4dad689e">
<img width="960" alt="Capture d'écran 2024-01-13 203344" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/c5f01ecf-9639-4418-a4dc-373ead9d3dc9">

authentification avec OAuth 2.0 et Google :
<img width="960" alt="Capture d'écran 2024-01-13 224703" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/39f1fcc7-8a78-4b22-941c-c90722a7aa68">
<img width="945" alt="capture_1" src="https://github.com/LAAFOU-Nisrine/S-curit-Oauth2-OIDC-JWT-Keycloak/assets/155231145/c776ebe0-4c80-463c-90c3-ac652142267a">

<img width="960" alt="Capture d'écran 2024-01-13 231525" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/e55db521-c960-4fe6-abef-f1c06e62c6bc">

/auth avec Google :
![image_111](https://github.com/LAAFOU-Nisrine/S-curit-Oauth2-OIDC-JWT-Keycloak/assets/155231145/1b1dd5de-054e-4756-aafe-0a7e0b7b6e09)


/auth avec Github :
![image1111](https://github.com/LAAFOU-Nisrine/S-curit-Oauth2-OIDC-JWT-Keycloak/assets/155231145/0b90843d-a76a-42f3-be9b-32a5e837e825)


/auth avec Keycloak :
<img width="960" alt="Capture d'écran 2024-01-14 135436" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/2f9481a1-c613-4bde-a37c-048e69648b75">

authentification (google,github et keycloak) avec Thymeleaf :
<img width="960" alt="Capture d'écran 2024-01-14 152750" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/43a4b271-c4c0-4cd6-b218-bc6620efafe7">


Products (thymeleaf) :
<img width="935" alt="Capture d'écran 2024-01-20 200451" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/4b6e00e0-5f44-46c4-ac4b-81a923bb6953">

Customers (thymeleaf) :
<img width="960" alt="Capture d'écran 2024-01-20 200204" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/6590f882-f707-43cd-a1b5-72a6ab30b65d">

Not authorized :
<img width="887" alt="Capture d'écran 2024-01-20 200558" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/3cd9050b-ca9c-47d5-9fe3-88fe3cd855fe">

Customer & inventory services :
<img width="960" alt="Capture d'écran 2024-01-20 200841" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/836bb9ac-7154-4081-a70d-46e1b52f48af">

SecurityConfig (Customer):
<img width="960" alt="Capture d'écran 2024-01-20 203612" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/47c6374d-1530-4225-956c-7076d3415f66">

SecurityConfig (inventory):
<img width="960" alt="Capture d'écran 2024-01-20 203722" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/31a61e8b-8ff2-4016-9cbe-a8e3cac69ca0">

Navbar & Authentification avec Keycloak (Angular) :
<img width="960" alt="Capture d'écran 2024-01-20 200957" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/1d78a2ae-e55d-4ed2-8164-8fe60f5cffc7">

<img width="960" alt="Capture d'écran 2024-01-20 201211" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/82fa9fd5-19ae-46a3-bbb8-bc4485a0c8e0">

Products (Angular) :
<img width="926" alt="Capture d'écran 2024-01-20 201443" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/7fd7f1cd-e338-41ae-aafd-3018f2227374">

docker-compose :
<img width="960" alt="Capture d'écran 2024-01-20 202957" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/b27d99b9-9f77-4d4d-9d5b-f4027b8ec66c">

Dockerfile (inventory):
<img width="960" alt="Capture d'écran 2024-01-20 203339" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/9afdae83-a73d-4e56-bd18-da082a0ae3c6">

Dockerfile (customer):
<img width="960" alt="Capture d'écran 2024-01-20 203257" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/164bf2c4-ace8-4ed0-bbab-4c480ff3c3ba">

Dockerfile (Angular app) :
<img width="960" alt="Capture d'écran 2024-01-20 203421" src="https://github.com/imadett88/Spring-Microservices-Security-using-Oauth2-OIDC-with-Keycloak/assets/83021588/1522176c-ba97-49c1-a152-43d137829537">






