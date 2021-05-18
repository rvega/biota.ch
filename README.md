# Biota.ch

Este es el código fuente de la página web http://biota.ch. Hecho con [Jekyll](https://jekyllrb.com) y [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes/tree/4.23.0). 

Alojado en [github pages](https://github.com/rvega/biota.ch/).


## Cómo cambiar archivos de la plantilla.

1. Haga una copia en su computador de el código de la plantilla minimal-mistakes. 
   ```
   git clone git@github.com:mmistakes/minimal-mistakes.git
   cd minimal-mistakes 
   git checkout 4.23.0
   ```

2. Copie el archivo que quiere cambiar de uno de los subdirectorios de minimal-mistakes al mismo subdirectorio en este repositorio. Esto aplica para estos subdirectorios:   
    ```
   /assets
   /_layouts
   /_includes
   /_sass
   ```
   Ejemplo: 
   ```
   mkdir repo/_includes
   cp minimal-mistakes/_includes/footer.html repo/_includes
   vim repo/_includes/footer.html
   ```

## Cómo pre-visualizar la página web en un computador local.

1. Instalar ruby 2.7.1. La forma mas fácil es usar [RVM](https://rvm.io/). `rvm install 2.7.1`

2. Instalar jekyll y bundler: `gem install bundler && cd este/repo && bundler`

3. Correr un servidor web local: `cd este/repo && jekyll serve`


