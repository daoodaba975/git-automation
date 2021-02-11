# Gmail Gherkin

FEATURE Se connecter sur Gmail

SCENARIO connexion réussi  
GIVEN j’ouvre mon navigateur connecter sur la page web de Gmail  
THEN je vérifie la page web de Gmail en inspectant l’url  
WHEN j’entre "daoodaba@gmail.com" dans le champ email  
AND j'appuie sur le bouton "Continuer"  
AND j’entre "mypassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN j'ai accés à ma boite mail Gmail  

SCENARIO Echec connexion : mot de passe invalide  
GIVEN j’ouvre mon navigateur connecter sur la page web de Gmail  
THEN je vérifie la page web de Gmail en inspectant l’url  
WHEN j’entre "daoodaba@gmail.com" dans le champ email  
AND j'appuie sur le bouton "Continuer"  
AND j’entre "errorpassword" dans le champ du mot de passe  
AND j'appuie sur le bouton "Connexion"  
THEN un message d'erreur s'affiche indiquant une erreur sur le mdp  

SCENARIO Echec connexion : adresse email invalide  
GIVEN j’ouvre mon navigateur connecter sur la page web de Gmail  
THEN je vérifie la page web de Gmail en inspectant l’url  
WHEN j’entre "daoodaba@outlook.com" dans le champ email  
AND j'appuie sur le bouton "Continuer"  
THEN un message d'erreur s'affiche indiquant une erreur sur l'adresse email  
