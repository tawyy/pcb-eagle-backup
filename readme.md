# Tawy random repo

Mes premières PCB faites sous EAGLE (2016), à une époque ou je ne savais même pas lire un schematic et que les PCB était dessinées comme si je faisais un dessin sous photoshop :) 
Aucune PCB dispo sur ce repo n'a été validée. Je n'utilise plus Eagle.

## Dreamcast

Merci à [dc-swat](http://www.dc-swat.ru/)  qui ont été les précurseurs dans le domaine. Coté logiciel, il faut le coupler à dreamshell ou retrodream pour un fonctionnement optimal.

* G1-ATA IDE Adapter permet de remplacer le lecteur GD-ROM par un disque dur IDE, la version proposée par DC-SWAT était un peu moche et surtout incorrecte au niveau des pitchs du connecteur, je l'avais redesign, réduit et remplacé les composants par du smd pour un rendu plus propre. Version avec 3.3V pour HDD2.5", connecteur inversé pour test avec le cable IDE à l'envers... Je ne sais plus trop ! *tocheck : le crystal à peut etre les pins mal placés.* 

* DC-IDE permet d'ajouter un HDD IDE dans la console en utilisants certains pins dispo sur la carte mère du lecteur GD-Rom et mettre le HDD à l'extérieur de la console. Moche mais fonctionnel. 

* Dreamshell bios permet d'avoir un double bios. Plusieurs versions existent dont certaines avec logo Dreamcast devkit en 3D. Monter le bios directement sur l'ancien est à mon sens aussi simple à installer. nul.

## Neo-Geo

* Stereo-mod du pauvre : PCB que j'ai design suite à une visite sur le [forum neo-geo](https://www.neo-geo.com/forums/index.php?threads/info-consolized-mv1fz-rgb-and-controller-points-on-the-bottom-of-the-board.222630/#post-3369623). J'avais fait une consolization d'un slot MVS et j'avais entendu parler d'une bidouille pour rendre le son stéreo. J'ai donc design *très vite fait* une PCB un peu éclatée (mais fonctionnelle) et l'avais rendu publique via un compte google drive que je partage encore aujourd'hui avec des gens qui la réclame. Je voulais un truc super cheap et je ne jurais que par OSHPark à l'époque (jusqu'au jour ou j'ai pris un frais de douane de l'espace de 15€ pour une commande de 2€) - je ne commande maintenant que sur jlcpcb/elecrow/pcbway. 

* Top PCB Memory Card : memory card que j'ai design en suivant le schema de [furrtek](https://github.com/neogeodev/NeoMemCard2). C'est la plaque du haut seulement :)

## Random PCB

* Helper : Surement ma première PCB :) un truc super simple qui permet de faire un hackpad "propre". J'utilise du wrapping wire pour les signaux et ca termine sur un screw terminal pour que l'utilisateur ait juste a visser les fils dedans. Je l'utilise toujours aujourd'hui quand j'ai besoin de faire un hackpad.

* MC Cthulhu PCB : J'avais réduit comme je pouvais la PCB du MC Cthulhu. Le pic programmé se vendait à l'époque tout seul et la PCB d'origine était vraiment pas jolie. Et voilà.

* Manette Super Nintendo : tentative de faire une manette nintendo sans fil en prenant une manette sans fil et l'insérant dedans... 8bitdo à sorti une PCB permettant de faire exactement ce que je voulais. Je l'ai donc acheté et abandonné.
