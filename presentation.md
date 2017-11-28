% Présentation Markdown
% Guimoz
% 27 Octobre 2017

# Markdown

Un langage simple pour des notes efficaces

#Pourquoi Markdown ?

- Simple
- Rapide
- Pas d'apprentissage

# Exemples

#Texte

```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
```

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__


#Texte v2

```
~~tilde~~
retour à ligne : une ligne vide
```

~~tilde~~

# Titres

```
# Titre
## Sous-titre
###Sous-sous-titre
```

<small>`#Titre` crée une nouvelle slide en mode présentation</small>

#Citation

```
> Citation
>
>> Citation2
````

> Citation
>
>> Citation2

#Inclusion de Code

```
`one_line=True`
```

````
```python
def multiple_lignes():
    pass
```
````

`one_line=True`

```python
def multiple_lines():
    pass
```


#Liste Ordonnée

```
1. Premier élément
2. Second élément
```

1. Premier élément
2. Second élément


# Liste non-ordonnée

```
- Élément
* autre
+ plop
```

- Élément
* autre
+ plop

# Images

```
Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
```

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

# Liens

```
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")
```

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

# Tableaux

```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

# Maths

```
$\LaTeX \heartsuit \frac{5}{2}$
```

$\LaTeX \heartsuit \frac{5}{2}$

# Convertir avec Pandoc

##

On peut générer plusieurs types de fichiers à partir d'un document markdown

[Source markdown](/markdown/presentation.md)

## Un pdf

```pandoc```

[Exemple pdf](/markdown/presentation.pdf)

## Un html

```pandoc```

[Exemple html](/markdown/presentation.html)

## Une présentation reveal.js

```pandoc```

[Exemple présentation](/markdown.html)

# Plus d'infos

[https://daringfireball.net/projects/markdown/](https://daringfireball.net/projects/markdown/)

[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
