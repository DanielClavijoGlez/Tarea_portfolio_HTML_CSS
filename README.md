# Portfolio Ping Xiao Po

## Curso Web HTML + CSS

### Aspectos a tener en cuenta para la corrección

1. Para hacerla responsiva se han usado 'clamp()' para el tamaño de las fuentes, 'min()' para el tamaño de los contenedores y 'max()' para los padding y los márgenes.

2. Para posicionar la mayoría de las cosas se ha usado 'flexbox'. Pero también se ha usado 'grid' limitando el número máximo de columnas, esto en el contenedor de las barras de habilidades y en el contenedor de los 4 primeros campos del formulario (nombre...usuario GitHub). Aparte se hace uso de 'position: absolute' para colocar el menú desplegable, las líneas que aparecen debajo de los links del header al hacer hover y el texto de la imagen del banner.

3. Se ha hecho con un enfoque mobile first y gracias en gran parte a lo comentado en los 2 puntos anteriores la página es casi totalmente responsiva sin media queries. Las media queries implementadas son sobre todo para distinguir entre dispositivos que pueden hacer hover y los que no, con '@media (hover: hover)' y para el "layout" solo se ha necesitado modificar el menú desplegable para que se oculte y se vean directamente los links en pantallas más grandes.

4. Para seguir el CSS más fácilmente se ha dejado al principio del archivo un índice, el cual te ayuda si seleccionas una de las líneas con el ratón y la buscas (ctrl + f), pues cada una coincide con el comentario dejado antes de cada "sección".
