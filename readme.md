cat > README.md << 'EOF'
# 📊 Empleados360 v1.1

**Empleados360** es un sistema de gestión integral para empleados, desarrollado con tecnologías web orientadas a facilitar procesos internos en empresas.  
La versión 1.1 incluye mejoras visuales, optimización de código y una estructura más clara en la base de datos.

---

## 🚀 Características principales

- 📁 Gestión de datos de empleados: altas, bajas y modificación de datos.
- 🔐 Control de accesos por rol.
- 🗂️ Generación de reportes y estadísticas internas.
- 🖥️ Interfaz intuitiva con diseño adaptable (responsive).

---

## 📂 Estructura del proyecto

\`\`\`
empleados360/
├── backend/           # Archivos PHP y lógica del sistema
├── frontend/          # HTML, CSS, JS
├── database/          # Archivo SQL con la estructura
├── assets/            # Imágenes, íconos y recursos visuales
├── README.md
└── .gitignore
\`\`\`

---

## 📦 Requisitos

- Servidor web (Apache, Nginx)
- PHP ≥ 7.4
- MySQL
- Navegador web moderno

---

## 🔗 Ruta de acceso

Una vez instalado en tu servidor local o hosting, accede desde el navegador:

\`\`\`
http://localhost/empleados360/
\`\`\`

O si está en línea:

\`\`\`
https://tu-dominio.com/empleados360/
\`\`\`

---

## 🔧 Instalación

1. Clonar el repositorio:
   \`\`\`bash
   git clone https://github.com/davidvillamoli00/empleados360.git
   \`\`\`
2. Importar el archivo SQL a tu gestor de bases de datos (MySQL).
3. Configurar la conexión en el archivo \`/backend/config/database.php\`.

---

## 📌 Versión

**v1.1**

---

## 👨‍💻 Autor

**David Villamolín**  
Repositorio: https://github.com/davidvillamoli00/empleados360
EOF
