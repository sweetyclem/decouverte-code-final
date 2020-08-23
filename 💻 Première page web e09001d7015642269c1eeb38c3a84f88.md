# 💻 Première page web

# INTRODUCTION

via horizon-numerique.key ou horizon-numerique.pdf

# ATELIER

## **Objectif**

Créer une page de présentation type CV

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
- JavaScript pour l'interactivité

## Mise en place de l'environnement de travail

1. cliquez sur le lien [https://codesandbox.io/s/decouverte-code-debut-3uk0n](https://codesandbox.io/s/decouverte-code-debut-3uk0n)
2. cliquez sur le bouton *fork* pour créer une copie sur laquelle vous allez travailler

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-20_a_12.38.25.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-20_a_12.38.25.png)

3. renommez ce fichier en écrivant votre nom à la place de DEBUT

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-20_a_12.36.54.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-20_a_12.36.54.png)

4. cliquez sur le bouton *Open in new windo*w pour prévisualiser votre page dans un onglet de votre navigateur

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-20_a_12.45.53.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-20_a_12.45.53.png)

5. cliquez sur l'icône play pour cacher ou afficher la prévisualisation afin de faire de la place à votre fenêtre de code

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/imageedit_2_4479235644.jpg](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/imageedit_2_4479235644.jpg)

6. cliquez sur l'icône *fichiers* pour faire encore plus de place à votre fenêtre de code

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-20_a_12.55.31.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-20_a_12.55.31.png)

À ce stade, vous devez avoir :

- un onglet de votre navigateur pour la fenêtre de code
- un onglet de votre navigateur pour la prévisualisation de votre page

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

La balise `head` ne contient rien qui est visible sur la page, elle sert à **passer des informations meta au navigateur** : encodage des caractères, chargement de fichiers externes, titre du document…
Le titre du document s’affiche dans l'onglet de la barre supérieure du navigateur. 
On va ajouter une balise `title` à l'intérieur de la balise `head` :

```html
<head>
	****<title>Site de Fanny Lochu</title>
</head>
```

**ASTUCE**
Si vous commencez à taper le nom de la balise (sans chevron) que vous souhaitez insérer, CodeSandbox ouvre une liste de propositions. Il suffit alors de sélectionner votre balise.

**À VOUS !**

1. Ajoutez la balise `title` à l'intérieur de la balise `head` 
2. Entre la balise ouvrante et la balise fermante, écrivez "Site de *Prénom Nom*" (remplacer *Prénom Nom* par votre prénom et votre nom)
3. Allez sur l'onglet de prévisualisation et actualisez votre page

Si le titre de l'onglet affiche bien le nouveau titre, revenez dans Zoom et cliquez sur yes.

### **<body></body>**

C'est dans la balise `body` que l'on insère le **contenu qui sera visible dans le navigateur.**

## **Header avec image**

Notre header va être constitué d'une image de fond et d'un titre. Pour des questions de référencement et d'accessibilité (par exemple pour les personnes mal voyantes) la structure doit utiliser des balises qui ont du sens pour les robots. Nous allons donc créer une zone d'en-tête grâce à la balise `header` puis insérer une balise `h1` pour le titre principal de la page.

```html
<header>
  <h1>Fanny Lochu</h1>
</header>
```

Une fois la structure HTML créée, on va mettre en forme le header grâce aux styles CSS.

**Image de fond**

Dans le dossier du projet, vous avez une image appelée `header.jpg`. C'est cette image qui va servir de fond à notre zone header.

Vous avez également, dans le dossier du projet, un fichier nommé `styles.css`. C'est dans ce fichier que l'on va ajouter les styles pour la mise en forme de notre page.

Pour que le fichier `index.html` sache où il doit prendre les styles, il faut le relier au fichier `styles.css` grâce à la balise `link`.

**À VOUS !**

