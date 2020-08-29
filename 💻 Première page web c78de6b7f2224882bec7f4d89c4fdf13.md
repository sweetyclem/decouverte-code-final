# 💻 Première page web

# INTRODUCTION

## **Présentation de la formatrice**

[Clémentine Pirlot - Software Developer - HiMama | LinkedIn](https://www.linkedin.com/in/clementine-pirlot/)

## **Les bases du web**

[%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/initiation-html-horizon-numerique.pdf](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/initiation-html-horizon-numerique.pdf)

# ATELIER

## **Objectif**

Nous allons créer une page de présentation type CV. Notre site sera statique, c'est à dire que tout le contenu sera dans le code. Par opposition, un site dynamique est un site où le contenu n'est pas connu à l'avance et qui utilise souvent une base de donnée.

## Ressources

**Exemples**

Fanny: [https://m64dw.csb.app/](https://m64dw.csb.app/)

Clémentine: [https://clementine-pirlot.netlify.app/](https://clementine-pirlot.netlify.app/) 

**Code complet**

Fanny: [https://codesandbox.io/s/decouverte-code-complet-fanny-m64dw](https://codesandbox.io/s/decouverte-code-complet-fanny-m64dw)

Clementine: [https://codesandbox.io/s/decouverte-code-complet-clementine-wlvxd](https://codesandbox.io/s/decouverte-code-complet-clementine-wlvxd?from-embed)

**Code début** 

[https://codesandbox.io/s/decouverte-code-debut-3uk0n](https://codesandbox.io/s/decouverte-code-debut-3uk0n)

Langages utilisés : 

- HTML pour le contenu
- CSS pour la mise en forme

## Mise en place de l'environnement de travail

1. cliquez sur le lien [https://codesandbox.io/s/decouverte-code-debut-3uk0n](https://codesandbox.io/s/decouverte-code-debut-3uk0n)
2. cliquez sur le bouton `fork` pour créer une copie sur laquelle vous allez travailler

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-20_a_12.38.25.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-20_a_12.38.25.png)

3. renommez ce fichier en écrivant votre nom à la place de DEBUT

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-20_a_12.36.54.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-20_a_12.36.54.png)

4. cliquez sur le bouton *Open in new windo*w pour prévisualiser votre page dans un onglet de votre navigateur

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-20_a_12.45.53.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-20_a_12.45.53.png)

5. cliquez sur l'icône play pour cacher ou afficher la prévisualisation afin de faire de la place à votre fenêtre de code

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/imageedit_2_4479235644.jpg](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/imageedit_2_4479235644.jpg)

6. cliquez sur l'icône *fichiers* pour faire encore plus de place à votre fenêtre de code

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-20_a_12.55.31.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-20_a_12.55.31.png)

À ce stade, vous devez avoir :

- un onglet de votre navigateur pour la fenêtre de code
- un onglet de votre navigateur pour la prévisualisation de votre page

Si vous avez ces deux éléments, revenez dans Zoom et cliquez sur yes.

## **Bases de la page**

Toutes les pages web comportent au minimum les balises suivantes :

```html
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```

Une balise est en général composée d'une **balise ouvrante** et d'une **balise fermante**.

Les balises sont imbriquées : **dernière balise ouverte = première balise fermée**

### **<head></head>**

La balise `head` ne contient rien qui est visible sur la page, elle sert à **passer des informations meta au navigateur** : encodage des caractères, chargement de fichiers externes, titre du document, etc.

Dans le code HTML, il s'écrit à l'intérieur de la balise `head` :

```html
<head>
	****<title>Site de Clémentine Pirlot</title>
</head>
```

Le titre du document s’affiche dans l'onglet de la barre supérieure du navigateur.

![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Untitled.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Untitled.png)

**ASTUCE**
Si vous commencez à taper le nom de la balise (sans chevron) que vous souhaitez insérer, CodeSandbox ouvre une liste de propositions. Il suffit alors de sélectionner votre balise.

**À VOUS !**

1. Ajoutez la balise `title` à l'intérieur de la balise `head` 
2. Entre la balise ouvrante et la balise fermante, écrivez "Site de *Prénom Nom*" (remplacez *Prénom Nom* par votre prénom et votre nom)
3. Allez sur l'onglet de prévisualisation et actualisez votre page

Si le titre de l'onglet affiche bien le nouveau titre, revenez dans Zoom et cliquez sur yes.

### **<body></body>**

C'est dans la balise `body` que l'on insère le **contenu qui sera visible dans le navigateur :** textes, images, liens,…

## **Header avec image**

Notre header va être constitué d'une image de fond et d'un titre. Pour des questions de référencement et d'accessibilité (par exemple pour les personnes mal voyantes) la structure doit utiliser des balises qui ont du sens pour les robots. Nous allons donc créer une zone d'en-tête grâce à la balise `header` puis insérer une balise `h1` pour le titre principal de la page.

```html
<header>
  <h1<img src="profile.jpg" alt="Photo de Clementine" />
      <h2>Présentation</h2>
      <p>
        Bonjour, je suis Clémentine Pirlot une développeuse française à Toronto!
        Après des études d'informatique au Greta de Lyon et à l'<a
          href="https://www.42.fr/"
          target="_blank"
          >Ecole 42</a
        >, ainsi que des expériences professionelles dans des grandes et petites
        entreprises, je suis actuellement développeuse fullstack chez HiMama,
        une startup de l'edtech à Toronto, au Canada.
      </p>>Clémentine Pirlot</h1>
</header>
```

Une fois la structure HTML créée, on va mettre en forme le header grâce aux styles CSS.

### **Image de fond**

Dans le dossier du projet, vous avez une image appelée `header.jpg`. C'est cette image qui va servir de fond à notre zone header.

Vous avez également, dans le dossier du projet, un fichier nommé `styles.css`. C'est dans ce fichier que l'on va ajouter les styles pour la mise en forme de notre page.

Pour que le fichier `index.html` sache où il doit prendre les styles, il faudra le relier au fichier `styles.css` grâce à la balise `link`.

**À VOUS !**

1. Ajoutez le code HTML suivant dans votre fichier `index.html` et modifiez le prénom et le nom

    ```html
    <header>
      <h1>Fanny Lochu</h1>
    </header>
    ```

2. Double-cliquez sur le fichier `styles.css` présent dans le dossier de votre projet
3. Copiez le code suivant dans `styles.css`

    ```css
    header {
      background-image: url("header.jpg");
      background-size: cover;
      height: 550px;
    }
    ```

    Ce bout de code permet de cibler la balise `header`, et lui appliquer une image de fond, qui couvre toute la place disponible, ainsi qu'une hauteur de 550px.

4. Revenez dans le fichier `index.html` et insérez la balise `link` dans la partie `head` (sous `title`), pour relier le fichier `styles.css` 

    ```html
    <head>
    	****<title>Site de Fanny Lochu</title>
    	<link href="./styles.css" rel="stylesheet" />
    </head>
    ```

5. Allez sur l'onglet de prévisualisation et actualisez votre page

Si votre page affiche bien l'image de fond, revenez dans Zoom et cliquez sur yes.

### **Titre h1**

Il s'agit maintenant d'appliquer des styles propres au titre h1 :

- une taille de typo grâce à la propriété `font-size`
- une couleur de typo grâce à la propriété `color`

**À VOUS !**

1. Dans le fichier `styles.css`, ciblez la balise `h1` pour lui appliquer une taille et une couleur de typo 

    ```css
    h1 {
      font-size: 56px;
      color: white;
    }
    ```

2. Allez sur l'onglet de prévisualisation et actualisez votre page

Si votre titre est blanc et plus gros, revenez dans Zoom et cliquez sur yes.

Pour que l'image soit plus jolie et le titre plus lisible, on va appliquer un filtre gris par dessus.

Puis on positionnera notre titre au centre du header.

**À VOUS !**

1. Dans votre fichier `styles.css`, modifiez l'apparence de l'image en remplaçant `background-image: url("header.jpg");` par le code suivant

    ```css
    background: linear-gradient(
          0deg,
          rgba(44, 44, 44, 0.6),
          rgba(44, 44, 44, 0.6)
        ),
        url("header.jpg");
    ```

2. Centrez le titre dans le header en appliquant les propriétés suivantes à la balise `header`

    ```css
    display: flex;
    align-items: center;
    justify-content: center;
    ```

3. Allez sur l'onglet de prévisualisation et actualisez votre page

Si un filtre gris est apparu sur l'image et que le titre est centré dans le header, revenez dans Zoom et cliquez sur yes.

### **Styles généraux**

En CSS, les balises situées à l'intérieur d'une autre héritent des propriétés de la balise supérieure. Ainsi, en appliquant une typo à `body`, le titre `h1` héritera de cette même typo.

Une fois la typo modifiée, on va **supprimer les marges** de la balise `body` pour que l'image soit bien collée aux bords de la fenêtre du navigateur.

**À VOUS !**

1. Dans le fichier `index.html`, utilisez la balise `link` dans la partie `head` (sous `title`) pour charger la typo Montserrat depuis la bibliothèque Google Fonts

    ```html
    <head>
    	****<title>Site de Fanny Lochu</title>
    	<link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet"/>
    	<link href="./styles.css" rel="stylesheet" />
    </head>

    ```

2. Dans le fichier `styles.css`, ciblez la balise `body` pour lui appliquer la famille de typo Montserrat, puis supprimez les marges grâce à la propriété `margin`.

    ```css
    body {
      font-family: Montserrat;
    	margin: 0;
    }
    ```

3. Allez sur l'onglet de prévisualisation et actualisez votre page

Si l'image de fond est bien collée aux bords de votre fenêtre et que votre titre est bien écrit avec une typo baton, revenez dans Zoom et cliquez sur yes.

Si votre nom a un accent, ça va afficher des caractères bizarres, que vous avez peut être déjà vus avant. C'est simplement que le navigateur ne sait pas qu'il faut utiliser un encodage pour ces caractères spéciaux. Donc pour lui dire de décoder les accents, on va ajouter une instruction dans la balise `head` :

```html
<meta charset="UTF-8">
```

## **Section Présentation**

### **Structure HTML**

On peut maintenant ajouter un paragraphe de présentation qui en dit plus sur nous. 

À la suite du bloc `header`, nous allons créer un nouveau bloc avec la balise `section`.

À l'intérieur de cette balise `section`, nous allons insérer :

- une photo de profile avec la balise `img`
- un titre `h2`
- un paragraphe`p` avec notre texte de présentation
- un lien `a` vers une page de profile LinkedIn

**À VOUS !**

1. Dans votre fichier `index.html`, à la suite de la balise fermante `</header>`, insérez une balise `section`

    ```html
    <section>

    </section>
    ```

2. À l'intérieur de la balise `section`, intégrez une image en utilisant le code suivant

    ```html
    <img src="images/profile.jpg" alt="Photo de Clementine" />
    ```

    Note : vous pouvez intégrer une photo de votre ordinateur en cliquant sur le dossier *"images"* puis sur le bouton *"upload Files"* pour l'ajouter dans le dossier image de votre projet.

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-21_a_16.22.20.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-21_a_16.22.20.png)

    **Attention** : le nom de votre image dans votre code doit être exactement le même que dans votre dossier *"images"* , et il ne faut pas d'espace dans le nom.
    Par exemple, si votre image s'appelle `ma-photo.jpg`, votre code HTML sera

    ```html
    <img src="images/ma-photo.jpg" alt="Photo de ..." />
    ```

3. Sous la balise fermante `img`, ajoutez une balise `h2`, pour insérer un titre de deuxième niveau 

    ```html
    <h2>Présentation</h2>
    ```

4. Sous la balise fermante `h2`, ajoutez une balise `p`, pour insérer un paragraphe 

    ```html
    <p>
      Bonjour, je suis Clémentine Pirlot une développeuse française à Toronto!
      Après des études d'informatique au Greta de Lyon et à l'Ecole 42, ainsi que des expériences professionelles dans des grandes et petites
      entreprises, je suis actuellement développeuse fullstack chez HiMama,
      une startup de l'edtech à Toronto, au Canada.
    </p>
    ```

    Note : la balise `br` permet d'insérer un saut de ligne à l'endroit où on la place, comme si on appuyait sur la touche `entrée` de notre clavier. `br` ne suis pas la structure balise ouvrante-balise fermante ; on dit qu'elle est orpheline.

5. Pour faire un lien vers un profile LinkedIn, remplacer *"développeuse"* par le code suivant

    ```html
    <a href="https://www.linkedin.com/in/clementine-pirlot/" target="_blank">développeuse</a>
    ```

6. Afin d'identifier précisément cette section et lui donner des styles différents des autres sections que nous ajouterons ensuite, ajoutez-lui une classe `about`, dans la balise ouvrante `section`

    ```html
    <section class="about">
    ```

7. Vérifiez que le code de votre bloc présentation ressemble à :

    ```html
    <section class="about">
      <img src="images/profile.jpg" alt="Photo de Clementine" />
      <h2>Présentation</h2>
      <p>
        Bonjour, je suis Clémentine Pirlot une
        <a href="https://www.linkedin.com/in/clementine-pirlot/" target="_blank"
          >développeuse</a
        >
        française à Toronto! Après des études d'informatique au Greta de Lyon et
        à l'Ecole 42, ainsi que des expériences professionelles dans des grandes
        et petites entreprises, je suis actuellement développeuse fullstack chez
        HiMama, une startup de l'edtech à Toronto, au Canada.
      </p>
    </section>
    ```

8. Allez sur l'onglet de prévisualisation et actualisez votre page

Si votre image, le titre et le paragraphe s'affichent, revenez dans Zoom et cliquez sur yes.

### **Styles CSS**

Il faut maintenant mettre en forme ce bloc, en ajoutant des styles dans le fichier `styles.css`

**À VOUS !**

1. Ajoutez le code suivant pour centrer et redimensionner le bloc

    ```css
    .about {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      width: 70%;
      margin: 70px auto;
      padding: 20px;
      padding-top: 0;
      box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2);
    }
    ```

2. Ajoutez le code suivant pour cibler l'image de la section `.about` et :
    - créer une image arrondie
    - modifier sa taille
    - réduire la marge en haut

    ```css
    .about img {
      border-radius: 50%;
      width: 150px;
      margin-top: -30px;
    }
    ```

3. Ciblez la balise `h2` pour lui appliquer une taille de typo et modifier ses marges

    ```css
    h2 {
      font-size: 24px;
      margin-top: 30px;
      margin-bottom: 15px;
    }
    ```

4. Ciblez la balise `a` pour changer la couleur du lien et supprimer son soulignement

    ```css
    a {
      color: #129daf;
      text-decoration: none;
    }
    ```

## **Section Compétences**

### **Structure HTML**

Nous allons maintenant ajouter une nouvelle section pour présenter nos compétences. Cette section sera composée de :

- un titre `h2`
- un conteneur général (`.skills-content`) contenant toutes les compétences
- des lignes (`.skills-row`) contenant chacune deux colonnes (`.skills-column`) permettant d'afficher deux compétences

![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-24_a_17.19.34.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Capture_decran_2020-08-24_a_17.19.34.png)

**À VOUS !**

1. Dans votre fichier `index.html`, à la suite de la balise fermante `</section>`, insérez une nouvelle balise `section` et donnez-lui la classe `.skills` pour la différencier de la section précédente (`.about`)

    ```html
    <section class="skills">

    </section>
    ```

2. À l'intérieur de cette nouvelle balise `section`, insérez un titre `h2`

    ```html
    <section class="skills">
    	<h2>Compétences</h2>
    </section>
    ```

3. Après le titre `h2`, ajoutez le conteneur général des compétences, avec à l'intérieur,  une ligne contenant deux colonnes

    ```html
    <section class="skills">
      <h2>Compétences</h2>
      <div class="skills-content">
    		<div class="skills-row">
          <div class="skills-column">
    			</div>
    			<!-- Fin .skills-column -->
    			<div class="skills-column">
    			</div>
    			<!-- Fin .skills-column -->
    		</div>
    		<!-- Fin .skills-row -->
      </div>
    	<!-- Fin .skills-content -->
    </section>
    ```

4. À l'intérieur de la première colonne (`.skills-column`), ajoutez le code suivant pour créer la première compétence

    ```html
    <div class="progress-container">
      <span class="progress-badge">HTML</span>
      <div class="progress">
        <div class="progress-bar" style="width: 90%;"></div>
        <span class="progress-value">90%</span>
      </div>
    </div>
    ```

5. À l'intérieur de la deuxième colonne (`.skills-column`), ajoutez le code suivant pour créer la deuxième compétence

    ```html
    <div class="progress-container">
      <span class="progress-badge">CSS</span>
      <div class="progress">
        <div class="progress-bar" style="width: 75%;"></div>
        <span class="progress-value">75%</span>
      </div>
    </div>
    ```

6. Allez sur l'onglet de prévisualisation et actualisez votre page

Si le titre et deux compétences s'affichent comme sur le screenshot ci-dessous, revenez dans Zoom et cliquez sur yes.              

![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Untitled%201.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Untitled%201.png)

                                              *Bloc Compétences avant mise en forme CSS*

### **Styles CSS**

Les styles CSS vont permettre de rendre ce nouveau bloc plus joli. 

**À VOUS !**

1. Pour centrer le bloc et créer la grille, ajoutez le code suivant dans le fichier `styles.css`

    ```css
    /* SKILLS
    –––––––––––––––––––––––––––––––––––––––––––––––––– */

    .skills {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      margin: 70px auto;
      padding: 20px;
      padding-top: 0;
    }

    .skills-content {
      margin: 0 auto 70px auto;
      padding: 20px;
      width: 70%;
      box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2);
    	text-align: left;
    }

    .skills-row {
      display: flex;
    }

    .skills-column {
      display: flex;
      flex: 1 1 50%;
      padding-right: 15px;
      padding-left: 15px;
    }
    ```

2. Pour mettre en forme la barre de progrès, ajoutez les styles suivants

    ```css
    .progress-container {
      margin-bottom: 20px;
      font-size: 18px;
      position: relative;
      width: 100%;
    }

    .progress-value,
    .progress-badge {
      color: #0b707e;
      font-size: 0.8571em;
      text-transform: uppercase;
    }

    .progress-value {
      position: absolute;
      top: 2px;
      right: 0;
      font-size: 0.8571em;
    }

    .progress {
      margin-top: 14px;
    }

    .progress {
      background: rgba(25, 105, 129, 0.4);
    }

    .progress-bar {
      height: 5px;
    }

    .progress-bar {
      background: #129daf;
    }
    ```

3. Allez sur l'onglet de prévisualisation et actualisez votre page

Si les deux compétences apparaissent avec la bonne mise en forme, comme sur le screenshot ci-dessous, revenez dans Zoom et cliquez sur yes.

![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Untitled%202.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Untitled%202.png)

### **Ajout de compétences**

Pour ajouter une ligne avec deux compétences, il suffit d'ajouter un bloc `skills-row` à la suite du premier `skills-row`:

```html
<div class="skills-row">
  <div class="skills-column">
    <div class="progress-container">
      <span class="progress-badge">RUBY</span>
      <div class="progress">
        <div class="progress-bar" style="width: 80%;"></div>
        <span class="progress-value">80%</span>
      </div>
    </div>
  </div>
  <div class="skills-column">
    <div class="progress-container">
      <span class="progress-badge">JAVASCRIPT</span>
      <div class="progress">
        <div class="progress-bar" style="width: 60%;"></div>
        <span class="progress-value">60%</span>
      </div>
    </div>
  </div>
</div>
<!-- Fin .skills-row -->
```

**À VOUS !**

1. Copiez et collez le code ci-dessus dans votre fichier `index.html`, à la suite du dernier commentaire `<!-- Fin .skills-row -->` 
2. Répétez la dernière opération pour ajouter une troisième ligne de compétences
3. Modifiez le contenu des compétences pour l'adapter à votre profil. 
Par exemple, si vous savez utiliser le logiciel Word,
remplacez

    ```html
    <span class="progress-badge">HTML</span>
    ```

    par

    ```html
    <span class="progress-badge">Word</span>
    ```

4. Pour modifier le pourcentage indiquant le niveau de maitrise, remplacez les chiffres de `progress-bar` et `progress-value`

    ```html
    <div class="progress-bar" style="width: 90%;"></div>
    <span class="progress-value">90%</span>
    ```

Lorsque vous avez ajouté et modifié au moins 2 compétences, revenez dans Zoom et cliquez sur yes.

## Effet parallax

Grâce aux styles CSS, nous pouvons ajouter un effet parallax à notre page. Cet effet permet de laisser fixe l'image de fond du header lorsque l'on scrolle la page.

**À VOUS !**

1. Dans le css du `header`, ajoutez le code suivant, après la ligne `justify-content: center;`

```css
background-attachment: fixed;
background-position: center;
background-repeat: no-repeat;
```

Si vous voyez l'image fixe lorsque vous scrollez sur la page, revenez dans Zoom et cliquez sur yes.

## **Section expérience**

Nous allons ajouter une nouvelle section pour présenter nos expériences professionnelles sous forme de timeline.

### **Structure HTML**

Ce sont les balises `ul` et `li` qui vont nous servir à créer la structure de cette section. Ces balises sont utilisées pour lister des éléments (ici nos expériences). 

La syntaxe d'une liste `ul` est toujours la suivante :

```html
<ul>
	<li>Élément 1</li>
	<li>Élément 2</li>
	<li>Élément 3</li>
</ul>
```

`ul` indique une liste non ordonnées (unordered list en anglais)
`li` est utilisé pour chaque élément de la liste

Notre section Expérience sera donc composée d'un conteneur général `.timeline` comportant :

- Un titre `h2`
- Une liste `ul` avec une balise `li` pour chaque expérience

```html
<section class="timeline">
  <h2>Expérience</h2>
	<ul>
		<li>
			Expérience 1
		</li>
		<li>
			Expérience 2
		</li>
		...
	</ul>
</section>
```

Pour chaque expérience, dans la balise `li`, nous aurons un conteneur `.bubble` comportant 3 lignes :

- Les dates du poste occupé avec la balise `time`
- L'intitulé du poste avec `span`
- Le lieu

```html
<section class="timeline">
  <h2>Expérience</h2>
	<ul>
		<!-- Début expérience 1 -->
    <li>
      <div class="bubble">
        <time>2019 - aujourd'hui</time>
        <span>Développeuse</span>
        <br />HiMama, Toronto
      </div>
    </li>
    <!-- Fin expérience 1 -->
    <!-- Début expérience 2 -->
    <li>
      <div class="bubble">
        <time>2018 - 2019</time>
        <span>Développeuse</span>
        <br />Borrowell, Toronto
      </div>
    </li>
    <!-- Fin expérience 2 -->
	</ul>
</section>
```

**À VOUS !**

1. Ajoutez le code ci-dessus dans le fichier `index.html`
2. Allez sur l'onglet de prévisualisation et actualisez votre page. 
Le bloc devrait s'afficher comme sur le screenshot suivant : 

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Untitled%203.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Untitled%203.png)

