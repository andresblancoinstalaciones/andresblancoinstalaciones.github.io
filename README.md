# Publicar un  blog

1. Todo blog debe iniciar con la fecha actual y tener la terminación .md
2. Lo primero que hay que agregar es un encabezado como el siguiente:
```clojure
 {:title "Este es mi segundo mensaje"
  :layout :post 
  :date "2024-06-23"
  :author "Andrés Blanco"}
```
3. Luego escribo mi post.
4. Compilo ejecutando el siguiente comando en la terminal:
```
clj -M:build
```
5. Selecciono todos los archivos nuevos + y hago click en *Confirmar* o *commit* y luego en *sincronizar* o *sync*
Y ¡listo!
