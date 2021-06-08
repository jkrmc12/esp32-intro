## Styr lampe med en knapp

### Lampe som lyser konstant

Vi begynner først med en svært enkel krets:

![](./5V_Lampe.png)

### Du trenger

| Type          | Antall           |  Utseeende |
| ------------- | :------------- | :----: |
| LED           | 1    |  ![LED](../img/led.png) (farge kan variere)
| Motstand 330 Ohm eller 220 ohm | 1 |  ![](../img/330ohm.png) 	
| Breadboard (prototypebrett)	| 1 | ![](../img/bb.png)
| ESP32-CAM | 1 | ![](../img/esp32cam_small.png)

* ESP32-CAM fungerer som en statisk strømkilde og mer merket ```5V``` i diagrammet
* Strømmen går fra strømkilden gjennom motstanderen og så inn i LED-en (lampen)
* Strømmen går fra LED-en tilbake til negativ side på strømforsyningen

Funksjonen til motstanden er å begrense hvor mye strøm som går gjennom LED-en slik at LED-en ikke går i stykker.

Koble opp slik:

![](./5V_Lampe_bb.png)

![](./5V_Lampe_photo.png)


