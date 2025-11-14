# 🌾 AgroConnect - Conectando el Campo con la Ciudad

**AgroConnect** es una aplicación móvil diseñada para reducir la intermediación comercial entre **productores agrícolas** y **consumidores urbanos**, facilitando la compraventa directa de productos frescos. Este proyecto busca mejorar los ingresos de los agricultores familiares en municipios rurales como Sabanas de San Ángel, Magdalena, al ofrecer una plataforma digital accesible y moderna.

## 🎯 Objetivo Principal

Reducir la intermediación comercial que afecta los ingresos de los productores hasta en un 60%, conectándolos directamente con los consumidores finales.

## 📱 Descripción General de la Aplicación

La aplicación funciona como un puente digital con dos roles principales y módulos independientes:

| Rol | Funcionalidades Clave |
| :--- | :--- |
| **Vendedor (Productor)** | Gestión completa de productos, inventario, pedidos, notificaciones y perfil de ventas. |
| **Comprador (Consumidor)** | Catálogo de productos, carrito de compras, proceso de checkout, historial de pedidos y sistema de mensajería. |

El sistema incluye un **Asistente AI integrado** (etiquetado como 'Contáctanos' en el diseño) y un sistema de **mensajería directa** entre usuarios.

## 🧭 Estructura de Navegación y Pantallas

El prototipo de Figma consta de 43 pantallas que cubren el flujo completo de la aplicación.

### 1. Flujo de Autenticación

| Pantalla | Descripción |
| :--- | :--- |
| **Bienvenida** | Pantalla inicial de presentación. |
| **Selección de Rol** | El usuario elige si desea ingresar como **Comprador** o **Vendedor**. Esta selección es permanente. |
| **Iniciar Sesión / Registrarse** | Formularios de autenticación. |

### 2. Módulo de Vendedor (Productor)

El vendedor tiene una barra de navegación inferior con las siguientes secciones:

| Sección | Descripción | Pantallas Clave |
| :--- | :--- | :--- |
| **Productos** | Dashboard principal. Muestra estadísticas clave (Productos, Pedidos, Ventas) y el listado de productos propios. Incluye la opción **+ Agregar** nuevo producto. | Dashboard, Mis Productos, Agregar Producto. |
| **Pedidos** | Listado y seguimiento de pedidos realizados por los compradores, con diferentes estados. | Pedidos Recientes, Detalle de Pedido. |
| **Mensajes** | Interfaz de chat para comunicarse directamente con los compradores. | Bandeja de Mensajes, Chat. |
| **Perfil** | Información del vendedor, estadísticas de ventas y botón de **Salir**. | Mi Perfil. |

### 3. Módulo de Comprador (Consumidor)

El comprador tiene una barra de navegación inferior con las siguientes secciones:

| Sección | Descripción | Pantallas Clave |
| :--- | :--- | :--- |
| **Inicio** | Catálogo principal de productos disponibles para la venta, con filtros por categoría. | Productos Disponibles, Búsqueda. |
| **Carrito** | Gestión de los productos seleccionados para la compra. | Mi Carrito. |
| **Pedidos** | Historial y seguimiento del estado de los pedidos realizados. | Mis Pedidos. |
| **Mensajes** | Interfaz de chat para comunicarse directamente con los vendedores. | Bandeja de Mensajes, Chat. |

## 💡 Características Técnicas

*   **Diseño Responsivo:** Optimizado para dispositivos móviles (375px de ancho).
*   **Accesibilidad:** Interfaz intuitiva pensada para usuarios con baja alfabetización digital.
*   **Modo Offline:** Funcionalidad básica con sincronización automática al recuperar la conexión.
*   **Tecnología:** Preparado para la conexión con bases de datos externas (Supabase o Firebase).

## 🔮 Próximas Mejoras Sugeridas

*   Integración con API de pagos (Nequi o PayU).
*   Módulo de geolocalización para logística.
*   Panel web para administración avanzada.
*   Estadísticas visuales para análisis de ventas y demanda.

## 🧑‍💻 Desarrolladores

Este proyecto fue desarrollado por:
*   Eusebio Muñoz Martínez
*   Oscar Barrientos Olmos
*   Keren Arias Acosta

