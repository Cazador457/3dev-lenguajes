# Practica 8
### Angel Bernardino Melquiades

## A.- ¿Cómo se inicializa un repositorio en Git?
Estando en terminal desde la carpeta que se usara para el repositorio se escribe:
```bash
git init
```

## B.- ¿Cómo creas un repositorio en GitHub?
Entramos a nuestra cuenta de GitHub, le damos en la opcion de crear nuevo repositorio y lo configuramos:
- Nombre sel repositorio
- Si sera publica o privada

En caso de no tenerlo agregar:
- README.md
- .gitignore
- Licencia

## C.- ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
Al tener la carpea del repositorio local solo son tres pasos:
```bash
git remote add origin https://github.com/Cazador457/3dev-lenguajes.git
git branch -M main
gigt push -u origin main
```

## D.- ¿Cuál es el flujo básico de trabajo en Git y GitHub?
Consta de 3 comandos diferentes:
```bash
git add .
git commit -m "Nota o nombre"
git push
```

## E.- ¿Para qué sirve el archivo .gitignore?
Permite selecionar el archivo o tipos de archivo que no queremos que se suban alrepositorio escribiendo sus nombres en el archivo:
```bash
pixel-art.jpg
.png
```

## F.- ¿Cuál es el propósito de una rama?
Es podermitir hacer cambios en los archivos del repositorio sin afectar directamente los archivos fuente.
```bash
pixel-art.jpg
.png
```

## G.- ¿Qué es una fusión?
Es la forma de combinar los cambios realizados en las ramas, ya sea entre ellas o con la rama principal.

## H.- Explica los diferentes tipos de fusión que existen
Hay dos tipos:
1. **Fast-Forward**:
    - Permite combinar los archivos cuando no hay problas de incompatibilidad.
1. **Manual Merge**:
    - Se hace una fusion archivo por archivo cuando se detecta una incompatibilidad.

## I.- ¿Cómo puedes ver el historial de tu repositorio?
Con dos comandos:
1. El primero muestra la informacion relevante de cada commit:
```bash
git log
```
2. El segundo muestra solo los nombres de los commits:
```bash
git log --oneline
```

## J.- ¿Cuál es el propósito de una etiqueta?
Ayudan a diferenciar las versiones del repositorio asi como su inpacto en el proyecto.