# 🛡️ Guía de Organización y Seguridad de Proyectos PHP

Material de apoyo para estudiantes de Ingeniería Informática. Esta guía cubre la transición desde la POO básica hacia el desarrollo de aplicaciones web profesionales, seguras y mantenibles.

## 🚀 Cómo usar esta guía

1. **Navegación:** Abre el archivo `index.html` en tu navegador. La guía está diseñada con un menú lateral y modo oscuro/claro.
2. **Estructura Base:** 
   - Coloca el archivo `generador_proyecto.php` en la raíz de tu servidor local (ej: `htdocs` o `www`).
   - Ejecútalo desde el navegador (`http://localhost/generador_proyecto.php`) o por consola (`php generador_proyecto.php`).
   - Esto creará automáticamente las carpetas `app`, `config`, `public`, etc., con los archivos base funcionales.
3. **Requisitos:** PHP 7.4 o superior (se recomienda 8.x para aprovechar Argon2id y mejores tipados).

## 📂 Estructura de Archivos de la Guía
- `index.html`: Módulo 1 (Anatomía del proyecto)
- `base-datos.html`: Módulo 2 (PDO, Singleton, Transacciones)
- `seguridad.html`: Módulos 3-5 (Auth, Hashing, CSRF, XSS, Validación)
- `arquitectura.html`: Módulos 6-8 (MVC, Roles, Debugging, Extras profesionales)
- `recursos.html`: Módulos 9-10 (Checklist imprimible, Glosario)
- `styles.css` / `script.js`: Estilos y funcionalidad compartida.

## ⚠️ Notas para el Estudiante
- Los bloques marcados con 🕵️‍♂️ **Caso de Hackeo** muestran vulnerabilidades reales. **Nunca** uses ese código en producción.
- Los bloques con 🛡️ **La Defensa** son las prácticas obligatorias para tu proyecto.
- La sección "Cultura Profesional" en el Módulo 4 es informativa. No es obligatoria para la calificación, pero dominarla te diferenciará en el mercado laboral.

---
*Desarrollado como material educativo para la cátedra de Desarrollo Web.*