1. Double-cliquez sur le fichier `styles.css` présent dans le dossier de votre projet
2. Copiez le code suivant dans `styles.css`

    ```css
    header {
      background-image: url("header.jpg");
      background-size: cover;
      height: 550px;
    }
    ```

    Ce bout de code permet de cibler la balise `header`, et lui appliquer une image de fond, qui couvre toute la place disponible, ainsi qu'une hauteur de 550px.

3. Revenez dans le fichier `index.html` et insérez la balise `link` dans la partie `head` (sous `title`), pour relier le fichier `styles.css` 

    ```html
    <head>
    	****<title>Site de Fanny Lochu</title>
    	<link href="./styles.css" rel="stylesheet" />
    </head>
    ```

4. Allez sur l'onglet de prévisualisation et actualisez votre page

Si votre page affiche bien l'image de fond, revenez dans Zoom et cliquez sur yes.

**Titre h1**

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

**Styles généraux**

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

## **Section présentation - HTML**

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
    <img src="images/profile.png" alt="Photo de Fanny" />
    ```

    Note : vous pouvez intégrer une photo de votre ordinateur en cliquant sur le dossier *"images"* puis sur le bouton *"upload Files"* pour l'ajouter dans le dossier image de votre projet.

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-21_a_16.22.20.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Capture_decran_2020-08-21_a_16.22.20.png)

    **Attention** : le nom de votre image dans votre code doit être exactement le même que dans votre dossier *"images"* .
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
        Bonjour ! Je suis Fanny Lochu une développeuse web et formatrice basée au sud de Paris.<br />
        Développeuse web full-stack en freelance depuis 2007, je transmets également mes connaissances et mon goût pour le code et la programmation en intervenant dans différentes écoles en tant que formatrice.
    </p>
    ```

    Note : la balise `br` permet d'insérer un saut de ligne à l'endroit où on la place, comme si on appuyait sur la touche `entrée` de notre clavier. `br` ne suis pas la structure balise ouvrante-balise fermante ; on dit qu'elle est orpheline.

5. Pour faire un lien vers un profile LinkedIn, remplacer *"Développeuse web full-stack"* par le code suivant

    ```html
    <a href="https://www.linkedin.com/in/fanny-lochu-886a8a12a/" target="_blank">Développeuse web full-stack</a>
    ```

6. Afin d'identifier précisément cette section et lui donner des styles différents des autres sections que nous ajouterons ensuite, ajoutez-lui une classe `about`, dans la balise ouvrante `section`

    ```html
    <section class="about">
    ```

7. Vérifiez que le code de votre bloc présentation ressemble à :

    ```html
    <section class="about">
    	<img src="images/profile.png" alt="Photo de Fanny" />
      <h2>Présentation</h2>
      <p>
        Bonjour ! Je suis Fanny Lochu une développeuse web et formatrice basée
        au sud de Paris.<br />
        <a href="https://www.linkedin.com/in/fanny-lochu-886a8a12a/" target="_blank">Développeuse web full-stack</a> en freelance depuis 2007, je transmets
        également mes connaissances et mon goût pour le code et la programmation
        en intervenant dans différentes écoles en tant que formatrice.
      </p>
    </section>
    ```

8. Allez sur l'onglet de prévisualisation et actualisez votre page

Si votre image, le titre et le paragraphe s'affichent, revenez dans Zoom et cliquez sur yes.

## **Section présentation - CSS**

Il faut maintenant mettre en forme ce bloc, en ajoutant des styles dans le fichier `styles.css`

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
    - créer une image arrondi
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

# **⇒ Passage sur zoom**

⚠️

On passe sur zoom ici, les participantes vont regarder la formatrice faire et à la fin on leur demande de copier coller sur leur propre codesandbox

Maintenant qu'on a toutes mis la main à la pâte, comme c'est un atelier découverte, je veux vous montrer toutes les super choses qu'on peut faire en codant et vous allez revenir sur zoom pour pouvoir suivre mon partage d'écran. À la fin vous allez copier ce code et le coller dans votre codesandbox et vous aurez deux documents avec des instructions détaillées pour changer le contenu pour y mettre le vôtre et pour mettre en ligne super facilement cette page web super pro.

