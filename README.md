


## Expression des besoins

Version 1.0

DOUARD alexandre
10/08/2017








## 1 Le Projet

**1.1	Objectif**

Ce projet a pour objectif la création d’une application de divertissement de type « Pictionary » comprenant deux modes de jeux :

-Un mode multijoueur : joueur / joueur en temps réel

-Un mode solo joueur / IA

Un mot est proposé au joueur, il a 20 secondes pour le dessiner et ainsi le faire deviner, soit à un autre joueur, soit à l’IA en fonction du mode jeux choisi.

La rétribution des points est collaborative et non compétitive.

### **1.2	Portée du projet**

Cette application ludique et éducative s’adresse à un public recherchant un divertissement créatif, sur un temps court, rapidement accessible et simple d’utilisation à partir d’un smartphone. Elle s’adresse particulièrement aux nostalgiques des jeux de société en famille.

Elle nécessite une connexion internet.

### **1.3	Rappel contextuel**

On peut noter l’existence de nombreuses applications de dessin type « Pictionary » dans le secteur du divertissement mobile. Toutefois il s’agit ici de répondre à plusieurs carences observées lors du développement du projet.

-Créer un jeux 100% Français avec différentes catégories de mots plus ou moins ardues.

-Permettre un mode multijoueur en temps réel.

-Pour le mode solo, intégrer une intelligence artificielle de reconnaissance de dessin à apprentissage progressif (c’est le joueur qui participe à l’amélioration et au développement de l’IA).

Parmi les projets les plus notoires, on peut citer l’application **DrawSomething** qui rassemble 50 Millions d’utilisateurs dès sa sortie et l’expérience **Quick, Draw !** développée par AI. Experiment avec l’aide de Google, qui propose son réseau neuronal (AI) en open-source.

**DrawSomething** :  https://play.google.com/store/apps/details?id=com.omgpop.dstfree&hl=fr

**Quick, Draw** ! :  https://quickdraw.withgoogle.com/ 



## 2	Le Système

### **2.1	Expérience utilisateur**

Cette application comprend : 

- la création d’un compte utilisateur (Connexion via Facebook ou mail) 

- la personnalisation du compte utilisateur (Avatar, ranking, points, possibilité d’inviter des amis)

- deux modes de jeux : solo ou multijoueur. Dans le mode solo, l’utilisateur dessine et dans le mode multijoueur, deux options se présentent à lui : dessiner ou deviner.

- une boutique afin de dépenser les points gagnés (packs évènementiels de catégories de mots/ outils pour dessiner).

- une icône on/off pour le son.

Globalement tout sera mis en œuvre pour optimiser l’expérience utilisateur et avoir une appréhension du jeu fluide, intuitive et agréable. Une bonne dose d’humour participerait favorablement à l’expérience.

### **2.2	Exemples**

1er exemple :

*Robert joue pour la première fois, il n’a pas encore de compte utilisateur, il possède un compte Facebook et il souhaite jouer en solo.*

Il va pouvoir créer son compte utilisateur à partir de son compte Facebook et ainsi se connecter très rapidement au jeu. De plus il va pouvoir inviter ses contact/amis Facebook à le rejoindre. Il va ensuite choisir le mode de jeu solo et rentrer directement dans la phase jeu : un mot lui sera proposé au hasard, il va dessiner et l’IA aura 20 secondes pour deviner ce mot. Robert gagne des points si le mot est deviné à temps. Après un certain nombre de points obtenus, Robert peut se rendre à la boutique afin d’acheter des options avec son magot et ainsi optimiser son niveau.

2ème exemple :

*Kimberley joue aussi pour la première fois, mais n’a pas de compte Facebook. Elle souhaiterait jouer avec d’autres joueurs et préférerait deviner un mot plutôt que de dessiner. Après quelques parties, elle se sent prête à dessiner.*

Elle va créer son compte utilisateur avec son adresse mail et renseigner un pseudo, elle pourra par la suite dans son compte utilisateur importer un avatar. Elle va choisir le mode de jeu multijoueur, deux options lui seront proposées : je dessine ou je devine. Elle choisit de deviner et est mise en connexion avec un autre joueur de la plateforme qui lui aura choisi de dessiner. Elle aura 20 secondes pour deviner le dessin de l’autre joueur qu’elle verra en temps réel. Si elle y parvient, tous les deux auront des points. Si elle échoue, personne ne gagne de point. Si un des deux joueurs abandonne la partie en cours de route, c’est le joueur restant qui obtient des points.

Ce jeu plaît à Kimberley, elle souhaite maintenant dessiner.

A la fin de chaque partie de 20 secondes elle ré-accède aux options je dessine ou je devine. Cette fois ci elle choisit de dessiner et la partie se déroule comme susmentionné. Ces parties lui ont fait gagner quelques points, elle souhaite les conserver pour plus tard, ils seront enregistrés dans son compte utilisateur.

## 3 Description de l’environnement numérique

Cette application doit être dynamique, elle sera développée en HTML, CSS, PHP et Javascript.

L’hébergement de l’application est à définir.

 Les versions technologiques de l’hébergeur devront être compatibles avec l’application.

### **3.1	Exigences techniques**

Cette application a une visée mobile et devra être « responsive » afin de s’adapter à différents types de supports. 

Dès la première connexion avec un appareil, une reconnaissance immédiate du compte utilisateur sera appliquée à une connexion ultérieure (cookies) avec le même appareil.

L’application devra être compatible avec les versions des navigateurs suivants :

Chrome 5+, Safari 5+, Firefox 5+, Internet Explorer 9+.

La charte graphique est à définir.

### **3.2	Volumétrie**

Nous souhaitons pour la phase de test développer une application acceptant jusqu’à 100 utilisateurs en simultané mais au vue des prérogatives, il serait souhaitable d’être rapidement prêt à accueillir le plus grand nombre d’utilisateurs possible.

## 4	Organisation

Pour le suivi continu de l’état d’avancement du projet, une méthodologie de type SCRUM sera employée. Le projet sera découpé en boîtes de temps, nommées « sprints » au bout desquelles seront délivré un incrément du produit.








        




   




