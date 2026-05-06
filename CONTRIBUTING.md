# 🤝 Guía de Contribución

¡Gracias por considerar contribuir a mis proyectos! Como estoy aprendiendo Python desde cero, toda ayuda es bienvenida, desde corrección de errores tipográficos hasta sugerencias sobre mejores prácticas de código.
---

## 📋 Tabla de Contenidos

- [Código de Conducta](#código-de-conducta)
- [¿Cómo puedo contribuir?](#cómo-puedo-contribuir)
- [Proceso de Pull Request](#proceso-de-pull-request)
- [Convención de commits](#convención-de-commits)
- [Configuración del entorno](#configuración-del-entorno)

---

## 📜 Código de Conducta

Al participar en este proyecto, aceptas seguir nuestro [Código de Conducta](CODE_OF_CONDUCT.md).

---

## 🤔 ¿Cómo puedo contribuir?

### 🐛 Reportar bugs

Antes de crear un issue de bug, por favor:

1. Revisa si ya existe un issue similar en la [lista de issues](../../issues).
2. Si no existe, crea uno nuevo usando la plantilla **Bug Report**.
3. Incluye el máximo de información posible: versión, OS, pasos para reproducir.

### ✨ Sugerir funcionalidades

1. Abre un issue usando la plantilla **Feature Request**.
2. Describe el problema que resuelve y cómo lo imaginas.
3. Espera feedback antes de empezar a implementarlo.

### 📝 Mejorar documentación

La documentación siempre puede mejorar. Si encuentras algo confuso, incompleto o incorrecto:

1. Edita directamente desde GitHub con el botón ✏️ (para cambios pequeños).
2. Para cambios grandes, sigue el proceso de PR.

### 💻 Contribuir código

1. Busca issues etiquetados como `good first issue` o `help wanted`.
2. Comenta en el issue que quieres trabajarlo.
3. Sigue el proceso de PR descrito abajo.

---

## 🔄 Proceso de Pull Request

```bash
# 1. Fork del repositorio (botón en GitHub)

# 2. Clona tu fork
git clone https://github.com/TU-USUARIO/NOMBRE-DEL-REPOSITORIO.git
cd NOMBRE-DEL-REPOSITORIO

# 3. Crea una rama descriptiva
git checkout -b feat/nombre-de-la-feature
# o
git checkout -b fix/nombre-del-bug

# 4. Haz tus cambios y commitea
git add .
git commit -m "feat: añadir soporte para X"

# 5. Push a tu fork
git push origin feat/nombre-de-la-feature

# 6. Abre el Pull Request desde GitHub
```

**Checklist antes de abrir el PR:**

- [ ] El código sigue los estándares del proyecto
- [ ] He añadido tests si aplica
- [ ] La documentación está actualizada
- [ ] Los tests existentes pasan
- [ ] El título del PR sigue la convención de commits

---

## ✍️ Convención de Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/):

| Tipo | Descripción |
|------|-------------|
| `feat` | Nueva funcionalidad |
| `fix` | Corrección de bug |
| `docs` | Cambios en documentación |
| `style` | Formato, sin cambios en lógica |
| `refactor` | Refactorización de código |
| `test` | Añadir o modificar tests |
| `chore` | Tareas de mantenimiento |
| `perf` | Mejoras de rendimiento |

**Ejemplos:**

```
feat: añadir autenticación con Google OAuth
fix: corregir error en validación de email
docs: actualizar README con nuevas instrucciones
```

---

## ⚙️ Configuración del Entorno

```bash
# Requisitos previos
# - Python 3.10+ / Node.js 14+ (según el proyecto)
# - Git configurado

# Clonar y configurar
git clone https://github.com/TU-USUARIO/REPOSITORIO.git
cd REPOSITORIO

# Crear y activar entorno virtual (Recomendado para Windows)
python -m venv venv
-\venv\Scripts\activate

# Instalar dependencias (ajusta según tu proyecto)
pip install -r requirements.txt
# o
npm install

```

---

## 💬 ¿Preguntas?

Si tienes dudas, abre una [Discussion](../../discussions) o contáctame directamente.

¡Gracias de nuevo por contribuir! 🚀
