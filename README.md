# playlist
tus mejores canciones


git remote -v

//git remote rename actual_name nuevo_name
git remote rename origin fork

// Agregamos el remoto del propietario del proyecto
git remote add origin https://github.com/zefetorres/playlist.git

// creamos nueva Rama antes hacer cambios y nos movemos a la nueva rama
git checkout -b bugfix

//Modificamos el codigo o hacemos cambios

//Agragamos los cambios y acemos commit
git add .
git commit -m "fix code to solve problem"

::: Solicitar incluir el cambio en el repositorio Original :::
git remote -v

//git push RemotoAlQueVamosEnviarCambios RamaDelRemotoQueRecibe
git push fork bugfix