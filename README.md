# 🛍 Sistema de Ventas PHP - Gestión Comercial Completa

> Sistema de gestión de ventas moderno y eficiente desarrollado en *PHP nativo* con arquitectura MVC para pequeñas y medianas empresas.

[![PHP](https://img.shields.io/badge/PHP-8.0+-blue.svg)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-5.7+-orange.svg)](https://www.mysql.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![AJAX](https://img.shields.io/badge/AJAX-XMLHttpRequest-green.svg)](https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX)
[![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)

## 🌟 Características Principales

### 💼 *Gestión Integral de Ventas*
- *Punto de Venta (POS)* intuitivo y rápido
- *Facturación electrónica* con códigos de barras
- *Control de inventario* en tiempo real
- *Reportes de ventas* detallados y personalizables

### 👥 *Administración de Usuarios*
- *Sistema de roles* (Admin, Cajero, Vendedor)
- *Autenticación segura* con sesiones
- *Gestión de perfiles* con fotografías
- *Control de accesos* por módulos

### 📊 *Módulos Especializados*
- *Gestión de Productos* con categorías y subcategorías
- *Control de Clientes* con historial de compras
- *Gestión de Proveedores* (Editoriales/Autores)
- *Reportes Financieros* con gráficos interactivos

### 🎨 *Interfaz Moderna*
- *Diseño responsive* para todos los dispositivos
- *Dashboard interactivo* con métricas en tiempo real
- *Navegación intuitiva* con sidebar dinámico
- *Alertas y notificaciones* en tiempo real

## 🚀 Tecnologías Utilizadas

### *Backend*
- *PHP 8.0+* - Lenguaje principal
- *MySQL* - Base de datos relacional
- *Arquitectura MVC* - Separación de responsabilidades

### *Frontend*
- *HTML5 & CSS3* - Estructura y estilos modernos
- *JavaScript ES6+* - Interactividad del cliente
- *AJAX* - Comunicación asíncrona
- *FontAwesome* - Iconografía profesional

### *Librerías Integradas*
- *FPDF* - Generación de reportes PDF
- *Code128* - Códigos de barras
- *Responsive Design* - Adaptable a cualquier pantalla

## 📁 Arquitectura del Sistema

```
-ventas/
├── 🏗 config/              # Configuración del sistema
├── 📊 DB/                  # Base de datos y scripts SQL
├── 📱 app/
│   ├── 🔄 ajax/           # Comunicación asíncrona
│   ├── 🎯 controllers/    # Lógica de control MVC
│   ├── 🗃 models/         # Modelos de datos
│   ├── 📄 pdf/            # Generación de documentos
│   └── 🎨 views/          # Interfaz de usuario
│       ├── 📋 content/    # Páginas principales
│       ├── 💅 css/        # Estilos personalizados
│       ├── 📸 fotos/      # Imágenes de usuarios
│       ├── 🛍 productos/  # Imágenes de productos
│       └── ⚡ js/         # Scripts JavaScript
└── 📚 Documentación completa
```

## ⚡ Funcionalidades Destacadas

### 🛒 *Sistema de Ventas Avanzado*
- ✅ *Búsqueda inteligente* de productos
- ✅ *Cálculo automático* de totales e impuestos
- ✅ *Múltiples métodos de pago*
- ✅ *Impresión de tickets* y facturas
- ✅ *Control de stock* automático

### 📈 *Reportes y Analytics*
- 📊 *Dashboard ejecutivo* con KPIs
- 📋 *Reportes de inventario* detallados
- 💰 *Análisis de ventas* por período
- 📱 *Exportación a PDF* profesional
- 🎯 *Métricas de rendimiento*

### 🔐 *Seguridad Robusta*
- 🛡 *Autenticación por sesiones*
- 🔒 *Validación de datos* en frontend y backend
- 👤 *Control de acceso* granular
- 🚫 *Protección contra inyección SQL*
- 🔄 *Sesiones seguras* con timeout

## 🛠 Instalación Rápida

### Prerrequisitos

```
- *PHP 8.0+* con extensiones MySQL
- *Apache/Nginx* servidor web
- *MySQL 5.7+* base de datos
- *Navegador moderno* (Chrome, Firefox, Safari)
```

### Pasos de Instalación

1. *📥 Clonar el repositorio*
    ```
    bash
   git clone https://github.com/julianpinto15/sistema-ventas-php.git
   cd sistema-ventas-php
   ```

3. *🗄 Configurar base de datos*
```
    sql
   -- Crear base de datos
   CREATE DATABASE ventas_db;
   
   -- Importar estructura
   mysql -u root -p ventas_db < DB/ventas.sql
 ```

5. *⚙ Configurar conexión*
 ```
   php
   // Editar config/server.php
   define('DB_HOST', 'localhost');
   define('DB_USER', 'tu_usuario');
   define('DB_PASS', 'tu_password');
   define('DB_NAME', 'ventas_db');
  ``` 

4. *🚀 Ejecutar aplicación*
 ```
   bash
   # Iniciar servidor PHP
   php -S localhost:8000
   
   # O configurar en Apache/Nginx
   # Acceder a: http://localhost/sistema-ventas-php
   ```

5. *🔐 Credenciales por defecto*
   ```
   - *Usuario:* admin
   - *Contraseña:* admin123
    ```

## 🎯 Casos de Uso Perfectos

### 🏪 *Retail y Comercio*
- ✅ Tiendas de ropa y accesorios
- ✅ Librerías y papelerías
- ✅ Ferreterías y suministros
- ✅ Farmacias y droguerías

### 🍕 *Servicios y Restauración*
- ✅ Restaurantes y cafeterías
- ✅ Servicios profesionales
- ✅ Centros de belleza
- ✅ Talleres y reparaciones

## 📸 Capturas del Sistema

### 🔐 Acceso y Autenticación

-  🛡️ Pantalla de Login Principal
  
![Image](https://github.com/user-attachments/assets/bb45d01c-588a-465a-8e4b-1948f846947d)

### 🏠 Panel de Control

-   🎛️ Dashboard Ejecutivo 
  
![Image](https://github.com/user-attachments/assets/4f761ca3-cfc2-446f-8296-48929c2cafd8)

### 💰 Sistema de Ventas

-   📋 Detalle de Transacción
  
![Image](https://github.com/user-attachments/assets/35c5811f-d0dc-4028-8d36-76cf48465f39)

### 🛒 Terminal POS Móvil

![Image](https://github.com/user-attachments/assets/cfa1cb35-db29-4311-b9e8-77af775374ba)

### 📦 Gestión de Inventario

-   📊 Control de Stock de Productos
  
![Image](https://github.com/user-attachments/assets/c03538cf-0d0c-415f-bb5b-1c7acfefed6e)

### 👥 Administración de Datos

-   🤝 Base de Datos de Clientes
  
![Image](https://github.com/user-attachments/assets/53247d4e-99b2-42f2-b228-1c4923544f55)

### 🏷️ Sistema de Categorías

![Image](https://github.com/user-attachments/assets/7028b4d5-d81f-40f0-a33b-73759c54e239)

### 💰 Administración de Cajas

![Image](https://github.com/user-attachments/assets/274a18eb-2df4-41a8-aa2f-28ea51d80009)

### ⚙️ Configuración de Usuario

-   📝 Registro de Nuevos Usuarios

![Image](https://github.com/user-attachments/assets/af4b48e1-a62d-4bf2-9adc-d230415e6702)

### 🔧 Panel de Configuración de Cuenta

![Image](https://github.com/user-attachments/assets/d107bc95-31e8-4beb-9b1d-436c00da569b)

## 🔄 Características AJAX

### ⚡ *Funcionalidades Dinámicas*
- 🔍 *Búsqueda en tiempo real* sin recargar página
- 📝 *Actualización automática* de inventarios
- 🛒 *Carrito de compras* dinámico
- 📊 *Gráficos interactivos* en dashboard
- 💾 *Guardado automático* de formularios

## 📋 Módulos Incluidos

| Módulo | Descripción | Estado |
|--------|-------------|--------|
| 👤 *Usuarios* | Gestión completa de usuarios y roles | ✅ |
| 🛒 *Ventas* | Sistema POS con facturación | ✅ |
| 📦 *Productos* | Inventario y categorización | ✅ |
| 👥 *Clientes* | CRM básico integrado | ✅ |
| 📊 *Reportes* | Analytics y reportes PDF | ✅ |
| 🏢 *Empresa* | Configuración y branding | ✅ |
| 🔐 *Seguridad* | Autenticación y permisos | ✅ |


## 🎉 Próximas Características

### 🔮 *Roadmap 2024*
- [ ] 📱 *API REST* para integración móvil
- [ ] 🌐 *Multi-idioma* (Español, Inglés)
- [ ] 💳 *Pagos online* (PayPal, Stripe)
- [ ] 📊 *Dashboard avanzado* con BI
- [ ] 🔄 *Sincronización en la nube*

## 📄 Licencia

Este proyecto está bajo la *Licencia MIT* - ver [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Desarrollador

*Julián Pinto* - Desarrollador Full Stack
- 🌐 *GitHub:* [@julianpinto15](https://github.com/Julianpinto15)
- 💼 *LinkedIn:* [Julián Pinto](https://www.linkedin.com/in/julian-pinto15/)
- 📧 *Email:* julianpinto700@gmail.com

---

*Santiago Barbosa * - Desarrollador Full Stack
- 🌐 GitHub: [@BARBOSA191919](https://github.com/BARBOSA191919)
- 💼 LinkedIn: [Santiago Barbosa](https://www.linkedin.com/in/santiago-barbosa-903641209/)
- 📧 Email: sbarbosarivas@gmail.com
  
---

<div align="center">

### 💡 ¿Te gusta el proyecto?

Si este sistema te ha sido útil, ¡considera darle una ⭐ en GitHub!

*[⭐ Star en GitHub](https://github.com/BARBOSA191919/Software-Libreria-P.)* 
</div>

---

<div align="center">
  <strong>Desarrollado con ❤ para impulsar tu negocio</strong><br>
  <em>Sistema de Ventas PHP - Gestión Comercial Profesional</em>
</div>
