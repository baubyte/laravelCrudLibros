## Simple CRUD Laravel con Crud Generator


### Creamos el Proyecto Laravel
    ./composer create-project laravel/laravel nombreproyecto

### Creamos una base de datos libros

### Corremos la migraciones
    ./artisan migrate

### Agregar Paquete Bootstrap
    ./composer require laravel/ui 

### Instalar Bootstrap
    ./artisan ui bootstrap --auth

### Ejecutar npm install
    ./npm install

### Ejecutar npm run dev
    ./npm run dev

### Instalamos Crud Generator
    ./composer require ibex/crud-generator --dev
#### https://github.com/awais-vteams/laravel-crud-generator

### Publicamos los paquetes y creamos el tag de Crud Generator
    ./artisan vendor:publish --tag=crud

### Creamos el CRUD para la tabla books
    ./artisan make:crud {nombre_tabla}