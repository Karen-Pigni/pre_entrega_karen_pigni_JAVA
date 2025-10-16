# 🧩 Sistema de Gestión de Artículos en Consola (Java)

Aplicación de consola desarrollada en **Java** que permite **gestionar artículos y pedidos** mediante un menú interactivo.  
El sistema sigue una arquitectura **por capas (MVC simplificado)** para mantener un código limpio, escalable y fácil de mantener.

---

## 📂 Estructura del proyecto

```bash
src/
│
├── controller/              # Controladores: manejan la lógica del flujo y la interacción con el usuario
│   ├── ArticuloController.java
│   └── PedidoController.java
│
├── service/                 # Servicios: contienen la lógica de negocio y manipulación de datos
│   ├── ArticuloService.java
│   └── PedidoService.java
│
├── model/                   # Modelos: representan las entidades principales del sistema
│   ├── Articulo.java
│   │    └── Bebida.java
│   └── Pedido.java
│
├── util/                    # Clases utilitarias: validaciones y lectura segura desde consola
│   └── Validations.java
│
└── Main.java                # Punto de entrada de la aplicación y menú principal
