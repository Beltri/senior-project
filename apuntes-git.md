#Apuntes de Git

Los tres estados:


###1. Modified - 2. Staged - 3. Commited ###

Las secciones principales de un proyecto GIT:

1. **Working directory**
	Aqui modificas los archivos ( Modified )

2. **Staging area**
	Aqui añades los archivos preparados ( Staged )

3. **Git Directory**
	Al comfirmar los cambios ( Commited ), toma los archivos que están en el Staging area y los almacena de manera permanente en el direcorio GIT.


Referencia: https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git


##Instalar GIT
https://git-scm.com/book/es/v1/Empezando-Instalando-Git

##Estudiar npm


## Creació nou repositori

Per crear un nou repositori ho faig desde Cmder.
Vaig a la carpeta a on vull fer el repositori amb el comando "cd"

(recorda que amb el tab puc anar completant la ruta, i a més puc posar cd + s per que em trobi la carpeta que comença amb S, com la de senior-project per que em mostri la ruta)

un cop estic a la ruta. Creo el repositori posant git init.
i ma em mostra que estic a la branca master

C:\Users\gemma.beltra\repositorio-git\senior-project
λ git init
Initialized empty Git repository in C:/Users/gemma.beltra/repositorio-git/senior-project/.git/
C:\Users\gemma.beltra\repositorio-git\senior-project [master]



##Xuletes
Utilitzo Cmder com a linea de comandos per treballar amb GIT
També podria utilitzar GITBash

git config --list ( per saber quina és la teva configuració )
git config --global user.name "gemma.beltra" ( he afegit el nom a user name )
git config --global user.email "gemma.beltra@softonic.com" ( he afegit el mail a user.mail )

Si vull obtenir ajuda puc escriure
git help
si vull ser més concret puc fer

git help --loquesea

referencia: https://git-scm.com/book/es/v1/Empezando-Obteniendo-ayuda
