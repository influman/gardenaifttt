# Installation
Contrôle du Smart System Gardena via IFTTT  
Water Control, Irrigation Control, Smart Power Socket, Tondeuse SILENO   
    
### Prérequis 
  
Récupérer le code Key du service Webhooks de IFTTT.  
Dans IFTTT.com, après avoir créé un compte le cas échéant, recherchez (rubrique Search) le service Webhooks, et récupérez votre code personnel KEY dans la rubrique Documentation.  
  
Créer les applets nécessaires sous IFTTT pour le contrôle des actions des appareils de votre Smart System  
  
Exemple pour un Water Control Gardena:   
  
  * Dans IFTTT.com, créez un nouvel Applet dans la rubrique My Applets (Bouton NEW APPLET)
  * Pour la partie +THIS, cherchez Webhooks, sélectionnez "Receive a Web Request", et nommez le déclencheur (Trigger) "gardena-arrosage-start"  
  * Pour la partie +THAT, cherchez Gardena, appareillez votre compte Gardena (email/mdp) le cas échéant, puis sélectionnez le service "VALVE:start watering"  
  * Sauvegarder votre Applet IFTTT
  
  * Créez 1 autre applet similaire pour le webhook "gardena-arrosage-stop" et le service "VALVE:stop watering"  
  * Créez 1 autre applet similaire pour le webhook "gardena-prog-pause" et le service "Pause schedule"  
  * Créez 1 autre applet similaire pour le webhook "gardena-prog-unpause" et le service "Unpause schedule"  
 
    
    
### Ajout du périphérique eedomus
Cliquez sur "Configuration" / "Ajouter ou supprimer un périphérique" / "Store eedomus" / "Gardena Smart System IFTTT" / "Créer"  

  
*Voici la donnée à renseigner:*

* [Obligatoire] - Le code Key du service Webhooks IFTTT
  
Le périphérique créée par défaut contient plusieurs WebHooks avec les "event name" suivants :  
  
  * gardena-arrosage-start  
  * gardena-arrosage-stop  
  * gardena-prog-pause  
  * gardena-prog-unpause  
  * gardena-sileno-start  
  * gardena-sileno-stop  
    
  
  
Influman 2019  
therealinfluman@gmail.com  
[Paypal Me](https://www.paypal.me/influman "paypal.me")  
  

