# SIF PCB Taiko No Tatsujin
La carte SIF permet d'amplifier et filtrer les signaux analogiques des piezos des Taiko de la borne. D'origine, la valeur des composants était fixe, car la conception reste inchangée pour les séries de bornes.

Maintenant, des personnes font des reproductions de cette borne, ou du moins du Taiko seulement. Et se contente pour la plupart de se connecter directement sur un Arduino, en filtrant les signaux via le firmware seulement, et le réglage se fait de manière empirique.

C'est pourquoi j'ai décidé de faire ce projet de carte SIF permettant de filtrer correctement les signaux d'entrée, et s'adaptant à la plupart des versions maison des Taiko que l'on peut trouver sur internet et refaire chez sois.

Le réglage se fait directement sur la carte en suivant une méthode simple.

Nomenclature :

* A1 : Arduino Pro Micro (Qté 1)
* Cx1 : Condensateur 1µF 1206 (Qté 8)
* Cx2 : Condensateur 4,7µF 1206 (Qté 8)
* CUxx : Condensateur 100nF 1206 (Qté 12)
* Dx : LED 1206 (Qté 8)
* Jx : TerminalBlock ou autre 2.54mm (Pour 2x8 entrées)
* Rx1, Rx2 : Résistance 1kΩ 1206 (Qté 16)
* Rx3 : Résistance 33kΩ 1206 (Qté 8)
* Rx4 : Résistance 100kΩ 1206 (Qté 8)
* Rx5 : Résistance 120Ω 1206 (Qté 8)
* RVxx : Potentiomètre 50kΩ 10 tours 3299Y (Qté 16)
* Ux1 : LM324N
* Ux2 : SN74HCY00N
* Ux3 : CD74HC4538E

![alt text](https://github.com/Mik027/SIF-PCB-Taiko-No-Tatsijin/blob/main/SIF%20PCB%20FACE.jpg)
