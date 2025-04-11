# 🚀 Mi Primer Proyecto con Git y GitHub 🚀

## 📝 Descripción
¡Bienvenido a mi primer proyecto utilizando Git para control de versiones! Este repositorio es parte de mi proceso de aprendizaje sobre Git y GitHub, donde estoy practicando comandos básicos y flujo de trabajo con control de versiones.

## 🎯 Objetivos
- Aprender los comandos básicos de Git
- Entender el flujo de trabajo de control de versiones
- Practicar la colaboración a través de GitHub
- Documentar mi progreso en este emocionante viaje

## 🛠️ Comandos Básicos de Git

### Configuración Inicial
```bash
# Configurar nombre de usuario
git config --global user.name "Tu Nombre"

# Configurar correo electrónico
git config --global user.email "tu@email.com"
```

### Crear y Clonar Repositorios
```bash
# Inicializar un repositorio nuevo
git init

# Clonar un repositorio existente
git clone https://github.com/usuario/repositorio.git
```

### Cambios Básicos
```bash
# Ver estado actual del repositorio
git status

# Añadir archivos al área de preparación
git add archivo.txt    # Añadir un archivo específico
git add .              # Añadir todos los archivos nuevos y modificados

# Confirmar cambios (crear commit)
git commit -m "Descripción de los cambios realizados"
```

### Trabajando con Ramas
```bash
# Ver las ramas existentes
git branch

# Crear una nueva rama
git branch nueva-rama

# Cambiar a otra rama
git checkout otra-rama
git switch otra-rama   # A partir de Git 2.23

# Crear y cambiar a una nueva rama en un solo paso
git checkout -b nueva-funcion
git switch -c nueva-funcion   # A partir de Git 2.23
```

### Sincronización con Repositorio Remoto
```bash
# Añadir repositorio remoto
git remote add origin https://github.com/usuario/repositorio.git

# Subir cambios al repositorio remoto
git push origin rama

# Obtener cambios del repositorio remoto
git pull origin rama

# Ver repositorios remotos configurados
git remote -v
```

### Fusionar Cambios
```bash
# Fusionar otra rama con la rama actual
git merge otra-rama

# Rebasar la rama actual sobre otra
git rebase otra-rama
```

### Revisar Historial
```bash
# Ver historial de commits
git log
git log --oneline      # Formato resumido
git log --graph        # Visualización gráfica
```

## 💡 Consejos Útiles
- Haz commits pequeños y frecuentes con mensajes descriptivos
- Actualiza tu repositorio local antes de empezar a trabajar
- Crea ramas para trabajar en funcionalidades nuevas
- Usa `.gitignore` para excluir archivos que no necesitan control de versiones
- Revisa siempre tus cambios antes de hacer commit con `git diff`

## 📚 Recursos Recomendados
- [Documentación oficial de Git](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Oh Shit, Git!?!](https://ohshitgit.com/) - Soluciones para errores comunes

## 📈 Progreso Personal
- [x] Configurar Git en mi computadora
- [x] Crear mi primer repositorio
- [x] Hacer mi primer commit
- [x] Conectar con GitHub
- [ ] Colaborar en un proyecto con otras personas
- [ ] Resolver mi primer conflicto de merge

---

⭐ ¡No olvides darle una estrellita a este repositorio si te ha sido útil! ⭐
