
## Reponse des QUESTIONS
C. 
7. Il faut ignorer __MACOS X, gradle, Build.
    Et commiter src/, build.gradle, settings.gradle, gradle/, gradlew et gradlew.bat, et README.MD et LICENSE

5. Comment peut-on transformer $DEV1 en depot git lie au depot $REMOTE ?
On relie le depot local au depot distant en ajoutant un remote (nomme par convention origin) qui pointe vers l'emplacement de $REMOTE.

7. 
Le repertoire $REMOTE ne contient pas l'arbre habituel des fichiers de code, mais uniquement la structure interne de Git (dossiers objects/, refs/, HEAD, config…).
Explication : C'est tout e fait normal car $REMOTE a ete cree avec git init --bare. C'est un depot « nu » qui sert uniquement de serveur central pour stocker l'historique et synchroniser le code, sans dossier de travail (working directory).
 11. git lol
 * 6a68113 (HEAD -> master, origin/master, origin/HEAD) Initial commit du projet Gradle
 
d. 
4. 
    a) git lol n'affiche pas commit de DEV1
    b) Apres git fetch , dev2 peut voir la commit de Dev1
    c) Il ne s'affiche pas la modification 
    d) il faut ajouter rebase

