
# Principales comandos

## git --version
	Muestra la versión instalada de Git.	
    Ejemplo de uso
    git --version
## git init
	Inicializa un repositorio Git en la carpeta actual.	
    Ejemplo de uso
    git init
## git add	
    Agrega cambios al área de preparación (staging).	
    Ejemplo de uso
    git add . (agrega todos los archivos)
## git commit	
    Registra los cambios con un mensaje descriptivo.	
    Ejemplo de uso
    git commit -m "Mi primer commit"
## git status	
    Muestra el estado del repo: cambios, staging, rama, etc.	
    Ejemplo de uso
    git status
## git clone	
    Copia un repositorio remoto a tu máquina local.	
    Ejemplo de uso
    git clone https://github.com/usuario/repo.git
## git push	
    Sube tus commits al repositorio remoto.	
    Ejemplo de uso
    git push origin main
## git pull	
    Descarga y fusiona cambios del repositorio remoto.
    Ejemplo de uso	
    git pull origin main
## git branch	
    Lista, crea o elimina ramas.	
    Ejemplo de uso
    git branch nueva-rama
## git checkout
    Cambia entre ramas o restaura archivos.	
    Ejemplo de uso
    git checkout desarrollo
## git merge
	Fusiona una rama con la rama actual.	
    Ejemplo de uso
    git merge nueva-funcionalidad
## git log
	Muestra el historial de commits.
    Ejemplo de uso
    git log --oneline
## git remote
	Gestiona conexiones con repositorios remotos.	
    Ejemplo de uso
    git remote add origin <url>
## git fetch
	Descarga cambios pero no los fusiona.	
    Ejemplo de uso
    git fetch origin
## git diff
	Muestra diferencias entre archivos o commits.
    Ejemplo de uso
    git diff HEAD~1 HEAD
