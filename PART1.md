# Gherkin

## Spotify

FEATURE: Utilisez Spotify

SCENARIO: Se connecter sur Spotify  
GIVEN j’ouvre mon navigateur connecter sur la page web de Spotify  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Spotify en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Spotify  

SCENARIO: Ecouter de la musique  
GIVEN j’ouvre mon navigateur connecter sur la page web de Spotify  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Spotify en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Spotify  
WHEN je sélectionne "une chanson" sur la liste de recommendation  
AND j'appuie sur le bouton "Play"  
THEN la musique se lance  

SCENARIO: Ecouter de la musique depuis une playlist  
GIVEN j’ouvre mon navigateur connecter sur la page web de Spotify  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Spotify en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Spotify  
WHEN je sélectionne "Afro" sur la liste des playlists  
AND j'appuie sur le bouton "Play"  
THEN la musique se lance depuis la playlist "Afro"  

## Netflix

FEATURE: Utiliser Netflix

SCENARIO: Se connecter sur Netflix  
GIVEN j’ouvre mon navigateur connecter sur la page web de Netflix  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Netflix en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Netflix  

SCENARIO: Regarder une série  
GIVEN j’ouvre mon navigateur connecter sur la page web de Netflix  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Netflix en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Netflix  
WHEN je sélectionne "une série" sur la liste de recommendation  
AND j'appuie sur le bouton "Regarder"  
THEN la série se lance  

SCENARIO: Rechercher une série  
GIVEN j’ouvre mon navigateur connecter sur la page web de Netflix  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Netflix en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Netflix  
WHEN je tape "Lupin" sur la barre de recherche  
AND j'appuie sur le bouton "Rechercher"  
THEN la liste de résultat s'affiche  
