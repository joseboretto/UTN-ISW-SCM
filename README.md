# GESTIÓN DE CONFIGURACIÓN (VIDEO)

## Consigna 1 :Comprender los conceptos de SCM expuestos en la clase teórica, para aplicarlos


1 - Definir cómo sería la estructura del repositorio de la materia en el disco duro personal de cada alumno.

2 - Identificar cada uno de los ítems de configuración.

3 - Completar la plantilla de ítems de configuración, indicando para cada uno deellos: nombre, regla de nombrado, ubicación física y tipo de ítem (CátedraClase o Producción Propia).


## Consigna 2: Comprender los conceptos de administración de configuración de software (SCM)

4 - Crear el repositorio definido en el ejercicio visto en la clase práctica.
```
Vamos a la pagina de github , nombre : UTN-ISW-SCM, creamos el readme y el git ignore
```
5 - Mostrar cómo se puede bajar al puesto de trabajo local el contenido del repositorio (check-out).
```
mostarar workflow, git clone {url}
```
6 - Agregar una carpeta al repositorio.
```
Copiamos la estrucutra, agregamos el ignore propio
```
7 - Hacer un cambio en el repositorio y actualizarlo (Commit/Check in).
```
git add . , git Commit - m "estrucutra del proyecto" , git push origin master
```
8 - Bajar (actualizar) los cambios que posea el repositorio, realizados por otros usuarios (Update).
```
Con la cuenta de otro, fork, clonear el otra carpeta, hacer un branch y  actualizar el readme.
En otra carpeta :
git clone
git branch trabajoReadme
git checkout trabajoReadme
  'ignore'
  'actualizar readme'
git Commit -a -m "Agrego el texto incial al readme con las consginas y el git ignore"
git push origin master
----------
Vuelvo a mi carpeta
git pull remote branch
```

9 -  Mostrar cómo se puede definir una línea base (etiquetado).

10 - Mostrar cómo se puede visualizar una línea base.
```
Con un GUI, muestro el repo.
```

