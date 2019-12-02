# PROYECTO GIT - JULIAN VILLANUEVA

## Parte individual.

1. ###  En la carpeta proyecto-git ‘iniciamos’ un repositorio git.

``` git init ```

![git init](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git init.JPG)

2. ###  Añadimos todos los ficheros al repositorio .

``` git add .```

![git add .](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git add ..JPG)



3. ###  Realizamos el primer commit.

```  git commit -m "Mensaje del commit"```

![git commit](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git commit.JPG)

4. ###  En la página index.html, cambia el título principal por el que desees, traduce el texto inferior y pon tu nombre como autor/a. 

```  git status```

![editamosIndexSublime](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\editamosIndexSublime.JPG)

![git status](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git status.JPG)

5. ###  Cambiar en las dos páginas los enlaces de la sección ‘nav’ para que enlacen las páginas correctamente. La página ‘elements’ no existe, dejar como destino “#”. Ver las diferencias de los ficheros.

```  git status```

![git status 2](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git status 2-1575275240747.JPG)

6. ###  Confirmamos los cambios

```  git add .```  

```  git commit -m "Mensaje del commit"```

![commit tras editar htmls](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\commit tras editar htmls.JPG)

7. ### Añadir un archivo ‘passwords.txt’ con un nombre de usuario y una contraseña. Ver el estado del repositorio.

```  nano passwords.txt```

![archivo passwords](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\archivo passwords.JPG)

![git status passwords](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git status passwords.JPG)

8. ###  Hacer que el fichero passwords.txt sea ignorado por el control de versiones. Ver el estado .

Para hacer que un fichero sea ignorado debemos de meterlo en el el archivo '.gitignore'.

```  nano .gitignore```

![creamos gitignore](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\creamos gitignore.JPG)

Veremos que al introducirlo en el '.gitignore' y añadir este con ```  git add .``` este será ignorado.

![git status ignore](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git status ignore.JPG)

![commit gitignore](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\commit gitignore.JPG)

9. ### Modifica el fichero ejemplo.html cambiando el título de la página. Confirma los cambios.

![git commit ejemplo titulo](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git commit ejemplo titulo.JPG)

10. ### Consulta las diferencias entre la versión actual y la anterior. 

```  git diff``` 

![git diff css](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git diff css.JPG)

11. ### En el fichero main.css, cambia el color de la letra de los h1 por ‘green’. Comprueba el estado del repositorio. Realiza una pequeña captura de pantalla donde se vea el cambio. Acepta los cambios, pero no hagas ‘commit’. Muestra el estado del repositorio.  

Tras modificar el archivo añadiendo el color a los elementos 'h1' realizamos un ```  git add .``` para añadir los cambios

![git add css](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git add css.JPG)

Se nos solicita que nos volvamos atrás en el fichero css.

Para ello hacemos un ```  git log``` para ver los 'commits' anteriores.

![git log](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git log.JPG)

Utilizamos ```  git restore``` para volvernos atrás en ese archivo especifico.

![git restore](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git restore.JPG)

12. ### Mostramos el log final

    ![git log final](C:\Users\diurno\Desktop\GIT-JulianVillanueva.assets\git log final.JPG)

    
## PARTE COLABORATIVA. (Protpietario)
    

    