Yvonne ATIS

Pack ATIS vocale pour VATFRANCE uniquement.

URL du générateur:
Yvonne2 :
http://atis.vatfrance.org/?app=ILS&i=$atiscode&arr=$arrrwy($atisairport)&dep=$deprwy($atisairport)&metar=$metar($atisairport)
Yvonne3 :
http://atis.vatfrance.org/$atiscode/$deprwy($atisairport)/$arrrwy($atisairport)/ILS/?m=$metar($atisairport)&sid=1A,1B


URL du générateur: 
Citer:
http://atis.vatfrance.org/$atiscode/$deprwy($atisairport)/$arrrwy($atisairport)/ILS/?m=$metar($atisairport)&sid=1A,1B


N'oubliez pas de changer "ILS" pour le type d'approche active, eg:
- ILSy
- RNAVa,VORa
- RNAVa-VPTa (Un tiret signifie "then")
- etc...

N'oubliez pas aussi de changer "1A,1B" pour le/les SIDs a prévoir, eg:
- 9A,9B,9Z (Pour LFPG en face Ouest liée)
- 9P (Pour Orly en Ouest)
- pour les C, L et R ajouter un espace &sid=3 C, 3 L
- etc...

D'autres informations sont disponibles en ajoutant a la fin de l'URL:
&ta=XXXX (La TA en pied, a définir uniquement pour les aéroport qui ne sont pas dans le tableau ici: http://atis.vatfrance.org/manager, sert a calculer le TL)
&fe=XX (L'altitude de l’aéroport en hPa, a définir uniquement pour les aéroport qui ne sont pas dans le tableau ici: http://atis.vatfrance.org/manager, sert a calculer le QFE)
&birds=1 (Annonce une activité aviaire proche)
&lvp=1 (Annonce que les procédures LVPs sont actives)
&add=monfichier (Ajouter un fichier customisé)