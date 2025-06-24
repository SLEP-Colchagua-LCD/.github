# 🤝 Guía para Contribuir

¡Hola! 👋  
Gracias por querer mejorar el **Libro de Clases Digital (LCD)**.  
Este proyecto es parte del **Servicio Local de Educación Pública de Colchagua**, y juntos queremos construir tecnología pública que realmente sirva a nuestras escuelas.

Aquí te explicamos cómo aportar de forma simple, ordenada y segura.

---

## 🚀 ¿Cómo empiezo?

### 1. Clona o forkea el repositorio

- Si tienes acceso: clónalo directamente.
- Si no: haz un **fork** y trabaja desde ahí.

### 2. Crea una nueva rama con nombre claro

Usa este formato:

```bash
feature/nueva-funcionalidad  
fix/arreglo-de-error  
doc/actualiza-documentacion  
```

👉 Ejemplos:

- `feature/agregar-asistencia-por-dia`
- `fix/error-en-promedio-final`

### 3. Haz tus cambios

Aplica buenas prácticas y comenta lo que no sea obvio.

### 4. Revisa que todo funcione

Antes de subir:

- ✅ Que compile sin errores
- ✅ Que no rompa lo que ya existe
- ✅ Que pasen las pruebas (si hay)

### 5. Crea un Pull Request

Dirígelo a la rama `develop` e incluye una descripción breve:

- ✅ Qué hiciste
- ✅ Por qué lo hiciste
- ✅ Cómo probarlo

---

## ✅ Buenas prácticas

- Nombra bien tus archivos, funciones y ramas
- Comenta tu código cuando sea necesario
- Agrega pruebas si tu cambio lo necesita
- Usa el mismo estilo que ya se usa en el código
- Escribe **commits en español**, breves y claros:

```bash
feat: permite exportar asistencia a Excel  
fix: soluciona error al editar calificación  
doc: agrega guía de despliegue al README  
```

---

## 🚫 No subas al repositorio

Evita incluir archivos sensibles o innecesarios, como:

- ❌ Contraseñas o claves privadas
- ❌ Archivos `.env`, `.pem`, `config.local.json`
- ❌ Datos personales o confidenciales
- ❌ Archivos generados automáticamente (`build/`, `dist/`, `logs/`)

💡 Usa el archivo `.gitignore` para excluir estos archivos.

---

## 📁 Estructura del proyecto (referencia)

```bash
├── src/               # Código del sistema  
├── tests/             # Pruebas  
├── docs/              # Documentación  
├── .github/           # Configuración de GitHub  
│   ├── ISSUE_TEMPLATE/  
│   └── workflows/  
├── README.md          # Guía general  
└── CONTRIBUTING.md    # Esta guía  
```

---

## 📬 ¿Necesitas ayuda?

Si tienes preguntas, escribe al equipo TI:  
📧 [soporte.ti@slepcolchagua.cl](mailto:soporte.ti@slepcolchagua.cl)

---

> **Construir tecnología pública es construir futuro.**  
Gracias por ser parte del cambio 💙
