# TP_Injection_Des_dependances

Dans Cette partie on a faire un petite application pour bien comprendre la notion "couplage faible"(= l'application doit etre fermé a la modification et ouvert à l'extension).

Tout d'abord on a crée des insterfaces et des implémentations de ces interfaces.
Et on a voir l'injection des dépendances par instanciation statique (ici si on veut avoir des extension on doit faire des changement dans la classe présentation c-à-d notre application n'est pas complétement fermé a la modification )

![image](https://user-images.githubusercontent.com/84719124/162339889-13977519-28e2-4227-91e6-52fc14f111bf.png)



![image](https://user-images.githubusercontent.com/84719124/162339912-eac751e1-845a-489f-be94-2de41b54148e.png)



Et on a voir l'injection des dépendances par instanciation dynamique ( ici on a créé un fichier text de configuration ou on a declaré les non des classes qu'on a utilisé dans l'application et  si on veut avoir des extension on doit seulement changer les noms des classes dans le fichier de configuration sans toucher le code source)


voici le fichier de configuration :
![image](https://user-images.githubusercontent.com/84719124/162340799-931fbf47-7c2b-4192-8f25-4d5b6312bb7d.png)

après l'exucution du code on trouve :
![image](https://user-images.githubusercontent.com/84719124/162341034-e9ce2eb5-4437-4969-b93e-9f9773aea763.png)


Enfin on a l'exucution du code après faire des modification dans le fichier de configuration :
![image](https://user-images.githubusercontent.com/84719124/162341237-47c56cbe-d818-428d-9356-9aa7fb93c08d.png)

