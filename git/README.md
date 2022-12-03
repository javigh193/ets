# Apuntes sobre GIT

## Instalación de git y configuración

    git --version
    
Crea un archivo en ~/.gitconfig:
  
    git config --global user.name "Sergio Delgado Quintero"

    git config --global user.email "sdelquin@gmail.com"
  
  [user]
  
   name = Sergio Delgado Quintero
    
   email = sdelquin@gmail.com
    
Rama principal por defecto:

    git config --global init.defaultBranch main 
    
Añade a ~/.gitconfig:

    [init]
     defaultBranch = main
      
## Inicializar un repositorio

    git init
   
      Initialized empty Git repository in /Users/sdelquin/work/.git/
      
## Clonar un repositorio
 
Vía ssh:

    git clone git@github.com:sdelquin/work.git
  
Vía httpshttps:

    git clone https://github.com/sdelquin/work.git

## Flujo de trabajo




