# TestEmbauche
cette petite application est developpée en utilisant le framework spring boot avec le moteur de template thymeleaf ainsi qu'une base de données Mysql..
pour utiliser cette application il faut:
- creér une base de données nommée "cabinet" et esuite importer la base de données ci-joint (pas obligatoire)
- ouvrir le projet dans Eclipse ou STS(Spring Tool Suite).
- ouvrir le dossier -->/TestEmbauche/src/main/java-->com.consultation-->TestEmbaucheApplication.java et faire un click droit puis Run As-->Spring Boot App.
- une fois le serveur est bien demarré ouvrir un naviguateur est taper http://localhost:8088/accueil pour acceder à la page d'accueil.
NB : j'ai utilisée les anotations lombok pour la génération des "getters" , des "setters" et les constructeurs, donc si l'IDE que vous allez utiliser n'est pas configurer avec les annotations lombok ça va pas marché , en alterne vous pouvez utiliser les getters et les sitters dans la classe "/TestEmbauche/src/main/java/com/consultation/entites/Consultation.java"
