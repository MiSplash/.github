<div align="center">

# MiSplash

### Tu negocio, abierto las 24 horas.

Reservas, tienda y gestión para negocios uruguayos — funcionando en 15 minutos.

<br />

[Sitio web](https://misplash.com) · [Ver una página de ejemplo](https://misplash.com/t/barberia) · [Contacto](mailto:uysplash@gmail.com) · [Instagram](https://instagram.com/misplashuy)

</div>

---

## Nuestros productos

| Producto | Qué resuelve | Cómo se adapta |
|---|---|---|
| **[MiSplash Negocios](https://misplash.com/negocios)** | Presencia online + gestión para PyMEs: reservas, tienda y panel en una sola plataforma | Tres modos según el negocio: **Agenda** (servicios y turnos), **Ecommerce** (tienda online) y **Full** (ambos unificados) |
| **[MiSplash Proyectos](https://misplash.com/proyectos)** | Gestión integral de organizaciones, colectivos y proyectos independientes | Módulos activables por organización: finanzas, recaudación, calendario, integrantes y auditoría |

---

## Qué es MiSplash

Miles de negocios chicos coordinan su día a mano: turnos por WhatsApp, pedidos en un cuaderno,
precios en una libreta. Funciona hasta que deja de funcionar — se pisan dos turnos, se pierde un
pedido, y siempre hay alguien esperando una respuesta a las once de la noche.

MiSplash le da a cada negocio **su propia página pública** y **un panel para administrarla**. Sus
clientes reservan o compran solos, cuando quieren, sin crearse una cuenta ni instalar nada. El
negocio se entera por mail y lo ve todo ordenado en un lugar.

Apuntamos a un público concreto: el barbero que sigue agendando por WhatsApp, la esteticista con un
Excel de turnos, el gimnasio que pierde reservas porque no contesta a tiempo, la tienda que vende por
Instagram y necesita un catálogo serio.

## Para quién

| Vertical | Casos típicos |
|---|---|
| Belleza y estética | Barberías, peluquerías, manicura, spa |
| Salud | Psicología, nutrición, kinesiología, odontología |
| Fitness y wellness | Gimnasios, yoga, pilates, personal trainers |
| Retail digital | Indumentaria, accesorios, decoración, gastronomía |
| Híbridos | Negocios que venden servicio y producto a la vez |

## Lo que hace

- **Página pública** en `misplash.com/t/tu-negocio` con catálogo, branding propio y reservas online
- **Agenda inteligente** con disponibilidad real cruzando horarios del negocio, del empleado y cupos del servicio
- **Ecommerce completo** con categorías, stock, carrito, checkout y gestión de pedidos
- **Panel de gestión** con dashboard, finanzas, historial de precios, clientes y reseñas verificadas
- **Comunicación automática** por email: confirmaciones, recordatorios el día antes, campañas a clientes
- **Diseño configurable** con temas, paleta y branding elegidos por cada negocio
- **Cobros recurrentes** integrados con MercadoPago

## Cómo arranca un negocio

1. Se registra en `misplash.com` — **7 días gratis, sin tarjeta**
2. Onboarding guiado paso a paso: bienvenida, apariencia, servicios, productos y equipo
3. Comparte su link público `misplash.com/t/su-nombre` por Instagram, WhatsApp o donde quiera
4. Empieza a recibir reservas o ventas el mismo día
5. Al terminar la prueba, elige el plan según el tamaño del negocio

## Planes

Tres productos según lo que el negocio necesite — **Agenda** (servicios y turnos), **Ecommerce**
(tienda online) y **Full** (ambos en un panel unificado) — cada uno en dos niveles:

| Nivel | Pensado para | Idea general |
|---|---|---|
| **Prueba** | Conocer el producto | 7 días gratis, sin tarjeta, sin compromiso |
| **Emprendedor** | Profesional independiente | Lo esencial para arrancar a recibir reservas o vender |
| **Pro** | PyME con equipo | Suma empleados, campañas, finanzas, reseñas y ofertas |
| **Add-on Ilimitados** | Negocios en escala | Elimina todos los límites sobre el plan Pro |

Hay descuento pagando el año por adelantado. Precios actualizados en
[misplash.com/negocios](https://misplash.com/negocios).

## Diferenciales

- **Tres productos en una plataforma**: agenda, ecommerce o ambos, según lo que el negocio necesite
- **Hecho para Uruguay**: precios en pesos, MercadoPago nativo, WhatsApp del negocio integrado, español rioplatense
- **Onboarding asistido**: el dueño del negocio queda operativo sin tutoriales ni soporte
- **Pensado para el celular**: es desde donde sus clientes van a abrir la página, así que es el caso principal y no una adaptación
- **Sistema de reseñas con validación**: solo reseñan clientes con reservas completadas
- **Cupos por servicio**: clases grupales, talleres y servicios uno a uno conviven en la misma agenda
- **Historial de precios**: cada cambio queda registrado, los cobros pasados mantienen el precio histórico

## MiSplash Proyectos

El segundo producto de la casa: un sistema de gestión integral para organizaciones, colectivos y
proyectos independientes —murgas, clubes, grupos— que necesitan ordenar su operación sin
herramientas dispersas.

| Módulo | Qué hace |
|---|---|
| **Finanzas** | Movimientos de ingresos y egresos, reportes y exportación |
| **Recaudación** | Campañas de rifas con rangos asignados por vendedor y seguimiento de vendidas |
| **Calendario** | Actividades, ensayos y eventos de la organización en un solo lugar |
| **Integrantes** | Padrón del equipo con roles diferenciados (administrador, gestor, integrante) |
| **Auditoría** | Registro de cada acción sensible: quién hizo qué y cuándo |
| **Perfil configurable** | Branding, colores y textos propios de cada organización |

Igual que Negocios tiene sus modos Agenda, Ecommerce y Full, Proyectos se adapta activando los
módulos que cada organización necesita.

## Stack técnico

<details>
<summary>Para devs que pasen por acá</summary>

- **Backend**: Laravel 12 sobre PHP 8.2+
- **Frontend**: Blade templates · Tailwind CSS · Alpine.js
- **Build**: Vite
- **Base de datos**: SQLite en desarrollo, MySQL en producción
- **Cola de jobs**: sync en desarrollo, database en producción
- **Cobros**: MercadoPago Subscriptions (pagos recurrentes)
- **Arquitectura**: multi-tenant — cada negocio funciona aislado dentro de la misma aplicación, con resolución por slug en la URL pública

Prioridades de diseño: que el celular sea el caso principal y no una adaptación, que ningún negocio
pueda ver los datos de otro, y que nada que involucre dinero dependa de que una pantalla haya quedado
abierta.

El repo principal es privado.

</details>

## Estado del proyecto

**En producción.** El circuito completo funciona de punta a punta con pagos reales: alta del negocio,
onboarding, reservas y ventas, cobro de la suscripción, cambio de plan con prorrateo y baja.

El producto soporta los tres modos (agenda, ecommerce, full), tiene onboarding completo, página
pública configurable, panel de superadmin con métricas y una suite de pruebas automatizadas sobre los
flujos críticos. Estamos abriendo a los primeros negocios.

## Equipo

Construido desde Uruguay por un equipo chico y enfocado, con la idea de ofrecer una herramienta
profesional al precio que una PyME real puede pagar.

## Contacto

- Sitio: [misplash.com](https://misplash.com)
- Email: [uysplash@gmail.com](mailto:uysplash@gmail.com)
- Instagram: [@misplashuy](https://instagram.com/misplashuy)

---

<div align="center">

Hecho en Uruguay.

</div>
