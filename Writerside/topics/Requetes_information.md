# Requêtes d'information 

Pour rappel, l'URL de base est : **https://custom-ocr.klippa.com/api/v1**.
<br>Voici les différentes requêtes d'information possibles avec la clé API :
<table>
    <tr>
        <td> <b>Méthode HTTP</b></td>
        <td> <b>URL de la requête </b></td>
        <td> <b>Paramètres requis</b></td>
        <td> <b>Description </b> </td>
    </tr>
    <tr>
        <td> GET </td>
        <td> https://custom-ocr.klippa.com/api/v1<b>/</b> </td>
        <td> X-Auth-Key</td>
        <td> Infos principales sur l'API </td>
    </tr>
    <tr>
        <td> GET </td>
        <td> https://custom-ocr.klippa.com/api/v1<b>/credits</b> </td>
        <td> X-Auth-Key </td>
        <td> Infos sur le nombre de crédits Klippa </td>
    </tr>
    <tr>
        <td> GET </td>
        <td> https://custom-ocr.klippa.com/api/v1<b>/fields </b></td>
        <td> X-Auth-Key </td>
        <td> Infos sur les différents champs </td>
    </tr>
    <tr>
        <td> GET </td>
        <td> https://custom-ocr.klippa.com/api/v1<b>/fields/{Template}</b> </td>
        <td> X-Auth-Key </td>
        <td> Infos des champs du template en paramètre</td>
    </tr>
    <tr>
        <td> GET </td>
        <td> https://custom-ocr.klippa.com/api/v1/templates </td>
        <td> X-Auth-Key </td>
        <td> Infos des différents templates </td>
    </tr>
    
</table>