3. Revenez dans `index.html` et ajoutez 2 ou 3 éléments à la liste. Pour cela, il suffit de copier/coller un bloc comme celui-ci :

    ```html
    <!-- Début expérience 3 -->
    <li>
      <div class="bubble">
        <time>2018</time>
        <span>Développeuse</span>
        <br />Je rêve d'une Maison, Paris
      </div>
    </li>
    <!-- Fin expérience 3 -->
    ```

     Vous pouvez ensuite modifier le contenu en changeant l'année dans la balise `time`, l'intitulé du poste dans la balise `span` et le lieu après `br`

Lorsque votre bloc Expérience affiche 4 ou 5 éléments, revenez dans Zoom et cliquez sur yes.

### **Styles CSS**

La communauté tech est basée sur le partage et on utilise très souvent du code récupéré sur Internet. C'est ce que vous allez faire ici, avec le code ci-dessous, qui permet de mettre en forme la timeline.

```css
/* TIMELINE
–––––––––––––––––––––––––––––––––––––––––––––––––– */
html {
  overflow-x: hidden;
}

.timeline h2 {
  text-align: center;
}

.timeline ul {
  padding: 50px 0;
}

.timeline ul li {
  list-style-type: none;
  position: relative;
  width: 6px;
  margin: 0 auto;
  padding-top: 50px;
  background: rgba(25, 105, 129, 0.4);
  color: white;
}

.timeline ul li::after {
  content: "";
  position: absolute;
  left: 50%;
  bottom: 0;
  transform: translateX(-50%);
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background: inherit;
}

.timeline .bubble {
  position: relative;
  bottom: 0;
  width: 400px;
  padding: 15px;
  background: rgba(18, 157, 175, 0.8);
  box-sizing: border-box;
}

.timeline .bubble::before {
  content: "";
  position: absolute;
  bottom: 7px;
  width: 0;
  height: 0;
  border-style: solid;
}

.timeline ul li:nth-child(odd) .bubble {
  left: 45px;
}

.timeline ul li:nth-child(odd) .bubble::before {
  left: -15px;
  border-width: 8px 16px 8px 0;
  border-color: transparent rgba(18, 157, 175, 0.8) transparent transparent;
}

.timeline ul li:nth-child(even) .bubble {
  left: -439px;
}

.timeline ul li:nth-child(even) .bubble::before {
  right: -15px;
  border-width: 8px 0 8px 16px;
  border-color: transparent transparent transparent rgba(18, 157, 175, 0.8);
}

time {
  display: block;
  font-size: 1.2rem;
  font-weight: bold;
  margin-bottom: 8px;
}

.bubble span {
  font-weight: bold;
}
```

