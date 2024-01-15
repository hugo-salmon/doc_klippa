# Traitement de PDF

Le traitement des fichiers PDF peut se faire grâce à des méthodes
d'extraction de texte `fast` et `full`.
- Avec la méthode `fast`, l'API extrait tout le texte du fichier. Si le fichier 
contient une/des image(s) avec du texte ou que le PDF est scanné, il ne sera pas analysé ou alors 
qu'en partie. Tous les `endpoints` ne prennent pas en charge la méthode 
d'extraction `fast` et se rabattent sur la méthode `full`.

- Avec la méthode `full`, l'API utilise la méthode OCR pour extraire le texte.
Cela donne un résultat plus précis mais cette méthode est moins performante 
que la méthode `fast`.

Par défaut, le traitement des fichiers PDF se fait sur les 4 premières
pages et la dernière page du PDF pour un temps de traitement rapide.
Si le fichier fait plus de 5 pages et que le traitement de toutes les
pages est nécessaire, la méthode `multipage` peut être utilisée.