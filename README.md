<div align="center">

  <!-- REEMPLAZAR: subí un banner a /profile/banner.png y descomentá esta línea -->
  <!-- <img src="./profile/banner.png" alt="Splash" width="100%" /> -->

  # Splash

  ### Tu negocio online, sin instalar nada.

  Reservas, tienda y gestión para PyMEs uruguayas — listo en cinco minutos.

  <br />

  [Sitio web](https://splash.app) · [Probá la demo](https://splash.app/t/barberia) · [Ver planes](https://splash.app/planes) · [Contacto](mailto:hola@splash.app)

  </div>

  ---

  ## Qué es Splash

  Splash es una plataforma SaaS que le da a cualquier negocio de servicios o ecommerce su propia mini-web profesional, con reservas online, tienda, gestión de clientes y comunicación automática —
  todo desde un único panel y sin que el dueño tenga que ser técnico.

  Apuntamos a un público concreto: el barbero que sigue agendando por WhatsApp, la esteticista con un Excel de turnos, el gimnasio que pierde reservas porque no contesta a tiempo, la tienda que
  vende por Instagram y necesita un catálogo serio.

  ## Para quién

  | Vertical | Casos típicos |
  |---|---|
  | Belleza y estética | Barberías, peluquerías, manicura, spa |
  | Salud | Psicología, nutrición, kinesiología, odontología |
  | Fitness y wellness | Gimnasios, yoga, pilates, personal trainers |
  | Retail digital | Indumentaria, accesorios, decoración, gastronomía |
  | Híbridos | Negocios que venden servicio y producto a la vez |

  ## Lo que hace

  - **Página pública** en `splash.app/t/tu-negocio` con catálogo, branding propio y reservas online
  - **Agenda inteligente** con disponibilidad real cruzando horarios del negocio, del empleado y cupos del servicio
  - **Ecommerce completo** con categorías, stock, carrito, checkout y gestión de pedidos
  - **Panel de gestión** con dashboard, finanzas, historial de precios, clientes y reseñas verificadas
  - **Comunicación automática** por email y WhatsApp: confirmaciones, recordatorios 24 horas antes, pedidos de reseña post-servicio
  - **Diseño configurable** con modo claro y oscuro, paleta y tipografía elegidas por cada negocio
  - **Cobros recurrentes** integrados con MercadoPago

  ## Cómo arranca un negocio

  1. Se registra en `splash.app` — catorce días gratis, sin tarjeta
  2. Onboarding guiado de cinco pasos: bienvenida, apariencia, empleados, servicios, finalización
  3. Comparte su link público `splash.app/t/su-nombre` por Instagram, WhatsApp o donde quiera
  4. Empieza a recibir reservas o ventas el mismo día
  5. Al terminar el trial, elige un plan según el tamaño del negocio

  ## Planes

  | Plan | Pensado para | Idea general |
  |---|---|---|
  | **Demo** | Probar el producto | Catorce días gratis, sin tarjeta, sin compromiso |
  | **Básico** | Profesional independiente | Lo esencial para arrancar a recibir reservas |
  | **Medio** | PyME con equipo y marketing | Suma empleados, productos y campañas |
  | **Pro** | Negocios en escala | Sin límites, soporte prioritario |

  Precios actualizados en [splash.app/planes](https://splash.app/planes).

  ## Diferenciales

  - **Tres productos en una plataforma**: agenda, ecommerce o ambos, según lo que el negocio necesite
  - **Hecho para Uruguay**: precios en pesos, MercadoPago nativo, WhatsApp integrado, español rioplatense
  - **Onboarding asistido**: el dueño del negocio queda operativo sin tutoriales ni soporte
  - **Sistema de reseñas con validación**: solo reseñan clientes con reservas completadas
  - **Cupos por servicio**: clases grupales, talleres y servicios uno a uno conviven en la misma agenda
  - **Historial de precios**: cada cambio queda registrado, los cobros pasados mantienen el precio histórico

  ## Stack técnico

  <details>
  <summary>Para devs que pasen por acá</summary>

  - **Backend**: Laravel 12 sobre PHP 8.2+
  - **Frontend**: Blade templates · Tailwind CSS · Alpine.js
  - **Build**: Vite
  - **Base de datos**: SQLite en desarrollo, MySQL en producción
  - **Cola de jobs**: sync en desarrollo, database en producción
  - **Cobros**: MercadoPago Subscriptions
  - **Email**: SMTP estándar (log driver en desarrollo)
  - **WhatsApp**: Twilio o UltraMSG
  - **Hosting objetivo**: Hostinger con LiteSpeed
  - **Arquitectura**: multi-tenant con `BelongsToTenant` trait y global scope de Eloquent, resolución por slug en la URL pública

  El repo principal es privado mientras estamos en pre-lanzamiento.

  </details>

  ## Estado del proyecto

  Splash está en desarrollo activo, en etapa pre-lanzamiento. El producto ya soporta los tres modos (agenda, ecommerce, full), tiene onboarding completo, sistema de planes funcional, panel de
  superadmin con métricas y flujo de cobros listo para conectar.

  ## Equipo

  Construido desde Uruguay por un equipo chico y enfocado, con la idea de ofrecer una herramienta profesional al precio que una PyME real puede pagar.

  ## Contacto

  - Sitio: [splash.app](https://splash.app) <!-- REEMPLAZAR si el dominio difiere -->
  - Email: [hola@splash.app](mailto:hola@splash.app) <!-- REEMPLAZAR -->
  - Instagram: [@holasplash](https://instagram.com/holasplash) <!-- REEMPLAZAR -->

  ---

  <div align="center">

  Hecho en Uruguay.

  </div>
