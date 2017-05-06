# loup-ardent
(Automatically exported from code.google.com/p/loup-ardent)

#summary manuel d'installation et d'utilisation.

-2 liens
http://planete-ldvelh.com/page/liens.html
http://en.wikipedia.org/wiki/Sagas_of_the_Demonspawn
http://fr.wikipedia.org/wiki/Loup*_Ardent

http://www.la-taverne-des-aventuriers.com/t3997-loupardent-outil-outil-pour-gerer-les-combats

-1.Description
courte
simulate gamebook character generation and combats for demonspawn serie.

longue
Simuler la création de personnage et les combats pour la série de livres dont vous êtes le héros "Loup*Ardent".

Simulate character generation and combats for "Demonspawn" gamebook serie. 

= Index =
0.Nouveautés

1.Étapes pour utiliser loup-ardent

2.Plus d'informations pour les utilisateurs de windows pour installer un environnement JAVA...

3.Changelog

4.Problèmes connus

= Details =
*0.nouveautés
L'executable ci apres rend obsolete les étapes (fastidieuses) ci apres pour les utilisateurs de windows:

https://drive.google.com/file/d/0B8o5p18XEsgHbkxfX1VyNmYtNm8/edit?usp=sharing

*1.Étapes pour utiliser loup-ardent

Les pré requis:
  * Un ordinateur exécutant linux ou windows (ou autre...)

  * Un environnement d'exécution Java (JRE) version 5 minimum
(http://java.com/inc/BrowserRedirect1.jsp?locale=fr)

  * Télécharger le fichier loupArdent.jar dans l onglet downloads de ce wiki *OU* directement sur cette URL https://loup-ardent.googlecode.com/files/loupArdent-v1.0.jar

  * Ouvrir un interpréteur de commandes ou une console (cmd.exe ou bash selon les systèmes d'exploitation...)
taper par exemple : *java -jar loupArdent-v1.0.jar*

  * Suivre les instructions du menu texte affiché.

*2.Plus d'infos pour les utilisateurs de Windows pour installer un environnement JAVA...

Démarrer -> programmes -> accessoires -> Invite de commande
Taper: java -version
Deux cas se présentent :

  * soit le texte "java n'est pas reconnu en tant que commande interne ou externe, un programme exécutable ou un fichier de commande"
et la il te faut installer ca : http://java.com/inc/BrowserRedirect1.jsp?locale=fr

puis Menu démarrer -> Clic droit sur le poste de travail -> Propriété -> Onglet Avancé -> Bouton variable d'environnement
Et la tu double clique sur la variable path en bas puis tu ajoute un point virgule a la fin des chemins et tu rajoutes "chemin de ton répertoire ou est installé java"\bin

java sera exécutable partout !

  * soit le texte te donnant la version de ton java et là il faut que le nombre donné soit supérieur ou égal 1.5.

*3.Changelog

  * v0.1 : Livraison initiale

  * v1.0 : Ajout de la gestion d Exterminator
       Testé avec "La Horde des Démons"

*4.Problèmes connus

  * PROBLÈME
J'ai créé un perso, les caract. s'affichent mais quand je veux l'enregistrer ça me fait:

{{{
java.io.FileNotFoundException: Loup.ser (Accès refusé)
         at java.io.FileOutputStream.open (Native Method)
         at java.io.FileOutputStream.(init)(Unknown Source)
         at java.io.FileOutputStream.(init)(Unknown Source)
         at fr.fdunan.jdr.c.a(Unknown Source)
         at fr.fdunan.jdr.InterfaceUtilisateur.main(Unknown Source)
}}}

  * SOLUTION
lancer loupArdent-vx.y.jar dans un répertoire ou l utilisateur Windows qui lance la commande a les droits en écriture.

exemple:
  * copier loupArdent-v1.0.jar dans c:\Users\MonUser avec l explorateur
  * lancer l interpréteur de commandes

Taper :
{{{
        cd c:\Users\MonUser  (taper entrée sur le clavier)
        java -jar loupArdent-v1.0.jar (taper entrée sur le clavier)
}}}
