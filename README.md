# Proyecto 12: Alrededor de los Estados Unidos

Este proyecto es una aplicación web construida con React que permite a los usuarios explorar perfiles de usuario y lugares de interés en los Estados Unidos. La aplicación incluye funcionalidades como la edición del perfil de usuario, la adición de nuevos lugares y la interacción con tarjetas de lugares a través de peticiones al servidor.

## Características

- **Edición de perfil de usuario:** Permite a los usuarios editar su perfil con facilidad. Los cambios se actualizan tanto en la interfaz de usuario como en el servidor.

- **Visualización de lugares de interés:** Presenta lugares de interés con títulos e imágenes atractivas. Al hacer clic en una tarjeta, se puede ver una descripción más detallada.

- **Agregar nuevos lugares:** Los usuarios pueden agregar nuevos lugares de interés mediante un formulario interactivo. Los datos se envían al servidor para su almacenamiento.

- **Interacción con tarjetas:** Los usuarios pueden dar "like" a las tarjetas de lugares, y se muestra un contador de likes. También se pueden eliminar tarjetas, y estos cambios se reflejan tanto en la interfaz de usuario como en el servidor.

- **Diseño Responsivo:** La página es responsiva y se adapta a diferentes tamaños de pantalla, con soporte para anchos de ventana de 320px a 1280px.

## Tecnologías utilizadas

- **React:** La biblioteca principal utilizada para construir la interfaz de usuario.

- **CSS:** Utilizado para el diseño y la presentación visual.

- **JavaScript:** La lógica del proyecto se implementa utilizando clases de JavaScript, diseñadas con un enfoque en el acoplamiento débil. Se realizan peticiones al servidor utilizando fetch para la actualización y obtención de datos.

- **Webpack:** Se utiliza para empaquetar, transpilar y optimizar el código.

- **API y Servidor:** Se realiza comunicación con un servidor que maneja las operaciones CRUD (Crear, Leer, Actualizar, Eliminar) mediante peticiones HTTP.

## Uso

- **Editar el perfil de usuario:** Al hacer clic en el botón "Editar", se abre un popup que permite editar el perfil del usuario. Al guardar los cambios, se actualiza la información del usuario tanto en la página como en el servidor.

- **Agregar nuevos lugares de interés:** Al hacer clic en el botón "Agregar", se abre un formulario para agregar un nuevo lugar de interés. Los usuarios pueden proporcionar un título y una imagen. Al hacer clic en el botón "Guardar", se crea una nueva tarjeta de lugar de interés y se envían los datos al servidor.

- **Interactuar con tarjetas:** Al hacer clic en una tarjeta de lugar de interés, se abre un popup con una imagen y una descripción más detallada del lugar. Los usuarios pueden dar "like" a las tarjetas y eliminarlas, y estos cambios se reflejan en tiempo real tanto en la interfaz como en el servidor.

- **Cerrar popups:** Los popups se pueden cerrar haciendo clic en el botón "Cerrar" o haciendo clic en el área sombreada alrededor del formulario.

- **Visualizar información detallada:** Al hacer clic en una tarjeta de lugar de interés, se abre un popup con una imagen y una descripción más detallada del lugar.

## Visita

Puedes ver la página en funcionamiento aquí  [➡️](https://danva16.github.io/web_project_around_react/)
