# My-Project

## Descripción del proyecto

Este es un proyecto nuevo de repositorio.  
Hasta el momento se han utilizado los siguientes comandos de Git:

- `git clone`
- `cd`
- `ls`
- `git status`
- `git add .`

---

## Evidencia inicial

![Inicio del proyecto](https://github.com/user-attachments/assets/7422a12c-9ab5-4ae8-bea5-fe353d7383af)

---

## Pregunta 1

**Si has clonado el repositorio, ¿es necesario ejecutar todos los comandos anteriores?  
¿Qué parte del comando se puede omitir? Justifica tu respuesta.**

### Respuesta

Como solo he clonado el repositorio en local, no se puede omitir ningún comando básico de navegación o verificación.  
Sin embargo, al hacer un commit, se podría usar el comando:

- `git commit -am "mensaje"`

Esto permitiría **omitir el `git add .`**, siempre que los archivos ya existan y estén previamente versionados.

---

![Creación de rama y merge](https://github.com/user-attachments/assets/fd2cc340-2100-4874-acf9-259e1ab60625)

---

## Pregunta 2

**¿El fichero y el directorio privado deben subirse al repositorio si están añadidos al archivo `.gitignore`? [Sí/No]. Justifica tu respuesta.**

### Respuesta

**No.**  
Los archivos y directorios incluidos en el archivo `.gitignore` **no se suben al repositorio**, ya que Git los ignora explícitamente para evitar que se versionen.

---

![Rama v02 y archivos txt](https://github.com/user-attachments/assets/4c24727c-56e2-46dc-bebf-961d4aac5f89)

---

## Pregunta 3

**Si se ejecutan las acciones `git add` y `git commit`, ¿qué realiza cada una sobre los ficheros? Justifica tu respuesta.**

### Respuesta

- `git add` se encarga de **añadir los archivos al área de preparación (staging area)**.
- `git commit` se encarga de **guardar definitivamente los cambios en el repositorio local**, creando un nuevo commit.

---

![Commit a 1txt](https://github.com/user-attachments/assets/4ed22b01-5543-4d3a-943d-40acbf8a77e9)

---

## Pregunta 4

**¿Qué es un tag en un repositorio Git (en este caso GitHub)? Justifica tu respuesta.**

### Respuesta

Un **tag** es una referencia que marca un commit específico como **especial o importante**, normalmente usado para identificar versiones estables del proyecto, como lanzamientos (`v1.0`, `v2.0`, etc.).

---

![Uso de gitignore](https://github.com/user-attachments/assets/49e395a0-5fb4-4cbb-91d9-bcb613d1a526)

---

## Pregunta 5

**Cuando trabajamos con ramas, ¿cuál es su fin y sentido en organizaciones pequeñas, medianas y grandes? Justifica tu respuesta.**

### Respuesta

Existe una rama principal llamada `main` o `master`, de la cual se derivan todas las demás.  
Las ramas secundarias permiten trabajar en nuevas funcionalidades, correcciones o pruebas sin afectar la rama principal, facilitando el trabajo en equipo y la organización del desarrollo, especialmente en proyectos medianos y grandes.

---

![Tags y ramas](https://github.com/user-attachments/assets/b5092bd9-ddaf-4f5e-816f-4c9545ab2043)

---

## Pregunta 6

**¿Se deberían producir conflictos en esta acción? [Sí/No]. Justifica tu respuesta.**

### Respuesta

**No**, a menos que existan cambios incompatibles entre ramas.  
Los conflictos suelen aparecer cuando dos ramas modifican las mismas líneas de un archivo y se intenta hacer un `git merge`.  
Un `git push` previo no es la causa directa del conflicto, sino las diferencias en los cambios realizados.

---

## Evidencia de merge y conflicto

![Git merge](https://github.com/user-attachments/assets/55242e0f-7334-4eca-bf7c-3e624a97e3d9)

![Preparando conflicto](https://github.com/user-attachments/assets/2b13ce88-be5d-4b9f-a017-341c3a517a4d)

![Resolviendo conflicto con vim](https://github.com/user-attachments/assets/5ad2d8ce-a075-4ca9-8ef7-a1fefe2301d4)

![Pendiente de push](https://github.com/user-attachments/assets/22770bac-b310-49a2-a40c-f227bd7450eb)
