LA GRAMOLA

La Gramola es una solución integral para bares que desean modernizar la experiencia musical de sus clientes. Permite que los clientes "compren" el derecho a elegir la siguiente canción que sonará en el local, integrándose directamente con la API de Spotify y gestionando pagos seguros a través de Stripe.

Características Principales

Para el Propietario (Panel de Gestión)

Registro Seguro: Alta de establecimientos con firma digital.

Validación por Email: Sistema de verificación de cuenta mediante tokens temporales.

Geolocalización Automática: El sistema detecta la ubicación del bar mediante su dirección física.

Control de Spotify: Gestión de dispositivos y selección de música de fondo desde sus propias playlists.

Suscripciones: Planes mensuales y anuales gestionados dinámicamente desde la base de datos.

Para el Cliente

Búsqueda en Tiempo Real: Acceso al catálogo global de Spotify.

Restricción Geográfica: Solo se permite añadir canciones si el cliente se encuentra en un radio de 100 metros del local (validación GPS).

Micro-pagos: Pago por canción individual integrado con Stripe.

Cola Inteligente: Las canciones pagadas se insertan automáticamente para sonar a continuación.

Stack Tecnológico

Frontend: Angular 17+ (Signals, Standalone Components, Tailwind CSS).

Backend: Java Spring Boot 3 (Spring Data JPA, Spring Mail, REST).

Base de Datos: MySQL 8.

APIs Externas: - Spotify Web API (OAuth 2.0).

Stripe API (Pasarela de pagos).

OpenStreetMap Nominatim (Geocoding).

Testing: Selenium WebDriver para pruebas funcionales.

📋 Requisitos Previos

Java 17 o superior.

Node.js y Angular CLI.

MySQL Server activo.

Cuentas de Desarrollador:

Spotify Developer (Client ID y Secret).

Stripe (Secret Key de prueba).

Seguridad

Contraseñas protegidas mediante Hash SHA-256.

Validación de integridad Anti-CSRF en flujos OAuth.

Cumplimiento de normativa PCI-DSS (los datos de tarjeta nunca tocan nuestro servidor).

Proyecto desarrollado para la asignatura de Tecnologías y Sistemas Web.
