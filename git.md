# Introducción a Git

## 1. ¿Qué es un repositorio en Git?
Un repositorio en Git es básicamente una carpeta del proyecto donde Git guarda los archivos
y también el historial de todos los cambios que se van haciendo con el tiempo.

---

## 2. ¿Cuáles son las áreas principales de Git?
Git trabaja con tres áreas:
- El working directory, que es donde editamos los archivos.
- El staging area, donde se seleccionan los cambios que se van a guardar.
- El repository, que es donde Git guarda definitivamente los cambios mediante commits.

---

## 3. ¿Cómo representa Git los cambios internamente?
Git guarda la información usando diferentes tipos de objetos. Algunos guardan el contenido
de los archivos, otros la estructura de carpetas y otros los cambios realizados en el proyecto.

---

## 4. ¿Cómo se crea un commit y qué información guarda?
Un commit se crea cuando confirmamos los cambios con un mensaje. Este guarda qué se cambió,
quién hizo el cambio, cuándo se hizo y una referencia al estado anterior del proyecto.

---

## 5. ¿Cuál es la diferencia entre git pull y git fetch?
git fetch solo descarga los cambios del repositorio remoto, pero no los aplica.
git pull descarga los cambios y los integra directamente en el proyecto.

---

## 6. ¿Qué es un branch en Git?
Un branch es una rama que permite trabajar en una parte del proyecto sin afectar la versión
principal. Git usa referencias para saber en qué punto del proyecto está cada rama.

---

## 7. ¿Cómo se realiza un merge y qué problemas pueden surgir?
Un merge sirve para unir los cambios de una rama con otra. A veces pueden aparecer conflictos
cuando dos cambios afectan la misma parte del archivo. Estos se resuelven revisando y
eligiendo qué cambios conservar.

---

## 8. ¿Cómo funciona el área de staging?
El área de staging sirve para indicar qué cambios queremos guardar en el próximo commit.
Si no se usa git add, Git no incluirá esos cambios.

---

## 9. ¿Qué es el archivo .gitignore?
El archivo .gitignor` le dice a Git qué archivos no debe tener en cuenta, como archivos
temporales o configuraciones personales que no es necesario subir al repositorio.

---

## 10. ¿Cuál es la diferencia entre un commit amend y un nuevo commit?
Un commit con --amend permite corregir el último commit, por ejemplo cambiar el mensaje o
agregar un archivo olvidado. Un nuevo commit crea un registro adicional en el historial.

---

## 11. ¿Cómo se usa git stash y para qué sirve?
git stash se usa para guardar cambios de forma temporal cuando no se quiere hacer un commit,
por ejemplo si necesitamos cambiar de rama rápidamente.

---

## 12. ¿Qué opciones ofrece Git para deshacer cambios?
Git permite deshacer cambios de varias formas, como restaurar archivos, revertir commits o
volver a un estado anterior del proyecto, dependiendo de la situación.

---

## 13. ¿Cómo funcionan los repositorios remotos?
Un repositorio remoto es una copia del proyecto en GitHub. Normalmente se llama origin,
y se usa para subir y bajar cambios del proyecto.

---

## 14. ¿Cómo se puede revisar el historial de cambios?
Git permite ver el historial de cambios, comparar versiones y revisar detalles de los commits
para entender cómo ha evolucionado el proyecto.
