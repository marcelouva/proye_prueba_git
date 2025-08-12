# Introducción a Git y GitHub
**Asignatura:** Ingeniería de Software  
**Docente:** [Tu nombre]  
**Fecha:** [Fecha de la clase]

---

## ¿Qué es Git?
- Sistema de control de versiones **distribuido** creado por **Linus Torvalds** en 2005.
- Permite llevar un **historial de cambios** en archivos de un proyecto.
- Funciona **localmente** y no depende de conexión a internet para registrar cambios.
- Es rápido, seguro y confiable.

**Nota del orador:** Explicar que Git es como una "máquina del tiempo" para el código.

---

## ¿Para qué sirve Git?
- Guardar un **historial completo** del proyecto.
- Volver a versiones anteriores cuando sea necesario.
- Trabajar en **ramas** para probar ideas sin afectar la versión principal.
- Coordinar el trabajo entre varios desarrolladores.
- Detectar y resolver conflictos de cambios.

---

## Problemas que resuelve Git
**Antes de Git:**
- Sobrescribir archivos por accidente.
- Archivos con nombres como: `final_definitivo_v3_ahora_si.py`.
- Dificultad para trabajar en equipo sobre el mismo archivo.

**Con Git:**
- Historial organizado.
- Trabajo simultáneo sin perder cambios.
- Comparar y combinar versiones fácilmente.

---

## Cómo funciona Git
**Conceptos clave:**
- **Repositorio:** Carpeta con el código y su historial.
- **Commit:** Fotografía del proyecto en un momento.
- **Rama (branch):** Línea de desarrollo independiente.
- **Merge:** Combinar cambios de ramas diferentes.

**Nota del orador:** Dibujar un diagrama de ramas en la pizarra para reforzar.

---

## Estados en Git
Git maneja 3 estados principales:

1. **Working Directory** – Archivos modificados pero no preparados.
2. **Staging Area** – Archivos listos para un commit.
3. **Repository** – Archivos confirmados en el historial.

```bash
# Ejemplo de flujo
git status       # Ver cambios
git add archivo.txt   # Pasar a staging
git commit -m "Agregado nuevo archivo"  # Confirmar al repositorio
```

---

## Configuración inicial
Antes de usar Git por primera vez:

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

---

## Crear un nuevo repositorio
```bash
# Crear repositorio en carpeta actual
git init

# Clonar un repositorio existente
git clone URL
```

---

## Registrar cambios
```bash
# Agregar archivo específico
git add archivo.txt

# Agregar todos los cambios
git add .

# Confirmar cambios
git commit -m "Descripción de los cambios"
```

---

## Ver historial y estado
```bash
# Ver estado de archivos
git status

# Ver historial de commits
git log
```

---

## Comandos para trabajo en equipo
```bash
# Subir cambios
git push origin main

# Descargar cambios
git pull origin main

# Crear rama
git branch nombre_rama

# Cambiar de rama
git checkout nombre_rama

# Combinar ramas
git merge nombre_rama
```

---

## Ejemplo práctico
Flujo típico de trabajo:

```bash
git init
echo "Hola mundo" > index.txt
git add index.txt
git commit -m "Primer commit"
git branch nueva-funcion
git checkout nueva-funcion
echo "Nueva línea" >> index.txt
git add index.txt
git commit -m "Agregada nueva línea"
git checkout main
git merge nueva-funcion
```

---

## ¿Qué es GitHub?
- Plataforma en la nube para alojar repositorios Git.
- Permite colaborar y compartir proyectos.
- Ofrece:
  - Repositorios públicos y privados.
  - Issues para seguimiento de tareas.
  - Pull requests para proponer cambios.
  - Integración con herramientas de CI/CD.

---

## Git vs GitHub
| Git | GitHub |
|-----|--------|
| Control de versiones | Servicio en la nube |
| Funciona localmente | Funciona en internet |
| Creado por Linus Torvalds | Fundado por Tom Preston-Werner y otros |

---

## Flujo básico con GitHub
1. Crear repositorio en GitHub.
2. Clonarlo en la computadora.
3. Trabajar con Git localmente (add, commit).
4. Subir cambios con `git push`.
5. Colaborar mediante pull requests.

---

## Ejemplo final con GitHub
```bash
git clone https://github.com/usuario/proyecto.git
cd proyecto
# Editar archivos
git add .
git commit -m "Actualización de la función X"
git push origin main
```

---

## Recursos y prácticas sugeridas
- [Documentación oficial de Git](https://git-scm.com/doc)
- [Guía de GitHub](https://docs.github.com)
- Practicar con un repositorio de prueba.
