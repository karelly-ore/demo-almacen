# Sistema de Gestión de Almacén Multiplataforma

## Resumen del Sistema
Este repositorio es la vitrina de un ecosistema tecnológico completo diseñado para digitalizar y optimizar la logística de un almacén real. No es simplemente una API; es una solución de software integral que abarca desde el motor de datos hasta las interfaces de usuario finales para escritorio y dispositivos móviles.

El sistema permite una gestión centralizada y eficiente de todo el ciclo de vida del inventario, resolviendo desafíos operativos complejos con una arquitectura moderna y escalable.

## Arquitectura del Sistema: Un Ecosistema Conectado

El proyecto se estructura bajo una arquitectura moderna de microservicios y cliente-servidor, garantizando modularidad y alto rendimiento:

**1. Motor Backend (La Inteligencia - Python/FastAPI):**
Este repositorio (en su versión privada) contiene el "cerebro" del sistema. Es una API RESTful de alto rendimiento que centraliza:
* La lógica de negocio compleja (validación de stock, cálculo de KPIs, reglas logísticas).
* La autenticación y seguridad.
* La conexión segura con la base de datos **PostgreSQL**.
* Sirve datos estandarizados en formato **JSON**.

**2. Clientes Frontend (La Interfaz - Flutter/Dart):**
Se desarrollaron aplicaciones cliente unificadas usando Flutter, lo que permite una experiencia de usuario consistente y un despliegue rápido en múltiples plataformas:
* **Aplicación de Escritorio:** Optimizada para la administración central, dashboard analítico y generación de reportes masivos.
* **Aplicación Móvil:** Diseñada para operadores en el campo, integrando capacidades de cámara para escaneo y registro ágil de movimientos directamente en los pasillos del almacén.


## Tecnologías y Herramientas

### Clientes (Escritorio y Móvil)
* **Framework:** **Flutter** (Dart) - Para una interfaz multiplataforma nativa y de alto rendimiento.
* **Integración Hardware:** Capacidades nativas para escaneo de códigos de barras.

### Backend (Este Repositorio Showcase)
* **Lenguaje:** Python 3.x
* **Framework:** FastAPI - Para una API RESTful asíncrona y rápida.
* **Documentación Interactiva:Swagger UI (Integrado nativamente para pruebas).

### Base de Datos
* **Motor:** PostgreSQL - Base de datos relacional robusta y escalable.

### Control de Versiones
* Git / GitHub

## 📸 Vistas del Sistema en Acción

Aquí se puede apreciar la interfaz analítica y operativa consumiendo los datos de la API en tiempo real:

**1. Panel de Control Principal (WMS Dashboard - Cliente Flutter)**
### Escritorio y Applicacion
<img width="1919" height="977" alt="Captura de pantalla 2026-03-20 130036" src="https://github.com/user-attachments/assets/df6f2dd8-56a2-49b1-bd8f-caa107a028bd" />
<img width="1567" height="844" alt="Captura de pantalla 2026-03-20 130217" src="https://github.com/user-attachments/assets/f11e62c7-54bf-4bb9-920e-2a30f092680d" />
<img width="1558" height="829" alt="Captura de pantalla 2026-03-20 130251" src="https://github.com/user-attachments/assets/ff6e21e2-c8e5-41bb-ada7-34c2122fbf8b" />
<img width="1907" height="979" alt="Captura de pantalla 2026-03-20 130309" src="https://github.com/user-attachments/assets/85bb396e-0cd0-4908-b296-45bb9bc9ad85" />
<img width="479" height="718" alt="Captura de pantalla 2026-03-20 130319" src="https://github.com/user-attachments/assets/2e8ceabd-0ba3-4ead-ba7a-06103fdb3269" />

![WhatsApp Image 2026-03-20 at 1 18 37 PM](https://github.com/user-attachments/assets/ea5f9b88-8793-44e9-8bc8-d38048c5a258)
![WhatsApp Image 2026-03-20 at 1 18 37 PM (1)](https://github.com/user-attachments/assets/5f6ba197-b202-4a1e-9b58-0512f691cf7d)
![WhatsApp Image 2026-03-20 at 1 18 37 PM (2)](https://github.com/user-attachments/assets/81120654-fa71-41a8-9516-fbfe6dc053ee)
![WhatsApp Image 2026-03-20 at 1 18 37 PM (3)](https://github.com/user-attachments/assets/f57024d6-4c8a-43d7-8b4e-56ce75fc8647)
![WhatsApp Image 2026-03-20 at 1 18 37 PM (4)](https://github.com/user-attachments/assets/48358c08-3401-4788-baac-36db82831580)
![WhatsApp Image 2026-03-20 at 1 18 37 PM (5)](https://github.com/user-attachments/assets/1bcbfaa7-8815-4096-af16-a390a2e67e43)

*Descripción: Interfaz de usuario mostrando el menú principal con acceso a Dashboard, Historial, Reportes, el Mapa interactivo del almacén, Registro de movimiento y Scanner*

**2. Documentación Interactiva de la API (Swagger UI / FastAPI)**
<img width="1793" height="756" alt="image" src="https://github.com/user-attachments/assets/9e1d7818-8366-4798-a560-abac2e1c56a1" />
*Descripción: Vista de los endpoints transaccionales y analíticos que alimentan las aplicaciones cliente.*

## 🔒 Estado del Proyecto y Confidencialidad

Este repositorio sirve exclusivamente como **portafolio profesional de vitrina (showcase)**.

Este sistema fue desarrollado para un entorno de producción real. Por motivos de **estricta confidencialidad, seguridad de la información y protección de la propiedad intelectual de la lógica de negocio del cliente**, el código fuente completo, los archivos de configuración y los procedimientos de despliegue **no están disponibles al público**.

**Desarrollado por:** Karelly Ore
*Estudiante de Ingeniería de Sistemas | Arquitecta de Soluciones Multiplataforma (Backend & Flutter)*
