# WebOS 🌐💻

**WebOS** es un **sistema operativo simulado en la web**, inspirado en macOS, que funciona 100% en el navegador.  
Permite a los usuarios crear cuentas, personalizar su escritorio con **foto de perfil** y **fondo de pantalla**, y usar aplicaciones básicas como Notas, Calculadora y Terminal, sin necesidad de instalar nada.

---

## 🌟 Características principales

- **Registro e inicio de sesión** de usuarios con credenciales seguras.  
- **Foto de perfil personalizada** para cada usuario.  
- **Fondo de pantalla** personalizable, que se mantiene entre sesiones.  
- Escritorio estilo **macOS** con dock interactivo.  
- Aplicaciones integradas:
  - 📝 **Notas**: editor de texto con guardado automático.
  - 🧮 **Calculadora**: operaciones básicas (+, -, ×, ÷).
  - 💻 **Terminal**: comandos simulados (`help`, `date`, `echo`).
- **Persistencia de datos** usando `localStorage` (no requiere servidor).  
- Interfaz **responsiva** y ligera, lista para cualquier navegador moderno.  

---

## 📌 Cómo usar WebOS en la web

1. Abre el archivo `index.html` en tu navegador (no necesita servidor).  
2. **Crea una cuenta**: ingresa usuario, contraseña, foto de perfil y fondo de pantalla.  
3. Haz **login** con tus credenciales.  
4. Disfruta de tu escritorio personalizado:  
   - Haz clic en las apps del dock para abrir ventanas.  
   - Escribe notas, realiza cálculos o prueba comandos en la terminal.  
5. Todos los cambios se guardan automáticamente en **localStorage**, para que tus notas, foto y fondo se mantengan entre sesiones.  

---

## ⚙️ Detalles técnicos

- **Datos del usuario** guardados en `localStorage`:
  ```json
  {
    "password": "tu_contraseña",
    "profile": "imagen_base64",
    "wallpaper": "imagen_base64",
    "notes": "contenido_notas"
  }
