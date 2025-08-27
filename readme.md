# 📊 Empleados360 v1.1

**Empleados360** es un sistema integral de gestión de empleados, diseñado para optimizar procesos internos en empresas y organizaciones.  
La versión **1.1** incorpora mejoras visuales, optimización en el rendimiento y una base de datos más clara y escalable.

---

## 🚀 Funcionalidades principales

- 📁 **Gestión completa de empleados**: altas, bajas y actualización de datos.  
- 🔐 **Control de accesos** mediante roles y permisos.  
- 🗂️ **Generación de reportes y estadísticas** para la toma de decisiones.  
- 🖥️ **Interfaz responsiva** y fácil de usar, adaptable a distintos dispositivos.  

---

## 📂 Estructura del proyecto

```
empleados360/
├── backend/           # Lógica del sistema y controladores (PHP)
├── frontend/          # Interfaz de usuario (HTML, CSS, JavaScript)
├── database/          # Scripts SQL para la base de datos
├── assets/            # Recursos estáticos: imágenes, íconos, estilos
├── README.md
└── .gitignore
```

---

## 📦 Requisitos del sistema

- Servidor web (Apache o Nginx)  
- PHP **7.4 o superior**  
- MySQL  
- Navegador web moderno  

---

## 🔧 Instalación

1. **Clonar el repositorio**  
   ```bash
   git clone https://github.com/davidvillamoli00/empleados360.git
   ```

2. **Importar la base de datos**  
   - Cargar el archivo SQL ubicado en `/database/` dentro de tu gestor MySQL.  

3. **Configurar la conexión**  
   - Editar el archivo:  
     ```bash
     /backend/config/database.php
     ```

4. **Acceder al sistema**  
   - En entorno local:  
     ```
     http://localhost/empleados360/
     ```
   - En producción:  
     ```
     https://tu-dominio.com/empleados360/
     ```

---

## 📌 Versión actual

**v1.1** – Estable  

---

## 🛠️ Roadmap / Próximas mejoras

- [ ] Implementación de autenticación en dos pasos (2FA).  
- [ ] Integración con API de nómina y RRHH.  
- [ ] Sistema de notificaciones por correo y dashboard.  
- [ ] Exportación de reportes en PDF/Excel.  
- [ ] Tests automatizados para backend y frontend.  

---

## 👨‍💻 Autor

**David Villamolín**  
🔗 Repositorio oficial: [Empleados360](https://github.com/davidvillamoli00/empleados360)  

---
