# Gherkin

## Gmail

FEATURE: Utilisez Gmail

SCENARIO: Se connecter sur Gmail  
GIVEN j’ouvre mon navigateur connecter sur la page web de Gmail  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Discord en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Gmail  

SCENARIO: Envoyer un email  
GIVEN j’ouvre mon navigateur connecter sur la page web de Gmail  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Discord en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Gmail  
WHEN j'appuie sur le bouton "Nouveau message"  
AND j'écris le "message"
AND j'appuie sur le bouton "Envoyer"  
THEN le message est envoyé  

SCENARIO: Consulter dossier spam  
GIVEN j’ouvre mon navigateur connecter sur la page web de Gmail  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Discord en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil Gmail  
WHEN j'appuie sur le menu "Plus"  
AND j'appuie sur le bouton "Spam"  
THEN je vois la liste des messages spam  

## GitHub

FEATURE: Utiliser GitHub

SCENARIO: Se connecter sur GitHub  
GIVEN j’ouvre mon navigateur connecter sur la page web de GitHub  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de Discord en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil GitHub  

SCENARIO: Créer repository  
GIVEN j’ouvre mon navigateur connecter sur la page web de GitHub  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de GitHub en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil GitHub  
WHEN j'appuie sur le bouton "Plus"  
AND j'appuie sur "New repository"  
AND j'entre le "nom" du repository  
AND j'appuie sur le bouton "Create repository"  
THEN le repository se créé  

SCENARIO: Afficher profil GitHub  
GIVEN j’ouvre mon navigateur connecter sur la page web de GitHub  
AND j’appuie sur entrer  
WHEN je vérifie si c’est bien la page web de GitHub en inspectant l’adresse de l’url  
AND j’entre "daooodaba975@gmail.com" dans le champ email  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma page d'accueil GitHub  
WHEN j'appuie sur mon "nom d'utilisateur"
AND j'ppuie sur le bouton "Profil"
THEN mon profil GitHub s'affiche  
