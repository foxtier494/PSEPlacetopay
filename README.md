# PSEPlacetopay
Laravel 5.5 PSE Placetopay
Ejecicio de prueba para la aplicacion de PSE Placetopay Laravel 5.5

La aplicación esta hecha en PHP Laravel 5.5
El formulario tiene validación de frontend y backend  
Los pagos son registrados en la base de datos: placetopays
La lista de banco se guarda en el cache por 24 horas
Los datos de la configuración de base datos en .env: DB_DATABASE=quota DB_USERNAME=root DB_PASSWORD=''
Ya configurado .env debe de ejecutar: 

php artisan migrate 
    y luego 
php artisan db:seed

En screenshot va a poder apreciar el proceso para utilizar la aplicación
