# lesfilles
lesfilles


composer create-project laravel/laravel example-app
composer require laravel/breeze --dev

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

Aller dans le fichier tailwind.config.js et remplacer le tableau vide ‘’content’’ par 

content: [
    "./resources/**/*.blade.php",
    "./resources/**/*.js",
    "./resources/**/*.vue",
  ],

Ouvrir un terminal pour php :
Y mettre : composer Install
Y mettre :php artisan serve

Ouvrir	 un terminal pour tailwind et les assets js:
Npm Install puis nom run dev
