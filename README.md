# CREAR REPOSITORIOS

##  ¿Qué es un Repositorio en GitHub?  
Un **repositorio** en GitHub es un espacio donde puedes almacenar, organizar y colaborar en proyectos de código.  

*  Guarda código y archivos del proyecto.  
*  Permite hacer seguimiento a los cambios con **Git**.  
*  Facilita la colaboración con otros desarrolladores.  
*  Se puede usar para desplegar proyectos en servidores como **Hestia**, **Oracle Cloud**, o para sitios web con **Apache y PHP**.  

---

##  Cómo Crear un Repositorio en GitHub  

###  **1. Crear un Repositorio desde GitHub**  
1️. Ve a [GitHub](https://github.com/) e **inicia sesión**.  
2️. Haz clic en el botón **New Repository** o ve a `https://github.com/new`.  
3️.**Escribe el nombre** de tu repositorio.  
4️.  Agrega una **descripción opcional**.  
5️.  Elige si el repositorio será **público o privado**.  
6️.  Marca la opción de `Initialize this repository with a README` si quieres un archivo inicial.  
7️.  Haz clic en **Create Repository**.  

---

### 🔹 **2. Crear un Repositorio desde la Terminal (Linux)**   

####  **Inicializar un Repositorio Git**  
```bash
git init
```

Este comando crea un repositorio vacío en tu carpeta actual.

 Vincularlo con GitHub
1.  Agrega los archivos al repositorio:
```
git add 
```
2️.  Guarda los cambios en un commit:
```
git commit -m "Primer commit"
```
3️. Conéctalo con GitHub (reemplaza usuario y repositorio con los tuyos):
```
git remote add origin https://github.com/usuario/repositorio.git
```
4️. Sube los archivos a GitHub:
```
git push -u origin main
```
