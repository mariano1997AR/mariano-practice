## Configuraciones de git

* git config --local user.name "Tu nombre aqui"
* git config --local user.email "Tu@email.aqui"

### Git estado
* git status

### Guardar cambios
* git add "archivo" o . para total archivos
* git commit -m "cualquier mensaje"

### git status
* HEAD: Estado actual de nuestro codigo, es decir, donde nos coloco git
* Working tree: Lugar donde los archivos realmente estan siendo almacenados.
* index: Lugar donde git almacena lo que sera commiteado, es decir, la ubicacion entre el working tree y el repositorio git en si

### git log
Es el historial de git para saber los commit que realizamos
<br>
Si queremos ver solo los commit
  
* git log --oneline

Si queremos ver todo el archivo del commit
<br>

* git log -p
## Configuraciones locales en git
* git config --local user.name "tu nombre"
* git config --local user.email "Tu email aqui"
