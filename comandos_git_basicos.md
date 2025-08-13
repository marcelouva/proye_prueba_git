# Comandos básicos de Git 🐙

## 1. `git init` – Inicia un repositorio  
Crea un nuevo repositorio Git en la carpeta actual.  
```bash
git init
```
📌 *Úsalo cuando quieras empezar a usar Git en un proyecto existente.*

---

## 2. `git clone` – Copia un repositorio existente  
Descarga todo el contenido de un repositorio remoto (por ejemplo, de GitHub) a tu computadora.  
```bash
git clone https://github.com/usuario/proyecto.git
```
📌 *Úsalo para trabajar con un proyecto que ya existe en la nube.*

---

## 3. `git status` – Muestra el estado  
Te dice qué archivos han cambiado, cuáles están listos para guardar y cuáles no.  
```bash
git status
```
📌 *Es como mirar el “mapa” antes de decidir tu siguiente paso.*

---

## 4. `git add` – Prepara cambios  
Añade archivos al “área de preparación” para que puedan ser guardados en el próximo commit.  
```bash
git add archivo.txt
git add .   # añade todos los archivos modificados
```
📌 *Piensa que es como meter cosas en una caja antes de sellarla.*

---

## 5. `git commit` – Guarda los cambios  
Crea un punto en la historia del proyecto con un mensaje que explique qué hiciste.  
```bash
git commit -m "Agrega la funcionalidad de login"
```
📌 *Es como hacer una foto de tu proyecto en ese momento.*

---

## 6. `git log` – Muestra el historial  
Te deja ver todos los commits hechos en el proyecto.  
```bash
git log
```
📌 *Es como mirar el álbum de fotos de tu proyecto.*

---

## 7. `git log --color --oneline --graph` – Historial resumido y visual  
Muestra el historial en una sola línea por commit, con colores y un gráfico de las ramas.  
```bash
git log --color --oneline --graph
```
📌 *Ideal para ver de forma rápida cómo se ramifica y une el proyecto.*

---

## 8. `git push` – Sube cambios al repositorio remoto  
Envía tus commits a la nube (GitHub, GitLab, etc.).  
```bash
git push origin main
```
📌 *Comparte tu trabajo con el resto del equipo.*

---

## 9. `git pull` – Baja cambios del repositorio remoto  
Descarga y combina los cambios que otros hicieron.  
```bash
git pull origin main
```
📌 *Actualiza tu proyecto con lo último que hay en el repositorio remoto.*

---

## 10. `git branch` – Maneja ramas  
Sirve para ver, crear o borrar ramas (versiones paralelas del proyecto).  
```bash
git branch            # lista las ramas
git branch nueva-rama # crea una nueva rama
```
📌 *Una rama es como un camino alternativo para trabajar sin romper el principal.*

---

## 11. `git checkout` – Cambia de rama o estado  
Te mueve a otra rama o a un commit anterior.  
```bash
git checkout nueva-rama
```
📌 *Es como cambiar de línea temporal en una historia.*
