# predict_genome_disorders
¡¡IMPORTANTE!! LEER ANTES DE ACTUAR  
Este repositorio contiene todos los archivos necesarios para el funcionamiento correcto del trabajo, escrito en forma de informe utilizando RMarkdown.
Antes de nada, decir que el documento utilizado para exponer en clase ha sido *html_genetic_disorders.Rmd*, con su respectiva salida en html, pero como  
en GitHub no carga bien el html con todas las florituras que hemos puesto, he generado otro documento llamado *github_genetic_disorders.Rmd*, que genera un  
archivo en formato markdown llamado *github_genetic_disorders.md*.  

La diferencia entre ellos radica en que el documento Rmd que da salida para github, no tiene ciertos elementos en el encabezado, como *toc_float*, ni *theme*, ni *smooth_scroll*, lo que hace que no tenga índice floante y que la pagina se genere sin estilo.  
Además, también le faltan las etiquetas HTML que le ponen el fondo y el color de la letra a la salida en HTML del documento *html_genetic_disorders.Rmd*.  

Otros elementos que se han tenido que quitar por dar error son:
+ Las etiquetas {.tabset .tabset_pills}, que se encargaban de genererar los desplegables en los distintos apartados.  
+ Todas las funciones relacionadas con el paquete **kableExtra**, que se encargaba de dar más personalización a las tablas.  

Además, el archivo *github_genetic_disorders.Rmd* genera en su salida una carpeta con las gráficas guardadas en forma de imágenes, ya que al no poder generarlas a partir del archivo *github_genetic_disorders.md*, necesitan poder cargarlas de alguna forma. Como github no me ha dejado subir la carpeta, hemos tenido que subir las imágenes sueltas, y cambiar la ruta de las imágenes en el archivo *github_genetic_disorders.Rmd* para que se cargasen correctamente.

Respecto a otros documentos:  
**LICENSE** Presenta la licencia que más se parece a la puesta en el repositorio desde el que nos descargamos los datos.  
**README.md** Explica el correcto uso y finalidad de los documentos presentes en el repositorio.  
La carpeta **images** contiene las imágenes utilizadas en la parte del uso del terminal.  
Las imágenes **Grafico3-1.png, Grafico_densidad-1.png y disease-1.png** son las imagenes de las gráficas generadas.  
**descripcion_columnas.pdf** contiene la descripción de las variables de las tablas de datos.  
**github_genetic_disorders.Rmd** es el documento Rmd que genera el documento de salida **github_genetic_disorders.md**.  
**html_genetic_disorders.Rmd** es el documento Rmd que genera el documento de salida **html_genetic_disorders.html**  
**libraries.bib** es el archivo que contiene la información para referenciar los paquetes de R utilizados. Este documento fue generado desde la consola de R con la entrada *knitr::write_bib(c(.packages(), 'dplyr', 'ggplot2', 'knitr', 'kableExtra'), 'libraries.bib')*  
**test_genetic_disorders.csv** y **train_genetic_disorders.csv** son las tablas de datos descargadas desde el repositorio correspondiente. Para este trabajo, se utilizó únicamente **train_genetic_disorders.csv**, al ser algo más completa que la otra.

De todos estos archivos, los únicos no esenciales para el correcto funcionamiento del trabajo son:
**test_genetic_disorders.csv** y **descripcion_columnas.pdf**.
El resto de componentes deberán estar organizados como en este repositorio, para evitar fallos de funcionamiento, como, por ejemplo, que una imagen no cargue porque la ruta de carga no coincida con la ruta asignada.
