<h1> Pautas de Diseño Atom Design </h1>

src/
|- Atoms/
| |- Button.js
| |- Input.js
| |- ...
|
|- Molecules/
| |- CardPost.js --> imagen && descripcion && botones me gusta y comentar
| |- ListaAmigos.js --> popup que muestra la lista de amigos
| |- InputComentario.js --> input && button que seguro se reutilizara en muchos lugares.
|
|- Organisms/
| |- Footer.js
| |- States.js
| |- Navbar.js --> logica --> logo && links
| |- PerfilDeUsuario.js --> foto , nombre, biografia, seguidores y publicaciones
| |- Explorer.js -->
| |- ...
|
|- Templates/ --> Donde ordenamos lo que vamos a acomodar en Pages (No lleva logica aqui a no ser simples)
| |- LayoutPrincipal.js --> Navbar
| |- BarraLateralDerecha.js --> Perfil && sugerencias && Footer
| |- LayoutPerfil.js --> encabezado de perfil && content && footer
| |- ...
|
|- Pages/ --> Solo vistas --> Serain los routes
|- Inicio.js
|- Perfil.js
|- Explore.js
|- Accounts.js

Atomos: contiene componentes átomos reutilizables, como botones, inputs, iconos, etc.

Moleculas: contiene componentes moléculas más complejos, como "CardPost.js" (imagen, descripción, botones Me gusta y Comentar), "FriendsList.js" (lista de amigos en un popup), "CommentInput.js" (campo de entrada de comentario), etc.

Organismos: contiene componentes organismos que involucran lógica más compleja, como "Navbar.js" (logica: logo, enlaces), "Footer.js", "ProfileHeader.js" (foto, nombre, biografía, seguidores, publicaciones), "Explorer.js", etc.

Templates: contiene componentes plantillas que definen la estructura general de cada sección de la aplicación, como "MainLayout.js" (Navbar, contenido y Footer), "ProfileLayout.js" (Encabezado de perfil, contenido y Footer), "ExploreLayout.js" (Encabezado de exploración, contenido y Footer), etc.

Pages: contiene las vistas de la aplicación, como "Home.js", "Profile.js", "Explore.js", "Accounts.js", etc.

- son las vistas que exportaremos para mostrar en App.js