Je vais copier coller du html et du css que j'ai préparé et pour vous expliquer un peu le processus, on démarre pas avec une page blanche et on écrit tout comme ça de nulle part. Quand on code il y a énormément de partage dans la communauté donc il y a plein de code qu'on trouve et qu'on peut adapter à ses besoins ou à ses préférences. En général on va pas réinventer la roue donc on utilise des bibliothèques ou des modules déjà faits en plus du code qu'on ajoute nous même.

### **Section compétences**

Maintenant on va ajouter une autre section avec nos compétences, en dessous de la présentation. On va mettre des compétences avec pour chaque une jolie barre de progrès pour indiquer notre niveau.

On commence par la structure on ajoute une ligne vide après la section présentation et on ajoute:

```html
<section class="skills">
  <h2>Compétences</h2>
  <div class="skills-content">
		<div class="skills-row">
      <div class="skills-column">
			</div>
		</div>
  </div>
</section>
```

Et dans `styles.css` on va ajouter des styles similaires à notre section présentation pour avoir une jolie carte:

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

Ensuite à l'intérieur de la colonne on va ajouter notre structure de barre de progrès:

```html
<div class="progress-container">
  <span class="progress-badge">HTML</span>
  <div class="progress">
    <div class="progress-bar" style="width: 90%;"></div>
    <span class="progress-value">90%</span>
  </div>
</div>
```

Et on va mettre une 2 ème colonne dans notre ligne:

```html
<div class="skills-column">
  <div class="progress-container">
    <span class="progress-badge">CSS</span>
    <div class="progress">
      <div class="progress-bar" style="width: 75%;"></div>
      <span class="progress-value">75%</span>
    </div>
  </div>
</div>
```

On va ajouter les styles pour la barre de progrès

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

Ça commence à rendre super bien! On va ajouter 2 lignes de compétences à la suite du premier `skills-row`:

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
<div class="skills-row">
  <div class="skills-column">
    <div class="progress-container">
      <span class="progress-badge">C#</span>
      <div class="progress">
        <div class="progress-bar" style="width: 60%;"></div>
        <span class="progress-value">60%</span>
      </div>
    </div>
  </div>
  <div class="skills-column">
    <div class="progress-container">
      <span class="progress-badge">TYPESCRIPT</span>
      <div class="progress">
        <div class="progress-bar" style="width: 50%;"></div>
        <span class="progress-value">50%</span>
      </div>
    </div>
  </div>
</div>
```

Maintenant qu'on a du contenu notre page va être scrollable. Il y a un effet super joli qui s'appelle parallax, qui fait que l'image reste fixe quand on scrolle la page. Dans le css du `header` on va ajouter:

```css
background-attachment: fixed;
background-position: center;
background-repeat: no-repeat;
```

Et maintenant ça rend super bien quand on scrolle!

## **Section expérience**

Nous allons créer une timeline et utiliser des effets pour que les éléments apparaissent quand on scrolle. Pour ça on va utiliser, en plus du HTML et du CSS, le langage Javascript.

**Structure HTML**

On va créer une nouvelle section dans laquelle on met un autre titre `h2` et on va mettre une liste "non ordonnée" c'est à dire sans numéros. C'est la balise `ul` pour `unordered list` qu'on utilise pour ce type de listes à puces.

```html
<section class="timeline">
  <h2>Expérience</h2>
  <ul>
    <li>
      <div class="bubble">
        <time>2019 - aujourd'hui</time>
        <span>Développeuse</span>
        <br />HiMama, Toronto
      </div>
    </li>
    <li>
      <div class="bubble">
        <time>2018 - 2019</time>
        <span>Développeuse</span>
        <br />Borrowell, Toronto
      </div>
    </li>
    <li>
      <div class="bubble">
        <time>2018</time>
        <span>Développeuse</span>
        <br />Je rêve d'une Maison, Paris
      </div>
    </li>
    <li>
      <div class="bubble">
        <time>2017</time>
        <span>Développeuse</span>
        <br />Econocom, Lyon
      </div>
    </li>
    <li>
      <div class="bubble">
        <time>2016</time>
        <span>Coordinatrice</span>
        <br />Social Builder, Paris
      </div>
    </li>
  </ul>
