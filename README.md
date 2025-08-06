# Aplicacion-Web-de-Cifrado-y-Gestion-Segura-de-Archivos
Aplicación web fullstack diseñada para cifrar, almacenar y gestionar tus archivos de forma segura. Protege tu privacidad y tus datos sensibles con una solución moderna y eficiente, ideal para documentos personales, imágenes o cualquier archivo que necesite un nivel extra de seguridad.

📝 Descripción
Aplicación de cifrado de archivos que combina un potente backend con Node.js y SQLite para el manejo seguro de datos y un frontend intuitivo construido con Vue.js y Nuxt.js. Esta solución autohospedable te permite encriptar y desencriptar archivos directamente desde tu navegador, asegurando que solo tú tengas acceso a tu información más valiosa.

Está diseñada pensando en la seguridad web, incorporando medidas esenciales para proteger contra ataques comunes como CSRF (Cross-Site Request Forgery) y XSS (Cross-Site Scripting), además de implementar Rate Limiting para prevenir abusos. Su arquitectura ligera garantiza un rendimiento óptimo incluso en dispositivos con recursos limitados, siendo una solución de almacenamiento seguro accesible y confiable.

✨ Características Destacadas

Cifrado Robusto: Utiliza algoritmos de cifrado estándar de la industria para proteger tus archivos.
Gestión Intuitiva: Sube, lista y descarga tus archivos cifrados con una interfaz de usuario limpia y fácil de usar.

Seguridad Integral:
Protección CSRF: Defiende contra ataques de falsificación de peticiones entre sitios.
Sanitización XSS: Previene la inyección de scripts maliciosos.
Rate Limiting: Controla el número de peticiones para mitigar ataques de fuerza bruta y DDoS.

Rendimiento Optimizado:
Backend con Node.js y SQLite: Rápido y eficiente para el manejo de archivos y metadatos.
Frontend con Vue.js y Nuxt.js: Experiencia de usuario fluida y carga rápida de páginas con SSR (Server-Side Rendering) y optimizaciones de SEO.
Base de Datos Ligera: SQLite para una gestión de metadatos sencilla y sin necesidad de configuración compleja.
Diseño Responsivo: Interfaz adaptada a cualquier dispositivo (escritorio, tablet, móvil) gracias a Bulma CSS.

🚀 Tecnologías Utilizadas

Backend
Node.js: Entorno de ejecución JavaScript.
Express.js: Framework web para Node.js.
SQLite: Base de datos relacional ligera.
Multer: Middleware para manejo de multipart/form-data (subida de archivos).
crypto (Node.js built-in): Módulo para operaciones de cifrado.
csurf: Middleware para protección CSRF.
express-rate-limit: Middleware para Rate Limiting.

Frontend
Vue.js: Framework progresivo de JavaScript.
Nuxt.js: Framework de Vue.js para aplicaciones universales y estáticas.
Bulma CSS: Framework CSS moderno y responsivo.
Axios (o fetch API): Para realizar peticiones HTTP al backend.

📦 Instalación y Configuración
Sigue estos pasos para poner en marcha la app en tu entorno local.

Prerrequisitos
Asegúrate de tener instalado:

Node.js (versión 14 o superior recomendada)
npm (viene con Node.js)

1. Clonar el Repositorio

git clone https://github.com/santiagourdaneta/Aplicacion-Web-de-Cifrado-y-Gestion-Segura-de-Archivos/
cd Aplicacion-Web-de-Cifrado-y-Gestion-Segura-de-Archivos

3. Configuración del Backend
   
# Para iniciar el backend (en una terminal separada)   
cd back
npm install
node server.js

El backend se ejecutará en http://localhost:4000.

3. Configuración del Frontend
   
# Para iniciar el frontend (en otra terminal separada)
cd front
npm install
npm run dev

El frontend se ejecutará en http://localhost:3000.

🚀 Uso
Una vez que el backend y el frontend estén corriendo:
Abre tu navegador y ve a http://localhost:3000.
Utiliza la interfaz para subir archivos. Estos se cifrarán y almacenarán de forma segura.
Podrás ver una lista de tus archivos cifrados y descargarlos para descifrarlos en tu máquina local.

🤝 Contribución
¡Las contribuciones son bienvenidas! Si deseas mejorar la app, por favor:

Haz un "fork" de este repositorio.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y asegúrate de que las pruebas pasen.
Crea un "pull request" detallado.

📄 Licencia
Este proyecto está bajo la licencia MIT.

🏷️ Etiquetas

cifrado encriptacion seguridad nodejs vuejs nuxt sqlite fullstack web-application data-privacy file-management csrf-protection 
xss-prevention rate-limiting javascript privacy self-hosted open-source #CifradoDeArchivos #SeguridadWeb #NodeJS #VueJS #NuxtJS 
#PrivacidadDeDatos #Ciberseguridad #FullstackDev #OpenSource #ProteccionDeDatos #AppWeb #SQLite #DesarrolloWeb
