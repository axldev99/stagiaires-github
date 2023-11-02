# stagiaires-github

Ceci est un exercice pour nos stagiaires afin d'évaluer leurs capacités à utiliser GitHub.

Nous ferons ici, une simple page HTML sur les singes.


# 1 Commencez par cloner ce directory 

git clone https://github.com/axldev99/stagiaires-github.git


# 2 Créez un fichier HTML nommé : index.html

Le titre de la page doit être "Le singe",

Ajoutez ceci au body : 

<h1>Le singe</h1>
<p>Le terme viendrait du latin impérial singeosorus, plutôt que du latin classique singeosaure</p>


# 3 Faites votre premier commit

<details>
  <summary>Example</summary>

  ```
  git add index.html
  git commit -m "Création de la page HTML de base"
  ```
</details>


# 4 Poussez votre code sur la branche main 

<details>
  <summary>Example</summary>

  ```
  git push origin main
  ```
</details>


# 5 Créez une nouvelle branche : Demo

<details>
  <summary>Example</summary>

  ```
  git checkout -b demo
  ```
</details>


# 6 Modifiez le code de index.html

Changez le titre de la page pour "Le super singe".
Remplacez la ligne du paragraphe par ceci : <p>Le VRAI terme viendrait du latin impérial simius, plutôt que du latin classique simia.</p>


# 7 Faites un commit de vos modifications

<details>
  <summary>Example</summary>

  ```
  git add index.html
  git commit -m "Modification de la description dans la branche demo"
  ```
</details>


# 8 Faites un push de vos changements 

<details>
  <summary>Example</summary>

  ```
  git push origin demo
  ```
</details>


# 9 Revenez sur main et faites une pull request

<details>
  <summary>Example</summary>

  ```
  git checkout main
  git merge demo
  ```
</details>


# 10 Résolvez les conflits s'il y en a, utilisez votre logique !

Un coup les conflits résolus, poussez vos changements.

<details>
  <summary>Example</summary>

  ```
  git add index.html
  git commit -m "Résolution du conflit de fusion"
  ```
</details>


# 11 Clôturez la pull request 

<details>
  <summary>Example</summary>

  ```
  git push origin main
  ```
</details>


# BRAVO! Vous êtes passez à travers!


