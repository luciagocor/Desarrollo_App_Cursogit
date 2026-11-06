# Aplicación Colaborativa del Equipo (Tarea taller Git & GitHub 06/11/2026)

Este repositorio sirve como entorno de simulación y práctica para afianzar el flujo de trabajo profesional con **Git (Terminal)** y **GitHub**.

---

## 📌 Guía de Convenciones y Normas de Ramas

Para mantener un historial limpio, organizado y evitar conflictos, es **obligatorio** seguir esta nomenclatura al trabajar en el proyecto.

### Reglas para Nombrar vuestra Rama

Cada desarrollador debe crear una rama independiente para implementar su función. El nombre de la rama **NO** debe ser genérico (evita nombres como `mi-rama`, `prueba` o `rama1`).

Debeis utilizar la siguiente estructura estándar:

```text
feature/<nombre1_nombre2>-<funcionalidad>
```

#### 🛠️ Comando para crear y cambiar a tu rama:
```bash
# Formato general
git checkout -b feature/tu-nombre-tu-funcion

# Ejemplo concreto
git checkout -b feature/elena-login
```

---

## 🔄 Flujo de Trabajo Paso a Paso (Workflow)

Para realizar tu contribución sin interferir con el trabajo del resto del equipo, sigue este orden estricto de comandos en la terminal:

1. **Asegúrate de estar en la rama principal y actualizada:**
   ```bash
   git checkout main
   git pull origin main
   ```

2. **Regístrate en este README:**
   Añade tu nombre en la sección de **Directorio del Equipo** (más abajo), hacer esto sin crear una nueva rama.

3. **Prepara y guarda tus cambios con un commit descriptivo:**
   ```bash
   git add .
   git commit -m "Registro en README"
   ```

2. **Con tu compañero, cread una rama de trabajo siguiendo la convención de nombres:**
   ```bash
   git checkout -b feature/tu-nombre-tu-funcion
   ```

3. **Editad el código en `app.py`:**
   Añade tu función personalizada.


6. **Subid vuestra rama al repositorio remoto:**
   ```bash
   git push origin feature/tu-nombre-tu-funcion
   ```

7. **Abre una Pull Request (PR) en GitHub:**
   Ve a la plataforma web de GitHub, selecciona tu rama recién subida y abre una PR hacia `main` solicitando la revisión de tus cambios.

---

## 👥 Directorio del Equipo (Registro de Autores)

A continuación se muestra la lista oficial de desarrolladores que han contribuido al código base de la aplicación. **Añade tu nombre al final de la lista durante tu ejercicio:**

* **** [Nombre Apellido] - Desarrollador/a | Rama: feature/nombre-funcion
Manuel Pavon - Junior

---

## ⚠️ Resolución de Conflictos y Buenas Prácticas

* **Haz `git pull` frecuente:** Antes de subir tus cambios o crear una nueva rama, descarga siempre lo que han hecho tus compañeros.
* **Mensajes de commit claros:** Usa prefijos como `feat:` para nuevas funciones o `docs:` para cambios en la documentación (`README.md`).
* **Un conflicto es normal:** Si dos personas editan el mismo archivo al mismo tiempo, Git detendrá la fusión y pedirá intervención manual. ¡Consulta con el equipo para decidir qué cambio conservar!