</section>
```

**À VOUS !**

1. Ajoutez le code ci-dessus dans le fichier `index.html`
2. Allez sur l'onglet de prévisualisation et actualisez votre page
3. Revenez dans `index.html` et ajoutez un élément à la liste (balise `li`) en changeant l'année dans la balise `time`

Si une liste à puces avec 5 éléments apparait en bas de votre page, dont le dernier avec l'année que vous venez d'ajouter, revenez dans Zoom et cliquez sur yes.

**Styles CSS**

C'est en ajoutant du CSS pour que notre timeline va vraiment prendre forme. Rappelez vous, si après l'atelier vous êtes curieuses vous pourrez cocher et décocher les styles dans l'inspecteur du navigateur et/ou rechercher sur google les règles qu'on utilise. 

Pour un joli effet, on va utiliser la fonction `rgba` qui permet de modifier la transparence d'une couleur et suit le format `rgba(rouge, vert, bleu, transparence`, la transparence étant un chiffre entre `0` et `1`

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
3. Changez la transparence de la couleur des bulles dans la parenthèse `rgba` correspondante

Si votre timeline est maintenant mise en forme, revenez dans Zoom et cliquez sur yes.

**Media queries**

Avec ce style ça rendra bien sur une page large mais pas sur les petits écrans qui n'auront pas la place.

Pour que nos styles puissent changer en fonction de la taille de l'écran, en CSS on utilise ce qu'on appelle des `media queries` qui nous permettent d'appliquer un style seulement sur certaines tailles d'écrans. 

On va ajouter une `media query` pour les écrans de moins de 900 pixels et une autre pour les écrans de moins de 600 pixels qui va passer la timeline d'un seul côté  :

```css
/* MEDIA QUERIES
–––––––––––––––––––––––––––––––––––––––––––––––––– */

@media screen and (max-width: 900px) {
  h1 {
    padding: 10px;
  }
  .about {
    width: 100%;
    padding: 0;
    margin: 70px auto;
  }
  .about p {
    padding: 0 15px;
  }

  .skills-content {
    width: 100%;
    padding: 15px 0;
  }

  .timeline .bubble {
    width: 250px;
  }
  .timeline ul li:nth-child(even) .bubble {
    left: -289px;
    /*250+45-6*/
  }
}

@media screen and (max-width: 600px) {
  h1 {
    font-size: 46px;
  }
  .progress-value,
  .progress-badge {
    font-size: 12px;
  }
  .timeline ul li {
    margin-left: 20px;
  }
  .timeline .bubble {
    width: calc(100vw - 91px);
  }
  .timeline ul li:nth-child(even) .bubble {
    left: 45px;
  }
  .timeline ul li:nth-child(even) .bubble::before {
    left: -15px;
    border-width: 8px 16px 8px 0;
    border-color: transparent rgba(18, 157, 175, 0.8) transparent transparent;
  }
}
```

Et pour que notre site détecte la taille de l'écran il faut ajouter une instruction méta dans la balise `head` de notre html

```html
<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
```

**À VOUS !**

1. Ajoutez le CSS ci-dessus à la fin du fichier `styles.css`
2. Dans la balise `head` de `index.html` ajouter la balise méta ci-dessus
3. Dans le menu `View` puis `Appearance` cliquez sur `Toggle preview` et redimensionnez la fenêtre pour qu'elle soit petite (vous pouvez cacher la prévisualisation après)

Si votre timeline est d'un seul côté sur un petit écran, revenez dans Zoom et cliquez sur yes.

**Effets CSS**

Pour animer cette timeline et qu'elle apparaisse dynamiquement on va utiliser une combinaison de CSS et de JavaScript. 

Le CSS permet de faire certaines animations mais c'est avec le JavaScript qu'on peut aller beaucoup plus loin et on va détecter quand notre élément est visible pour pouvoir déclencher l'animation CSS à ce moment là.

Les `media queries` doivent toujours rester à la fin de notre feuille de styles, donc on va ajouter le CSS pour les effets avant cette section. Ces règles CSS vont cacher nos bulles, et on précise que si elles ont une classe de `in-view` on les fait apparaitre avec une animation qui dure une demi seconde

```css
/* EFFECTS
–––––––––––––––––––––––––––––––––––––––––––––––––– */

.timeline ul li::after {
  transition: background 0.5s ease-in-out;
}

.timeline ul li.in-view::after {
  background: rgba(18, 157, 175, 1);
}

.timeline .bubble {
  visibility: hidden;
  opacity: 0;
  transition: all 0.5s ease-in-out;
}

.timeline ul li:nth-child(odd) .bubble {
  transform: translate3d(200px, 0, 0);
}

.timeline ul li:nth-child(even) .bubble {
  transform: translate3d(-200px, 0, 0);
}

.timeline ul li.in-view .bubble {
  transform: none;
  visibility: visible;
  opacity: 1;
}
```

**À VOUS !**

1. Dans `styles.css` insérez le CSS ci-dessus avant la section des `media queries`
2. Allez sur l'onglet de prévisualisation et actualisez votre page

Si vos bulles ont maintenant disparu, revenez dans Zoom et cliquez sur yes.

**Animation avec Javascript**

Un fichier appelé `scripts.js` existe dans votre projet. On va y ajouter trois fonctions Javascript.

La première s'appelle `isElementInViewport` et quand on lui passe une des bulles de notre timeline, elle va demander au navigateur sa taille et sa position dans la fenêtre avec la fonction `getBoundingClientRect` et va calculer si l'élément est dans la partie visible de notre navigateur.

La seconde fonction, `showElements` va faire une boucle et pour chaque bulle de la page vérifier si elle est visible en appelant notre fonction `isElementInViewport` et si la réponse est oui alors elle ajoute la classe `in-view` à cet élément.

La troisième partie va utiliser la fonction `onload` du navigateur qui se déclenche quand notre page a fini de charger pour activer notre animation. Elle récupère dans une variable une liste de toutes les bulles de notre timeline et appelle la méthode `showElements`. Elle va aussi activer notre animation dans le cas où la page est scrollée ou redimensionnée.

```jsx
// Fonction isElementInViewport
const isElementInViewport = element => {
  const rectangle = element.getBoundingClientRect();
  return (
    rectangle.top >= 0 &&
    rectangle.left >= 0 &&
    rectangle.bottom <=
      (window.innerHeight || document.documentElement.clientHeight) &&
    rectangle.right <=
      (window.innerWidth || document.documentElement.clientWidth)
  );
};

// Fonction showElements
const showElements = elements => {
  for (let i = 0; i < elements.length; i++) {
    if (isElementInViewport(elements[i])) {
      elements[i].classList.add("in-view");
    }
  }
};

// On appelle notre fonction pour qu'elle s'éxécute
window.onload = () => {
  const elements = document.querySelectorAll(".timeline ul li");
  showElements(elements);

  window.addEventListener("resize", () => showElements(elements));
  window.addEventListener("scroll", () => showElements(elements));
};
```

Enfin, pour dire au html qu'on veut utiliser le code qui est dans notre fichier `scripts` on doit ajouter un lien dans la balise `head`:

```html
<script src="./scripts.js"></script>
```

**À VOUS !**

1. Dans le fichier `scripts.js` insérez le code Javascript ci-dessus
2. Dans `index.html` ajoutez la balise `script` ci-dessus à l'intérieur de la balise `head`
3. Allez sur l'onglet de prévisualisation, remontez tout en haut et actualisez votre page

Si vos bulles apparaissent en scrollant, revenez dans Zoom et cliquez sur yes.

## **Formulaire de contact**

Pour que notre site soit vraiment utilisable il faut un moyen de nous contacter. Un formulaire permet aux gens de nous contacter sans avoir à divulguer notre adresse email.

Notre codesandbox et les dossiers qu'on va mettre sur Github sont publics. On ne veut pas mettre d'informations personnelles comme un numéro de téléphone ou un email, ou une addresse. On risquerait d'être inondée de spam parce qu'il existe de nombreux robots qui lisent toutes les pages web qui existent et piquent ces infos. 

**Carte Google**

Une carte Google rendra notre site très professionnel et indiquera aux visiteurs la ville où nous travaillons. 

On ne va pas mettre notre adresse exacte parce qu'on veut pas que le monde entier sache où on habite, on va plutôt mettre notre ville.

```html
<section class="contact">
  <h2>Contact</h2>
</section>
```

**À VOUS !**

1. Ajoutez la nouvelle section ci-dessus dans `index.html` avant la balise de fermeture du `body`
2. Allez sur [https://maps.google.com](https://maps.google.com) et tapez votre ville. Cliquez sur `Partager`

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Screen_Shot_2020-08-15_at_12.19.41_PM.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Screen_Shot_2020-08-15_at_12.19.41_PM.png)

3. Cliquez sur `Intégrer une carte`

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Screen_Shot_2020-08-15_at_12.20.17_PM.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Screen_Shot_2020-08-15_at_12.20.17_PM.png)

4. Cliquez sur `Copier le contenu HTML`

    ![%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Screen_Shot_2020-08-15_at_12.20.24_PM.png](%F0%9F%92%BB%20Premie%CC%80re%20page%20web%20e09001d7015642269c1eeb38c3a84f88/Screen_Shot_2020-08-15_at_12.20.24_PM.png)

5. Insérez le code HTML copié dans `index.html`  après la balise `h2`
6. Allez sur l'onglet de prévisualisation et actualisez votre page

Si une carte Google avec votre ville apparait au bas de la page, revenez dans Zoom et cliquez sur yes.

**Structure HTML**

Normalement pour avoir un formulaire de contact sur un site il faut qu'il soit dynamique, alors que le nôtre on a vu qu'il était statique, c'est à dire qu'il n'a pas de base de données et que tout le contenu est dans le code. 

Grâce à l'hébergeur web Netlify on va pouvoir héberger notre site gratuitement et avoir toute la logique derrière un formulaire de contact sans s'en préoccuper. 

Il faut simplement qu'on ajoute un attribut `data-netlify="true"` à notre formulaire et les robots de Netlify, une fois notre site mis en ligne, vont prendre le relais.

```html
  <form name="contact" method="POST" data-netlify="true">
    <div class="row">
      <div class="form-group">
        <label>Nom</label>
        <input type="text" name="name" placeholder="Votre nom" required />
      </div>
      <div class="form-group">
        <label>Email</label>
        <input
          type="email"
          name="email"
          placeholder="Votre email"
          required
        />
      </div>
    </div>
    <div class="form-group">
      <label>Message</label>
      <textarea
        name="message"
        placeholder="Votre message..."
        required
      ></textarea>
    </div>
    <button class="btn">Envoyer</button>
  </form>
```

**À VOUS !**

1. Insérez le formulaire HTML ci-dessus dans `index.html` après la balise `iframe` de la carte Google
2. Allez sur l'onglet de prévisualisation et actualisez votre page

Si un formulaire apparait au bas de la page, revenez dans Zoom et cliquez sur yes.

**Styles CSS**

```css
/* CONTACT
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.contact {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 70px auto;
  width: 60%;
}

iframe {
  margin-top: 30px;
  margin-bottom: 30px;
	width: 100%;
}

form {
  width: 100%;
}

.row {
  display: flex;
  flex-direction: row;
}

.form-group {
  margin-top: 10px;
  margin-bottom: 10px;
  border-bottom: 2px solid #d9d9d9;
  flex-grow: 1;
}

.form-group:first-of-type {
  margin-right: 30px;
}

label {
  font-size: 16px;
  color: #999999;
  padding: 5px;
}

input {
  width: 100%;
  color: #555555;
  border: none;
  height: 40px;
  padding: 5px;
  margin-top: 5px;
  font-size: 18px;
  font-family: Montserrat;
}

textarea {
  border: none;
  min-height: 110px;
  color: #555555;
  width: 100%;
  padding: 5px;
  margin-top: 10px;
  font-family: Montserrat;
  font-size: 18px;
}

::placeholder {
  font-family: Montserrat;
  font-size: 18px;
  font-weight: bold;
}

.btn {
  margin-top: 20px;
  padding: 0 20px;
  min-width: 130px;
  height: 50px;
  background-color: rgba(18, 157, 175, 1);
  border-radius: 5px;
  border: none;
  font-size: 16px;
  color: white;
}
```

**À VOUS !**

1. Insérez le code CSS ci-dessus dans `styles.css` avant les `media queries`
2. Allez sur l'onglet de prévisualisation et actualisez votre page

Si le formulaire a maintenant un design, revenez dans Zoom et cliquez sur yes.

**Styles pour petits écrans**

Sur mobile on a pas assez de place pour avoir le nom et l'email sur la même ligne. On va ajouter des règles CSS aux `media queries`. Dans la première pour les écrans de moins de 900px:

```css
.contact {
  margin: 30px;
  width: unset;
}
```

Et pour les écrans de moins de 600 pixels:

```css
form {
  display: flex;
  flex-direction: column;
}
.row {
  flex-direction: column;
}
.form-group:first-of-type {
  margin-right: 0;
}
```

**À VOUS !**

1. Insérez le code CSS ci-dessus dans `styles.css` dans la première `media query` pour les écrans de moins de 900px
2. Insérez le deuxième morceau de code CSS dans `styles.css` dans la seconde `media query` pour les écrans de moins de 600px
3. Allez sur l'onglet de prévisualisation et actualisez votre page

Si le formulaire a maintenant un design, revenez dans Zoom et cliquez sur yes.

Notre formulaire ne va pas fonctionner ici puisque c'est Netlify qui le fait fonctionner, il faudra déployer notre site d'abord (c'est super simple et gratuit. Je vais le faire de mon côté et vous avez le lien vers le tutoriel détaillé dans votre booklet Social Builder.

## **Mettre notre site en ligne**

Notre site est maintenant complet, nous allons pouvoir le mettre en ligne.

À nouveau ici tout est public, codesandbox, github et bien sûr le site déployé avec netlify sont visibles par tout le monde donc on mettra pas d'informations confidentielles ou personnelles.

**À VOUS !**

1. Suivez les instructions détaillées sur ce lien (le lien est aussi dans le booklet Horizon Numérique).

    **[Exporter et déployer son site](notion://www.notion.so/Premie%CC%80re%20page%20web%20442fbf381b1948c59df4ea693925bcfc/Exporter%20et%20de%CC%81ployer%20son%20site%2054b9b44b7e9f4540bb24e8d3ccd6e8c6.html)**

    [](https://github.com/sweetyclem/decouverte-code-final/blob/master/Exporter_et_deployer_son_site.pdf)

Quand votre site est déployé sur Netlify, revenez dans Zoom et cliquez sur yes.

## **Changer le contenu de la page**

**À VOUS !**

1. Suivez les instructions détaillées sur ce lien (le lien est aussi dans le booklet).

    **[Changer le contenu de la page](notion://www.notion.so/Premie%CC%80re%20page%20web%20442fbf381b1948c59df4ea693925bcfc/Changer%20le%20contenu%20de%20la%20page%20e1b3d389db4a4725a53ee47333754f1c.html)**

    [](https://github.com/sweetyclem/decouverte-code-final/blob/master/Changer_le_contenu_de_la_page.pdf)

Lorsque vous avez changé tout le contenu, revenez dans Zoom et cliquez sur yes.