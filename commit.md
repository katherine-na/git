<h1 align="center"> Mensaje en un git commit</h1>

<p align="center">
Es un texto corto que se escribe cuando se guardan los cambios de un trabajo en Git.
</p>

## Un buen ejemplo de commit

![](https://www.freecodecamp.org/news/content/images/2020/07/git-commits-history.png)


## Cuál es su objetivo?
Este mensaje tiene como objetivo identificar tu trabajo y ayudar a otras personas a que cuando lo lean puedan entender claramente lo que hiciste en esta parte de tu trabajo.  
Es esencial escribir bien tu commit para tener:

- Mejor colaboración
- Mejor entendimiento

### Buenas prácticas para escribir commits en Git

Estructura:
```
tipo del cambio [scope]: descripcion de los cambios
```

Por ejemplo:
```
feat: add new search feature
^--^  ^--------------------^
│     │
│     └--> # Descripción de los cambios
│
└──------> # Tipo del cambio
```

Puedes añadir también la información del paquete que es afectado por el commit. Se le conoce como [scope] y sería de la siguiente forma:

```
feat(backend): add filter for cars
fix(web): remove wrong color
```
### Tipo de cambio 

- docs: Cambios en la documentación.
- style: Cambios de formato, tabulaciones, espacios o puntos y coma, etc; no afectan al usuario.
- feat: Una nueva característica para el usuario.
- fix: Corrige un error en la base del código.
- perf: Cambios que mejoran el rendimiento del sitio.
- build: Cambios en el sistema de build, tareas de despliegue o instalación.
- ci: Cambios en la integración continua.
- refactor: Refactorización del código como cambios de nombre de variables o funciones.
- test: Añade tests o refactoriza uno existente.


### Ejemplos

```bsh
docs(web): change the information

Change the information of article 30
```

```bsh
style(web): add punctuation marks 

Add punctuation marks on the line 31
```

```bsh
feat(backend): add filter for cars
```

```bsh
fix(web): remove wrong color
```

```bsh
perf(web):
```

```
build(): update 
```

```bsh
ci(docs):
```

```
refactor():
```

```
test():
```
