# 1. Clona el repositorio
git clone https://github.com/tuusuario/tu-proyecto.git nombre-del-proyecto

cd nombre-del-proyecto
**1.1   descomprimir el archivo .rar y colocarlo a la raiz**

# 2. Copia el archivo de entorno y configura
cp .env.example .env
# 3. Instala las dependencias de Laravel
composer install

# 4. Genera la clave de aplicación
php artisan key:generate

# 5. Configura la base de datos en el archivo .env

# 6. Ejecuta las migraciones y seeders
php artisan migrate --seed

# 7. Instala dependencias de frontend (AdminLTE)
npm install && npm run dev

# 8. Levanta el servidor local
php artisan serve
