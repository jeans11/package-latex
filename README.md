# package-latex (en cours de documentation)

Il s'agit d'un paquet Latex qui simplifie la déclaration des autres paquets. Il définit également des commandes

## Installation
---

- Créez un dossier "tex" à la racine de votre home
  
  
  mkdir -p ~/texmf/tex/
  
- Placez les deux fichiers à la racine de ce répertoire

- Pour inclure le paquet

  
  \usepackage{MonPaquet}
  

## Les langages
---

- Langages supportés (basé sur le package listings)

Langage    | Label
-----------|------
Java       | java
Javascript | JS
HTML       | html
CSS        | css
PHP        | php
Python     | python
Json       | json
XML        | xml
SQL        | sql

- Citer du code

```Latex
  \begin{label du langage}[Entrez ici la légende]
    \\ Votre code
  \end{label du langage}
```

## Autres commandes
---

- Ajouter une image

```Latex
\begin{img}
  \includegraphics{path/image}
  \caption{Votre légende}
\end{img}
```
