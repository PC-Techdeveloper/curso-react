# curso-react

React es una biblioteca de JavaScript de código abierto diseñada para crear interfaces de usuario con el objetivo de facilitar el desarrollo de aplicaciones en una sola página.

# Tipos de Exportación

-- POR DEFECTO: Único componente o elemento que se va a importar en un archivo.

export default nombre-del-componente;

-- NOMBRADA: Exportar varios elementos de un mismo archivo (especificar cual de los elementos se importará).

export function componente(){
return(
...
);
}

# Recibir props en un componente

Las `props` son la colección de datos que un componente recibe del contenedor padre, y que pueden usarse para definir los elementos de React que retornará el componente. En términos prácticos, si un componente necesita recibir información para funcionar, la recibe vía props.

# Pasar props a un componente

Para pasar props, se agregan al archivo JSX, de la misma forma en el que se hace con los atributos HML. Para acceder a las props se utiliza la sintaxis de destructuración.
