# ESP32C3-Screen-1.28
Firmware Jauge AFR by Bolino08C qui communique avec un speeduino qui a un AirBear (ESP32C3 SuperMini)

Lien vers AirBear Speeduino : https://github.com/speeduino/Airbear

Lien vers l'écran que j'ai utilisé : https://fr.aliexpress.com/item/1005006623621289.html

Fonctionnement de l'écran :
* A l'allumage il tente une connection avec le AirBear 3 fois. 
Si il ne détecte pas, l'allumage est long et la valeur de l'AFR reste à 0.
* En cas d'arrêt du Speeduino et remise en route, l'écran redémarre et tente de se reconnecter 3 fois.
(Exemple : la voiture cale, tu redémarre. L'écran redémarre aussi.)
* Le AirBear connecté au second port Série (Serial2 ou 3 suivant le CPU), doit-être paramétré avec le Type de connection Bluetooth BLE.
* Le paramètrage du second port série dans TunerStudio doit-être en msDroid
![image](https://github.com/user-attachments/assets/14a3e357-c538-49df-a5b7-f7031fd2a044)

Si tout est respecté :
![471203869_9055712401156151_1738117031796719000_n](https://github.com/user-attachments/assets/7e1798c5-eedd-479a-b4a8-7679cb8cd56a)


Je fournis ESP FLASH TOOL DOWNLOAD TOOL V3.9.7 pour permettre de flasher le firmware.

Voici les paramètres : ![Burn operation-1](https://github.com/user-attachments/assets/6bd9dc7b-f77a-4c6a-826c-2790847a9364)
![Burn operation-2](https://github.com/user-attachments/assets/c071e8a1-3d95-45e2-a220-10bc5275fbb1)

Eteindre et rallumer l'écran après le flash.

Bolino08C le Bolideur.
