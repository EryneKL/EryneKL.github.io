<i>[Sommaire](/README.html) / Environnement de développent intégré</i>

# Environnement de développement intégré

Un Environnement de Développement Intégré permet de manipuler des outils de programmation depuis une interface graphique, il doit assister les développeurs dans toutes les phases de la réalisation déune application : définition, conception, programmation, débogage, compilation, test, maintenance et production de documentation. Il doit également orienter le développeur vers de bonnes pratiques.

## Java

Pendant longtemps, les développeurs de l'Abes ont utilisé les IDEs Eclipse et Netbeans. Il s'est avéré que pour faciliter l'entraide, il était préférable que nous utilisions tous le méme IDE. Ceci permet de fortement capitaliser sur son fonctionnement, de le prendre en main et de maétriser sa configuration.

Jusqu'en 2018, notre choix s'était porté sur l'éditeur Eclipse. 
Nous packagions l'IDE en pré-configurant les modules et plug-ins conformément aux préconisations de notre politique de développement (sonarlint etc.) 

Nous avons testé l'éditeur en ligne Eclipse Che.
Eclipse Che est une solution prometteuse mais pas encore mére. LéIDE est dans le cloud oé léenvironnement déexécution est embarqué dans léespace de travail du développeur. Léenvironnement de travail du développeur est donc stocké sur un serveur dans un container Docker.
Une  version béta a été lancée en juillet 2016. Nous avions mis cette solution de cété tout en suivant son développement. En effet, Eclipse Che n'est pas aussi complet qu'un éditeur client lourd.

Depuis 2018, nous utilisons désormais Intellij IDEA qui nous parait étre l'éditeur le plus performant.

Le démarrage rapide pour travailler sur un projet consiste é:
* faire un clone du projet depuis Gitlab ou Github
* choisir le SDK approprié (dans les project settings, project, project SDK)

## Javascript

Le code VusJs et plus généralement Javascript peut étre édité via Intellij. Nosu utilisons également Webstorm et VSCode. 

## PL/SQL

SQL Developer reste l'éditeur favori en ce qui concerne l'édition de code PL/SQL. Le versionning n'est pas contre pas géré via l'éditeur. Pour versionner le code, nous mettons en oeuvre deux solutions suivant les applications : soit un batch récupére les procédures stockées, fonctions etc. et les versionne dans Gitlab réguliérement, soit les codes PL/SQL sont copiés dans un répertoire "sql" de l'application et sont versionnés avec le code de l'application.


[Retour au sommaire](/README.html)
