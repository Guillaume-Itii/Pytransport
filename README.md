# Pytransport

Spécification : <br>
	<Strong>Format du fichier<strong><br>
	On considérera que pour la V1, toutes les stations peuvent aller d'un sens et l'autre, fichier en .csv avec comme format : <br>
	nom_de_larret;station_lié_1,station_lié_2;distance_station_1,distance_station_2<br>

<table>
	<th>Station</th><th>Déstination</th><th>Distance</th><th>Durée</th>
	<tr><td>A</td><td>B,C,D</td><td>1,1,2</td><td>3,1,2</td></tr>
	<tr><td>B</td><td>C,D</td><td>1,2</td><td>3,2</td></tr>
	<tr><td>C</td><td>A,B</td><td>1,2</td><td>3,2</td></tr>
</table>
