# Site Error Logger

**Versión 1.2**  
Autor: Ainoa Parra Duque

---

## 📋 Descripción

**Site Error Logger** es un plugin para WordPress que permite:

- 📄 Mostrar los **últimos 50 registros** del archivo `debug.log` directamente desde el panel de administración.
- ⚙️ Activar fácilmente las constantes `WP_DEBUG` y `WP_DEBUG_LOG` desde una página de configuración.
- 🛠️ Facilitar la depuración de errores y advertencias sin necesidad de acceder por FTP o al servidor.

---

## 🛠️ Funcionalidades principales

- Panel de administración con un menú propio:
  - **Errores del sitio**: Visualiza el contenido reciente del `debug.log`.
  - **Configuración**: Activa `WP_DEBUG` y `WP_DEBUG_LOG` editando automáticamente el `wp-config.php`.
  
- Compatible con WordPress 5.0 en adelante.

- Seguro (no muestra rutas completas ni ejecuta comandos remotos).

---

## 📝 Instalación

1. Sube la carpeta del plugin al directorio:  

2. Activa el plugin desde el menú **Plugins** en WordPress.

3. Accede al menú **Errores del sitio** para visualizar el log o activar la depuración.

---

## 🖥️ Uso

- Ve a **Herramientas → Errores del sitio** para ver los últimos errores registrados.
- Ve a **Herramientas → Errores del sitio → Configuración** para activar el modo depuración de WordPress.

> 📝 **Nota:** Si el archivo `debug.log` no existe, asegúrate de haber activado `WP_DEBUG` y de que el directorio `wp-content` tenga permisos de escritura.

---

## ⚠️ Advertencia Importante

> Este plugin edita el archivo **wp-config.php** para activar las constantes de depuración.  
> Haz siempre una copia de seguridad de tu archivo **wp-config.php** antes de utilizar esta función.

---

## 📤 Contribuciones

¡Eres bienvenido a contribuir!  
Puedes enviar **Pull Requests** o sugerencias a través de **Issues** en este repositorio.

---

## 📝 Licencia

Este plugin está publicado bajo la licencia [MIT](https://opensource.org/licenses/MIT).

---

## 🛠️ Desarrollado por

Ainoa Parra Duque
http://ainoapd.es
---
