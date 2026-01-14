# La Gramola 🎵

La Gramola es una solución integral para bares que desean modernizar la experiencia musical de sus clientes. Permite que los clientes "compren" el derecho a elegir la siguiente canción que sonará en el local, integrándose directamente con la API de Spotify y gestionando pagos seguros a través de Stripe.

# 🚀 Características Principales

## 🏢 Para el Propietario (Panel de Gestión)

🔐 **Registro Seguro**: Alta de establecimientos con captura de firma digital.

📧 **Validación por Email**: Sistema de verificación de cuenta mediante tokens temporales de seguridad.

📍 **Geolocalización Automática**: El sistema detecta la ubicación exacta del bar mediante su dirección física.

🎛️ **Control de Spotify**: Gestión de dispositivos y selección de música de fondo desde sus propias playlists.

💳 **Suscripciones**: Planes mensuales y anuales gestionados dinámicamente desde la base de datos.

## 👤 Para el Cliente

🔍 **Búsqueda en Tiempo Real**: Acceso total al catálogo global de canciones de Spotify.

📏 **Restricción Geográfica**: Solo se permite añadir canciones si el cliente se encuentra en un radio de 100 metros del local (validación por GPS).

💰 **Pagos de Canciones**: Pago por canción individual integrado de forma fluida con Stripe.

⏭️ **Cola**: Las canciones pagadas se insertan automáticamente para sonar a continuación de la canción actual.

# 🛠️ Stack Tecnológico

**Frontend**: Angular.

**Backend**: Java Spring Boot.

**Base de Datos**: MySQL.

## APIs Externas:

Spotify Web API (Protocolo OAuth 2.0).

Stripe API (Pasarela de pagos).

OpenStreetMap Nominatim (Geocoding de direcciones).

Testing: Selenium WebDriver para pruebas funcionales de extremo a extremo.

# 🛡️ Seguridad y Robustez

**Encriptación**: Contraseñas protegidas mediante algoritmos de Hash SHA-256.

**Integridad**: Validación Anti-CSRF robusta en todos los flujos de autorización OAuth.

**Privacidad**: Cumplimiento de normativa PCI-DSS (los datos sensibles de tarjetas nunca tocan nuestro servidor).

# 🧪 Calidad y Testing

El proyecto incluye pruebas automatizadas con Selenium WebDriver que validan flujos críticos:

**Flujo de Éxito**: Búsqueda, pago correcto con tarjeta de prueba y verificación de registro en MySQL.

**Gestión de Errores**: Control de pagos incorrectos.

## Proyecto desarrollado en la asignatura de Tecnologías y Sistemas Web.
