# FormulaireConnexion
# Information technique :
  -Pour les langagues j'au utiliser HTML , CSS , JS , PHP.
  -j'ai aussi utiliser un template qui est disponible sur le site colorlib pour avoir un joli formulaire.
  -pour la base de donnée : MySQL
 # comment l'utuliser:
  -d'abort l'outil neccesaire pour pouvoir l'exécuter c'est le wampserver.
  -premierement il faut ouvrire la bdd que j'ai mis dans le dossier "base de donne" avec phpmyadmin , et puis mettre le dossier "login" tout entier dans le repertoir www
  aprés lancer l'exécution une fenetre de connction sera afficher.
  -pour expliquer un peu le fonctionnement : 
   *un user se connect si il laisse un ou plusieur champs vide evidement il peut pas enter .
   *s'il remplit les 2 champs (email , password) ici on va voir s'il existe pas c'est a dire c'est la 1ere fois il va enter et il sera insérer dans la bdd et un msg "Enregistrement effectue" sera afficher , si non si il existe déja (son mail existe déja dans la bdd ) a ce niveau la on va faire un autre test mais cette fois si c'est sur le mot de passe.
    s' il tape un password erroné il peut pas entrer et rien sera afficher .
    s'il tape son password vrai , ici il retre directement dans sa session et un msg "vous etes connecté en tant que : mail " sera affiché . 
   - j'ai mis 2 boutton un pour la connection et l'autre pour le reset.
  # identifiant/mot de passe : 
    si vous vouler tester avec un user qui est déja insérer dans la bdd vous pouver utiliser .
      email : maria.bosli.pro@gmail.com
      mdp : maria