*Proyecto de Grado - Ingeniería de Sistemas, Universidad Nacional Abierta y a Distancia (UNAD).*

---

*Este archivo README.md fue generado automáticamente a partir de la documentación original del proyecto.*

## 🖼️ Vistas Previas del Prototipo (43 Pantallas)

Para una mejor visualización, el prototipo ha sido desglosado en 43 imágenes individuales, organizadas por flujo. Puedes ver todas las imágenes en la carpeta [`design/screens`](./design/screens).

### 1. Flujo de Autenticación (7 Pantallas)

| Pantalla | Descripción | Vista Previa |
| :--- | :--- | :--- |
| **34_Bienvenida_Splash** | Pantalla de carga inicial. | ![](/design/screens/34_Bienvenida_Splash.png) |
| **35_Autenticacion_Seleccion_Rol** | El usuario elige entre Comprador o Vendedor. | ![](/design/screens/35_Autenticacion_Seleccion_Rol.png) |
| **27_Autenticacion_Login_Comprador** | Formulario de inicio de sesión para Comprador. | ![](/design/screens/27_Autenticacion_Login_Comprador.png) |
| **36_Autenticacion_Login_Comprador_Lleno** | Login Comprador con campos llenos. | ![](/design/screens/36_Autenticacion_Login_Comprador_Lleno.png) |
| **28_Autenticacion_Login_Vendedor** | Formulario de inicio de sesión para Vendedor. | ![](/design/screens/28_Autenticacion_Login_Vendedor.png) |
| **29_Autenticacion_Registro_Comprador** | Formulario de registro para Comprador. | ![](/design/screens/29_Autenticacion_Registro_Comprador.png) |
| **30_Autenticacion_Registro_Vendedor** | Formulario de registro para Vendedor. | ![](/design/screens/30_Autenticacion_Registro_Vendedor.png) |

### 2. Módulo de Comprador (18 Pantallas)

| Pantalla | Descripción | Vista Previa |
| :--- | :--- | :--- |
| **01_Comprador_Productos_Catalogo** | Pantalla principal con el catálogo de productos. | ![](/design/screens/01_Comprador_Productos_Catalogo.png) |
| **02_Comprador_Productos_Filtro** | Vista del catálogo con filtros aplicados. | ![](/design/screens/02_Comprador_Productos_Filtro.png) |
| **03_Comprador_Producto_Detalle** | Detalle de un producto específico. | ![](/design/screens/03_Comprador_Producto_Detalle.png) |
| **04_Comprador_Producto_Detalle_Modal** | Modal para añadir al carrito. | ![](/design/screens/04_Comprador_Producto_Detalle_Modal.png) |
| **05_Comprador_Carrito_Vacio** | Vista del carrito sin productos. | ![](/design/screens/05_Comprador_Carrito_Vacio.png) |
| **06_Comprador_Carrito_Lleno** | Vista del carrito con productos. | ![](/design/screens/06_Comprador_Carrito_Lleno.png) |
| **07_Comprador_Carrito_Checkout** | Proceso de pago (Checkout). | ![](/design/screens/07_Comprador_Carrito_Checkout.png) |
| **13_Comprador_Carrito_Checkout_Lleno** | Checkout con datos de envío y pago llenos. | ![](/design/screens/13_Comprador_Carrito_Checkout_Lleno.png) |
| **14_Comprador_Carrito_Confirmacion** | Modal de confirmación de pedido. | ![](/design/screens/14_Comprador_Carrito_Confirmacion.png) |
| **15_Comprador_Pedido_Exitoso** | Pantalla de pedido confirmado. | ![](/design/screens/15_Comprador_Pedido_Exitoso.png) |
| **08_Comprador_Pedidos_Historial** | Historial de pedidos realizados. | ![](/design/screens/08_Comprador_Pedidos_Historial.png) |
| **18_Comprador_Pedidos_Historial_Lleno** | Historial de pedidos con datos. | ![](/design/screens/18_Comprador_Pedidos_Historial_Lleno.png) |
| **09_Comprador_Mensajes_Bandeja** | Bandeja de entrada de mensajes. | ![](/design/screens/09_Comprador_Mensajes_Bandeja.png) |
| **17_Comprador_Mensajes_Bandeja_Lleno** | Bandeja de entrada con mensajes. | ![](/design/screens/17_Comprador_Mensajes_Bandeja_Lleno.png) |
| **10_Comprador_Mensajes_Chat** | Interfaz de chat con un vendedor. | ![](/design/screens/10_Comprador_Mensajes_Chat.png) |
| **16_Comprador_Mensajes_Chat_Lleno** | Chat con conversación. | ![](/design/screens/16_Comprador_Mensajes_Chat_Lleno.png) |
| **11_Comprador_Perfil** | Perfil del comprador. | ![](/design/screens/11_Comprador_Perfil.png) |
| **12_Comprador_Perfil_Editar** | Edición del perfil del comprador. | ![](/design/screens/12_Comprador_Perfil_Editar.png) |

