🛡️ Sistema Icoria - Gestión de Usuarios y Accesos (TP 2)

Proyecto desarrollado en C# utilizando Windows Forms y SQL Server, correspondiente al Trabajo Práctico N° 2.

🚀 Características del Sistema
- **Autenticación Segura:** Control de acceso mediante roles (Administrador y General) y validación de usuarios activos.
- **Primer Ingreso Obligatorio:** Forzamiento del cambio de contraseña en el primer inicio de sesión.
- **Recuperación de Contraseña:** Flujo guiado con código de validación.
- **Panel de Administración:** Grilla interactiva para gestión completa de usuarios (altas, modificaciones, bajas lógicas y borrados físicos).
- **Registro de Usuarios:** Alta de nuevos perfiles con validaciones estrictas (DNI, expresiones regulares) y generación automática de credenciales.
- **Edición de Perfil:** Modificación de datos personales y domiciliarios según restricciones de rol.

---

🛠️ Tecnologías y Requisitos
- **Lenguaje:** C# (.NET 8.0)
- **Interfaz Gráfica:** Windows Forms (WinForms)
- **Base de Datos:** SQL Server / LocalDB
- **Librería de Conexión:** `Microsoft.Data.SqlClient`

---

📥 Puesta en Marcha (Instrucciones para el equipo)

1. **Clonar o descargar** este repositorio en tu computadora.
2. **Configurar la Base de Datos:**
   - Abrir **SQL Server Management Studio (SSMS)**.
   - Ejecutar el script SQL provisto en la carpeta del proyecto para crear la base de datos y la tabla `Usuarios` con los registros iniciales.
3. **Cadena de Conexión:**
   - La conexión por defecto está configurada en la clase `ConexionBD.cs` apuntando a un servidor local (`Server=.;Database=MiSistemaDB;Integrated Security=True;...`). Si utilizás una instancia distinta (como SQL Express), actualizala en dicho archivo.
4. **Ejecución:**
   - Abrir la solución `Login_Grupal.sln` con **Visual Studio**.
   - Compilar y presionar **Iniciar (F5)**.

---

🔑 Credenciales de Prueba Iniciales
- **Administrador:**
  - *Usuario:* `admin`
  - *Contraseña:* `123` (o la configurada en el script inicial)