**À VOUS !**

1. À la fin du fichier `styles.css` copiez le code ci-dessus
2. Allez sur l'onglet de prévisualisation et actualisez votre page

Si votre timeline est maintenant mise en forme, revenez dans Zoom et cliquez sur yes.

## Carte Google

Une carte Google rendra notre site très professionnel et indiquera aux visiteurs la ville où nous travaillons. On ne va pas mettre notre adresse exacte parce qu'on veut pas que le monde entier sache où on habite, on va plutôt mettre notre ville.

Notre codesandbox et les dossiers qu'on va mettre sur Github sont publics. On ne veut pas mettre d'informations personnelles comme un numéro de téléphone ou un email, ou une addresse. On risquerait d'être inondée de spam parce qu'il existe de nombreux robots qui lisent toutes les pages web qui existent et piquent ces infos. 

**À VOUS !**

1. Ajoutez une nouvelle section dans `index.html` avant la balise de fermeture du `body`

    ```html
    <section class="contact">
      <h2>Contact</h2>
    </section>
    ```

2. Allez sur [https://maps.google.com](https://maps.google.com) et tapez votre ville. Cliquez sur `Partager`

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Screen_Shot_2020-08-15_at_12.19.41_PM.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Screen_Shot_2020-08-15_at_12.19.41_PM.png)

3. Cliquez sur `Intégrer une carte`

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Screen_Shot_2020-08-15_at_12.20.17_PM.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Screen_Shot_2020-08-15_at_12.20.17_PM.png)

4. Cliquez sur `Copier le contenu HTML`

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Screen_Shot_2020-08-15_at_12.20.24_PM.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20c78de6b7f2224882bec7f4d89c4fdf13/Screen_Shot_2020-08-15_at_12.20.24_PM.png)

5. Insérez le code HTML copié dans `index.html`  après la balise `h2`
6. Allez sur l'onglet de prévisualisation et actualisez votre page

Si une carte Google avec votre ville apparait au bas de la page, revenez dans Zoom et cliquez sur yes.

## Pour aller plus loin

Notre site est maintenant presque complet. La page suivante vous permettra de le finir totalement en ajoutant un formulaire de contact, des styles pour les petits écrans et en mettant en ligne gratuitement votre site.

**À VOUS !**

1. Suivez les instructions détaillées sur cette page

    [Pour aller plus loin](https://www.notion.so/Pour-aller-plus-loin-2d868f1794754228bdccedf8ae3644a9)