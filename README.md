# UNAD
Proyecto SIGDA PROTOTIPO
# 📱 Gestión de Excedentes Alimentarios

Aplicación desarrollada en **Glide**, diseñada para gestionar y redistribuir excedentes alimentarios de almacenes de forma organizada y responsable.  
Permite registrar donantes, administrar inventarios de alimentos, consultar detalles de los productos y visualizar su ubicación en mapa.

---

##  Características Principales

| Funcionalidad | Descripción |
|--------------|-------------|
| Gestión de Donantes | Registro de información personal y visual de entidades que aportan alimentos |
| Control de Excedentes | Creación, edición y visualización de productos con excedente |
| Geolocalización | Mapa interactivo con ubicación de los almacenes |
| Control de inventarios | Cantidades, estado y fecha de caducidad del producto |
| Búsqueda y filtrado | Búsqueda de productos y donantes de forma rápida |

---

##  Módulos de Navegación

La aplicación se compone del siguiente menú inferior:

| Módulo | Descripción |
|--------|-------------|
| Inicio | Sección base de navegación |
| Excedentes | Inventario y gestión de productos disponibles |
| Solicitar Excedente | Solicitud directa de productos a los almacenes |
| Mapa | Ubicación geográfica de almacenes y puntos de entrega |

---

## Diseño UI/UX

- Diseño moderno, limpio y minimalista
- Simpleza en navegación e interacción
- Botones principales con color **azul/morado** (#4A56E2)
- Tipografía sans-serif alta legibilidad
- Vistas tipo tarjeta y tabla para productos y donantes
- Componentes con bordes redondeados y sombras suaves
- Imágenes destacadas para facilitar identificación de alimentos

---

## Modelo de Datos

### Colecciones utilizadas en Glide

| Colección | Campos principales | Relación |
|----------|------------------|----------|
| Donantes | Nombre, correo, teléfono, foto, ubicación | Independiente |
| Excedentes | Producto, cantidad, estado, fecha caducidad, imagen, ubicación | Relación 1:N con Almacenes |
| Almacenes | Nombre, dirección, coordenadas | Indice para ubicación |

---

### Relaciones entre tablas

---

## Flujo de Usuario

```mermaid
flowchart TD
    A[Usuario] --> B[Inicio]
    B --> C[Excedentes]
    C --> D[Ver Detalle del Producto]
    D --> E[Ver Ubicación en Mapa]
    B --> F[Donantes]
    F --> G[Registrar Donante]

MIT License - Se permite modificar, usar y distribuir el código de forma libre.


## Capturas de Pantalla
<img width="428" height="849" alt="image" src="https://github.com/user-attachments/assets/1c88fb6f-8471-4849-9ecf-ca3240ec9764" />

<img width="417" height="849" alt="image" src="https://github.com/user-attachments/assets/043ac106-13c4-42b0-ae0a-99ad93078dd7" />

<img width="408" height="851" alt="image" src="https://github.com/user-attachments/assets/c3d4a97b-5a88-4c20-b9a7-f76491da7b70" />

<img width="419" height="855" alt="image" src="https://github.com/user-attachments/assets/0d5c7e6a-628e-4fe7-8148-7d692729d256" />


---
---

## Estructura del Repositorio


https://go.glideapps.com/app/BrdHFDYZZtJZgjSgYeqO/layout
