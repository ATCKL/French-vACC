Yvonne ATIS

Pack ATIS vocale pour VATFRANCE uniquement.

URL du g�n�rateur:
Yvonne2 :
http://atis.vatfrance.org/?app=ILS&i=$atiscode&arr=$arrrwy($atisairport)&dep=$deprwy($atisairport)&metar=$metar($atisairport)
Yvonne3 :
http://atis.vatfrance.org/$atiscode/$deprwy($atisairport)/$arrrwy($atisairport)/ILS/?m=$metar($atisairport)&sid=1A,1B


URL du g�n�rateur: 
Citer:
http://atis.vatfrance.org/$atiscode/$deprwy($atisairport)/$arrrwy($atisairport)/ILS/?m=$metar($atisairport)&sid=1A,1B


N'oubliez pas de changer "ILS" pour le type d'approche active, eg:
- ILSy
- RNAVa,VORa
- RNAVa-VPTa (Un tiret signifie "then")
- etc...

N'oubliez pas aussi de changer "1A,1B" pour le/les SIDs a pr�voir, eg:
- 9A,9B,9Z (Pour LFPG en face Ouest li�e)
- 9P (Pour Orly en Ouest)
- pour les C, L et R ajouter un espace &sid=3 C, 3 L
- etc...

D'autres informations sont disponibles en ajoutant a la fin de l'URL:
&ta=XXXX (La TA en pied, a d�finir uniquement pour les a�roport qui ne sont pas dans le tableau ici: http://atis.vatfrance.org/manager, sert a calculer le TL)
&fe=XX (L'altitude de l�a�roport en hPa, a d�finir uniquement pour les a�roport qui ne sont pas dans le tableau ici: http://atis.vatfrance.org/manager, sert a calculer le QFE)
&birds=1 (Annonce une activit� aviaire proche)
&lvp=1 (Annonce que les proc�dures LVPs sont actives)
&add=monfichier (Ajouter un fichier customis�)