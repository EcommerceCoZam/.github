# 🛒 **EcommerceCoZam** - Proyecto de Microservicios E-Commerce

Bienvenido a **EcommerceCoZam**, un proyecto integral de arquitectura de microservicios desarrollado como proyecto final del curso de Ingeniería de Software V. Este proyecto implementa una solución completa de e-commerce utilizando tecnologías modernas, prácticas de DevOps, y principios de arquitectura cloud-native.

## 📋 **Descripción del Proyecto**

EcommerceCoZam es una implementación completa de una plataforma de comercio electrónico basada en microservicios, desarrollada siguiendo metodologías ágiles y las mejores prácticas de la industria. El proyecto abarca desde la infraestructura como código hasta la observabilidad y monitoreo, pasando por pipelines de CI/CD, pruebas automatizadas y gestión de cambios.

### 🎯 **Objetivos Principales**

- Implementar una arquitectura de microservicios robusta y escalable
- Aplicar prácticas modernas de DevOps y seguridad
- Desarrollar una solución cloud-native con Kubernetes
- Implementar observabilidad y monitoreo completo
- Seguir metodologías ágiles durante todo el ciclo de desarrollo

## 🏗️ **Arquitectura del Sistema**

El sistema está compuesto por múltiples microservicios independientes que trabajan en conjunto para proporcionar una experiencia completa de e-commerce:

### **Servicios Core**
- **Gateway y Descubrimiento**: Gestión de tráfico y registro de servicios
- **Autenticación**: Manejo seguro de usuarios y autorización
- **Gestión de Productos**: Catálogo y categorías
- **Gestión de Usuarios**: Perfiles de clientes y administradores
- **Sistema de Pedidos**: Procesamiento completo de órdenes
- **Pagos**: Procesamiento seguro de transacciones
- **Envíos**: Gestión logística y tracking
- **Favoritos**: Lista de deseos personalizada

### **Servicios de Soporte**
- **Configuración Centralizada**: Gestión de configuraciones
- **Monitoreo y Observabilidad**: Métricas, logs y trazas distribuidas
- **Infraestructura**: Aprovisionamiento automatizado con Terraform

## 📁 **Repositorios del Proyecto**

La organización EcommerceCoZam contiene los siguientes repositorios:

