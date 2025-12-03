# 📘 Documentación para el Usuario Final: Guía Rápida de **GestPass**

## 🏷️ Título: GestPass — Su Gestor de Contraseñas Seguro e Intuitivo

**Dirigido a:**  
Usuarios sin conocimientos técnicos avanzados, profesionales independientes y PYMEs.

**Propósito:**  
GestPass es una aplicación web que le permite almacenar, gestionar y cifrar sus contraseñas de forma segura y accesible.  
Esta guía le ayudará a utilizar las funcionalidades principales de la plataforma.

---

## 🔐 Sección 1: Primeros Pasos y Seguridad

### 1.1 Acceso y Confianza

Para acceder a **GestPass**, solo necesita iniciar sesión con sus credenciales.  
Utilizamos un sistema de autenticación moderno (**NextAuth y JWT**) que asegura que solo usted pueda acceder a sus datos.

**Seguridad de sus Datos:**  
La seguridad es la prioridad principal de GestPass.  
Todas sus contraseñas almacenadas se protegen mediante cifrado avanzado (**bcrypt**), lo que significa que su información está codificada de forma que nadie (ni siquiera los desarrolladores de GestPass) puede leerla directamente.

---

### 1.2 Estructura del Almacenamiento

GestPass le permite organizar sus credenciales como **“Elementos”**.  
Usted puede clasificar estos elementos en distintas categorías:
- Inicio de Sesión  
- Tarjeta  
- Identidad  
- Entre otras  

Esto facilita un almacenamiento y administración segura de sus credenciales.

---

## 🗂️ Sección 2: Gestión de sus Credenciales (Elementos)

El corazón de **GestPass** es la administración segura de sus credenciales.

### 2.1 Agregar un Nuevo Elemento

1. **Navegación:** Diríjase a la sección **“Mis Elementos”** y haga clic en el botón **“Añadir”**.  
2. **Tipo de Elemento:** Seleccione el tipo de elemento que está agregando (por ejemplo, *Inicio de Sesión* para una página web, o *Tarjeta* para detalles bancarios).  
3. **Información:** Ingrese el nombre, el sitio web (URL), el nombre de usuario y la contraseña asociada.  
4. **Guardar:** Una vez guardado, su información queda **cifrada inmediatamente**.

---

### 2.2 Usando el Generador de Claves

Para asegurar la máxima protección, utilice el **Generador de Claves incorporado**.  
Este le permite crear contraseñas robustas que cumplen con los requisitos de seguridad (caracteres especiales, longitud, etc.), minimizando el riesgo de accesos no autorizados.

---

### 2.3 Edición y Organización

- **Edición:** Puede modificar la información de cualquier elemento en cualquier momento.  
- **Favoritos:** Marque un elemento como *Favorito* si lo utiliza frecuentemente para acceder a él rápidamente.  
- **Notas:** Use el campo *Notas* para añadir información adicional o recordatorios específicos sobre la credencial.

---

## 🧰 Sección 3: Servicios y Soporte Técnico

**GestPass** ofrece servicios de posventa diseñados para aumentar su confianza como consumidor.

### 3.1 Recuperación de Contraseña del Usuario (Vía Resend)

Si olvida su contraseña principal de GestPass, puede recuperarla de manera segura siguiendo estos pasos:

1. **Solicitud:** En la pantalla de inicio de sesión, seleccione la opción **“Olvidé mi contraseña”**.  
2. **Verificación:** Ingrese el correo electrónico asociado a su cuenta GestPass.  
3. **Envío Seguro:** El sistema utilizará el servicio **Resend** para enviarle un correo electrónico de recuperación.  
   Este correo incluirá un enlace temporal y seguro para que pueda establecer una nueva contraseña.  
4. **Advertencia:** Si no solicita la recuperación, ignore y elimine el correo.  
   Nunca comparta este enlace con terceros.  
   *(Esta funcionalidad se encuentra operativa en el estado actual del proyecto).*

---

### 3.2 Reporte de Errores y Soporte

Valoramos la mejora continua del sistema.  
Si encuentra algún problema, error o comportamiento inesperado:

- **Reporte Directo:** Utilice la sección **“Reportar Errores”** del sistema.  
  Los mensajes enviados a través de esta sección llegan directamente al correo del desarrollador, asegurando una rápida atención y respuesta.
