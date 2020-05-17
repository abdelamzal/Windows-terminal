# Windows-terminal

1. Installer Git-bash
2. Installer SSH
3. Installer Windows terminal

My settings for Windows terminal and ssh key connection 
date : 05/2020


## Editer le fichier git-prompt.sh
> Pour commencer il faut se rendre dans le dossier d’installation de l’outil git: C:\Program Files\Git\etc\profile.d\
Vous y trouverez le script git-prompt.sh, qui définit justement le format d’affichage du prompt.

> Attention: Vous devez être administrateur pour modifier le contenu de ce dossier.

> Je vous conseille ici de faire une copie de ce script par sécurité. Par exemple git-prompt-copie.sh.


## Code Couleur
> Comme vous l’avez vu dans le prompt, il est possible de changer les couleurs du texte. Pour cela il faut utiliser la balise ‘\[033[<color_code>m\]’ comme par exemple:

    PS1=”$PS1″‘\[\033[32m\]’ # change to green

|     Code      |       Color     |
| ------------- |: -------------: |
|      30       |        Black    |
|      31       |        Red      |
|      32       |        Green    |
|      33       |        Yellow   |
|      34       |        Blue     |
|      35       |        Magenta  |
|      36       |        Cyan     |
|      37       |        White    |
|      0        |        Black    |


## Variables
> Il est également possible d’utiliser certaines variables pour enrichir le prompt comme par exemple: 

    PS1=”$PS1″‘\w’ # current working directory

|    Variable   |       Contenu            |
| ------------- |: ----------------------: |
|      \n       |      saut de ligne       |
|      \w       |      dossier courant     |
|      \u       |      nom d’utilisateur   |
|      \h       |      nom de la machine   |

	
	
	