### 🚀 **Servicios de Aplicación**
| Repositorio | Tecnología | Descripción |
|-------------|------------|-------------|
| [`ecommerce-api-gateway`](https://github.com/EcommerceCoZam/ecommerce-api-gateway) | Java | Gateway de API - Punto de entrada principal |
| [`ecommerce-service-discovery`](https://github.com/EcommerceCoZam/ecommerce-service-discovery) | Java | Servidor de descubrimiento de servicios (Eureka) |
| [`ecommerce-proxy-client`](https://github.com/EcommerceCoZam/ecommerce-proxy-client) | Java | Cliente proxy para autenticación y autorización |
| [`ecommerce-user-service`](https://github.com/EcommerceCoZam/ecommerce-user-service) | Java | Gestión de usuarios y perfiles |
| [`ecommerce-product-service`](https://github.com/EcommerceCoZam/ecommerce-product-service) | Java | Catálogo de productos y categorías |
| [`ecommerce-order-service`](https://github.com/EcommerceCoZam/ecommerce-order-service) | Java | Procesamiento y gestión de pedidos |
| [`ecommerce-payment-service`](https://github.com/EcommerceCoZam/ecommerce-payment-service) | Java | Procesamiento de pagos |
| [`ecommerce-shipping-service`](https://github.com/EcommerceCoZam/ecommerce-shipping-service) | Java | Gestión de envíos y logística |
| [`ecommerce-favourite-service`](https://github.com/EcommerceCoZam/ecommerce-favourite-service) | Java | Lista de productos favoritos |
| [`ecommerce-cloud-config`](https://github.com/EcommerceCoZam/ecommerce-cloud-config) | Java | Servidor de configuración centralizada |

### 🔧 **Infraestructura y DevOps**
| Repositorio | Tecnología | Descripción |
|-------------|------------|-------------|
| [`infrastructure`](https://github.com/EcommerceCoZam/infrastructure) | HCL/Terraform | Infraestructura como código |
| [`k8s-manifests`](https://github.com/EcommerceCoZam/k8s-manifests) | Shell/YAML | Manifiestos de Kubernetes |
| [`ecommerce-helm-charts`](https://github.com/EcommerceCoZam/ecommerce-helm-charts) | Smarty/Helm | Charts de Helm para despliegue |
| [`vm-devops-provisioning`](https://github.com/EcommerceCoZam/vm-devops-provisioning) | Ansible | Aprovisionamiento automatizado de VMs para DevOps con Ansible |
| [`ecommerce-pipeline-library`](https://github.com/EcommerceCoZam/ecommerce-pipeline-library) | Groovy | Biblioteca de pipelines CI/CD |

### 🧪 **Calidad y Documentación**
| Repositorio | Tecnología | Descripción |
|-------------|------------|-------------|
| [`ecommerce-tests`](https://github.com/EcommerceCoZam/ecommerce-tests) | Python | Suite completa de pruebas automatizadas |
| [`ecommerce-parent`](https://github.com/EcommerceCoZam/ecommerce-parent) | - | Proyecto padre para gestión de dependencias |
| [`ecommerce-docs`](https://github.com/EcommerceCoZam/ecommerce-docs) | Markdown | Documentación técnica y metodológica |

## 🛠️ **Stack Tecnológico**

### **Backend**
- **Java 11** con Spring Boot y Spring Cloud
- **Maven** para gestión de dependencias
- **MySQL** y **H2** para persistencia de datos

### **Infraestructura**
- **Docker** para containerización
- **Kubernetes** para orquestación
- **Terraform** para infraestructura como código
- **Ansible** para aprovisionamiento y configuración automatizada de VMs
- **Helm** para gestión de despliegues

### **Observabilidad**
- **Prometheus** y **Grafana** para métricas
- **ELK Stack** para gestión de logs
- **Zipkin/Jaeger** para trazas distribuidas

### **CI/CD**
- **Jenkins/GitHub Actions** para pipelines
- **SonarQube** para análisis de código
- **Trivy** para escaneo de vulnerabilidades

## 👨‍💻 **Equipo de Desarrollo**

Este proyecto fue desarrollado por:

- **Juan David Colonia Aldana** - [GitHub](https://github.com/jdColonia/)
- **Esteban Gaviria Zambrano** - [GitHub](https://github.com/EstebanGZam)

## 🚀 **Características Implementadas**

### ✅ **Funcionalidades Core**
- Arquitectura de microservicios completa
- Autenticación y autorización JWT
- Gestión completa de catálogo de productos
- Sistema de pedidos con estado
- Procesamiento de pagos
- Gestión de envíos
- Sistema de favoritos

### ✅ **DevOps y Calidad**
- Metodología ágil (Kanban)
- Estrategias de branching (GitFlow)
- Infraestructura como código con Terraform
- Pipelines CI/CD automatizados
- Pruebas automatizadas (unitarias, integración, E2E)
- Análisis estático de código
- Escaneo de vulnerabilidades

### ✅ **Observabilidad**
- Monitoreo con Prometheus y Grafana
- Gestión centralizada de logs
- Trazas distribuidas
- Health checks y métricas de negocio
- Alertas automáticas

### ✅ **Seguridad**
- Gestión segura de secretos
- RBAC para control de acceso
- TLS para comunicaciones
- Escaneo continuo de vulnerabilidades

## 📚 **Documentación**

Para información detallada sobre metodologías, arquitectura y guías de operación, consulte el repositorio [`ecommerce-docs`](https://github.com/EcommerceCoZam/ecommerce-docs).

## 🏁 **Comenzando**

Para comenzar con el proyecto, siga estos pasos:

1. **Clonar los repositorios necesarios**
2. **Configurar la infraestructura** usando Terraform
3. **Desplegar los servicios** en Kubernetes
4. **Configurar el monitoreo** y observabilidad

Para instrucciones detalladas, consulte la documentación en cada repositorio específico.

---

*Desarrollado con ❤️ por el equipo EcommerceCoZam*
