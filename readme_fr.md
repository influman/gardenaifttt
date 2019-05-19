# Installation
Contr�le du Smart System Gardena via IFTTT  
Water Control, Irrigation Control, Smart Power Socket, Tondeuse SILENO   
    
### Pr�requis 
  
R�cup�rer le code Key du service Webhooks de IFTTT.  
Dans IFTTT.com, apr�s avoir cr�� un compte le cas �ch�ant, recherchez (rubrique Search) le service Webhooks, et r�cup�rez votre code personnel KEY dans la rubrique Documentation.  
  
Cr�er les applets n�cessaires sous IFTTT pour le contr�le des actions des appareils de votre Smart System  
  
Exemple pour un Water Control Gardena:   
  
  * Dans IFTTT.com, cr�ez un nouvel Applet dans la rubrique My Applets (Bouton NEW APPLET)
  * Pour la partie +THIS, cherchez Webhooks, s�lectionnez "Receive a Web Request", et nommez le d�clencheur (Trigger) "gardena-arrosage-start"  
  * Pour la partie +THAT, cherchez Gardena, appareillez votre compte Gardena (email/mdp) le cas �ch�ant, puis s�lectionnez le service "VALVE:start watering"  
  * Sauvegarder votre Applet IFTTT
  
  * Cr�ez 1 autre applet similaire pour le webhook "gardena-arrosage-stop" et le service "VALVE:stop watering"  
  * Cr�ez 1 autre applet similaire pour le webhook "gardena-prog-pause" et le service "Pause schedule"  
  * Cr�ez 1 autre applet similaire pour le webhook "gardena-prog-unpause" et le service "Unpause schedule"  
 
    
    
### Ajout du p�riph�rique eedomus
Cliquez sur "Configuration" / "Ajouter ou supprimer un p�riph�rique" / "Store eedomus" / "Gardena Smart System IFTTT" / "Cr�er"  

  
*Voici la donn�e � renseigner:*

* [Obligatoire] - Le code Key du service Webhooks IFTTT
  
Le p�riph�rique cr��e par d�faut contient plusieurs WebHooks avec les "event name" suivants :  
  
  * gardena-arrosage-start  
  * gardena-arrosage-stop  
  * gardena-prog-pause  
  * gardena-prog-unpause  
  * gardena-sileno-start  
  * gardena-sileno-stop  
    
  
  
Influman 2019  
therealinfluman@gmail.com  
[Paypal Me](https://www.paypal.me/influman "paypal.me")  
  