### 3. Módulo de Vendedor (18 Pantallas)

| Pantalla | Descripción | Vista Previa |
| :--- | :--- | :--- |
| **19_Vendedor_Dashboard_Productos** | Dashboard principal del vendedor (Productos). | ![](/design/screens/19_Vendedor_Dashboard_Productos.png) |
| **38_Vendedor_Dashboard_Productos_Lleno** | Dashboard con productos listados. | ![](/design/screens/38_Vendedor_Dashboard_Productos_Lleno.png) |
| **31_Vendedor_Producto_Agregar** | Formulario para agregar un nuevo producto. | ![](/design/screens/31_Vendedor_Producto_Agregar.png) |
| **39_Vendedor_Producto_Agregar_Lleno** | Formulario de agregar producto lleno. | ![](/design/screens/39_Vendedor_Producto_Agregar_Lleno.png) |
| **32_Vendedor_Producto_Editar** | Formulario para editar un producto existente. | ![](/design/screens/32_Vendedor_Producto_Editar.png) |
| **40_Vendedor_Producto_Editar_Lleno** | Formulario de editar producto lleno. | ![](/design/screens/40_Vendedor_Producto_Editar_Lleno.png) |
| **33_Vendedor_Producto_Eliminar_Modal** | Modal de confirmación para eliminar producto. | ![](/design/screens/33_Vendedor_Producto_Eliminar_Modal.png) |
| **20_Vendedor_Dashboard_Pedidos** | Vista de pedidos pendientes. | ![](/design/screens/20_Vendedor_Dashboard_Pedidos.png) |
| **41_Vendedor_Pedidos_Recientes_Lleno** | Vista de pedidos recientes con datos. | ![](/design/screens/41_Vendedor_Pedidos_Recientes_Lleno.png) |
| **22_Vendedor_Pedidos_Recientes** | Detalle de un pedido reciente. | ![](/design/screens/22_Vendedor_Pedidos_Recientes.png) |
| **42_Vendedor_Pedidos_Detalle_Lleno** | Detalle de pedido con información completa. | ![](/design/screens/42_Vendedor_Pedidos_Detalle_Lleno.png) |
| **21_Vendedor_Dashboard_Ventas** | Vista de estadísticas de ventas. | ![](/design/screens/21_Vendedor_Dashboard_Ventas.png) |
| **24_Vendedor_Mensajes_Bandeja** | Bandeja de entrada de mensajes. | ![](/design/screens/24_Vendedor_Mensajes_Bandeja.png) |
| **43_Vendedor_Mensajes_Bandeja_Lleno** | Bandeja de entrada con mensajes. | ![](/design/screens/43_Vendedor_Mensajes_Bandeja_Lleno.png) |
| **25_Vendedor_Mensajes_Chat** | Interfaz de chat con un comprador. | ![](/design/screens/25_Vendedor_Mensajes_Chat.png) |
| **26_Vendedor_Perfil** | Perfil del vendedor. | ![](/design/screens/26_Vendedor_Perfil.png) |
| **37_Autenticacion_Registro_Vendedor_Lleno** | (Duplicado de Registro Vendedor) | ![](/design/screens/37_Autenticacion_Registro_Vendedor_Lleno.png) |
| **32_Vendedor_Producto_Editar** | (Duplicado de Editar Producto) | ![](/design/screens/32_Vendedor_Producto_Editar.png) |
