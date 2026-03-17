<div align="center">
  <h1>E-commerce Web App - La Tiendita de las Mil Cosas</h1>
</div>

Este proyecto es una aplicación web completa para un negocio de ventas al por menor. Me enfoqué en crear una experiencia de usuario rápida y fluida, diseñada principalmente para dispositivos móviles, que permite gestionar todo el proceso desde la búsqueda hasta el pedido final por WhatsApp.

---

### Ejecución

* **Arquitectura Vanilla JS:** No usé frameworks pesados para que la web cargue al toque. Todo el sistema de navegación entre categorías y la renderización de productos se maneja mediante lógica pura en JavaScript.
* **Sistema de Inventario Dinámico:** La data está organizada en un motor de búsqueda interno que filtra cientos de productos al instante sin necesidad de recargar la página.
* **Carrito de Compras y Lógica de Negocio:** * Implementé un sistema de persistencia para que el usuario no pierda su pedido.
    * **Descuentos Automáticos:** El código calcula promociones por apertura y ajusta el precio final si la compra supera montos específicos.
    * **Gestión de Packs (Bundles):** Programé una lógica especial para combos que permite mostrar múltiples imágenes y detalles dentro de un solo ítem.
* **Integración con WhatsApp Business:** El sistema genera un mensaje formateado automáticamente con el nombre del cliente, distrito, fecha y el detalle exacto del pedido (cantidades, subtotal y descuentos) para cerrar la venta en un clic.

---

### Descp

* **Diseño Mobile-First:** Pensado para la gente que compra desde el celular, con menús táctiles, scroll suave y carga optimizada de imágenes (Lazy Load).
* **Buscador Inteligente:** Filtra por palabras clave en todo el inventario de categorías (Tecnología, Juguetes, Hogar, etc.) de forma inmediata.
* **Experiencia de Usuario (UX):** Incluye banners promocionales dinámicos, modales de producto con galerías de imágenes y un carrito lateral (sidebar) muy intuitivo.

---

### 📸 

**Tienda en Producción:** [latienditadelasmilcosas.serviciosgeneralesivam.com](https://latienditadelasmilcosas.serviciosgeneralesivam.com/)

---
<div align="center">
  <sub>Proyecto enfocado en convertir visitas en ventas reales mediante una interfaz rápida y funcional.</sub>
</div>
