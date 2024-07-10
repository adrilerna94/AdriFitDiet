# AdriFitDiet

# Introducción
- Este proyecto consiste en una aplicación web frontend y backend para la confección de planes nutricionales en base a unos perfiles individualizados.

# Requerimientos
- Estos perfiles, confeccionados por el usuario, tendrán un nombre, unos macronutrientes (carbohidratos, grasas, proteínas, calorías), una Kcal totales, una cantidad de comidas asociadas y un nombre para cada comida.
- En base a los perfiles específicos confeccionados por el usuario, se generará un menú diario que contendrá:
  - Unos macronutrientes objetivo/dia en la cabezera de la página asociado a un contador que irá restando los macronutrientes y kcal objetivo a los macros y kcal que iremos añadiendo con cada comida que agreguemos al menú.
  -  Un listado de comidas con sus alimentos asociados por comida.
  -  Un botón de edición por comida. Éstas podrán copiarse, moverse o eliminarse.
  -  Un contador de macronutrientes y kcal por comida dentro de cada comida.
  -  Un botón de Añadir Alimento dentro de cada comida
  -  Un botón que permita navegar hacia el listado de alimentos de nuestra base de datos junto con la barra de navegación que permita filtrar los resultados.
  -  En esa página que podamos crear un alimento nuevo en el caso de que no exista el alimento que queramos en nuestra base de datos.
  -  Menú hamburguesa(mobile)/Sidebar (desktop) que disponga de :
    - Breve Snapshot en la cabecera del perfil que hemos seleccionado con:
        - Avatar
        - Nombre Perfil
        - Total Kcal
        - Macronutrientes
    - Perfiles
    - Mis Alimentos : con nuestro listado de alimentos y un botón para añadir un alimento nuevo
    - Cerrar Sesión: que nos permite desloggearnos
  - Login: con su autorizacion y autenticación. Idealmente conectado a nuestra cuenta de google para hacer el registro más rápido.
  - Logo Admin para gestionar la cuenta: nombre usuario, contraseña.

# Objetivos
- Backend
  - Base de datos con un listado de alimentos a seleccionar
  - Creacion de API rest con el CRUD
  - Relaciones entre entidades
  - Authentication y Authorization
- Frontend
  - Filtrar los resultados del listado
  - CRUD Alimentos
  - CRUD Perfiles
  - Login/Logout
  - Register
