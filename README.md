# Proyecto-SalonDeBelleza

# 💅 Nikté Salón — Sistema Integral de Gestión de Reservaciones

Plataforma web completa para la gestión de reservaciones, servicios, clientes y operación diaria de un salón de belleza. Desarrollada en equipo como Proyecto Integrador y desplegada en producción.

---

## 🌐 Demo en vivo

> 🔗 **[https](https://niktebeautytrc.me/)** — 

---

## 📌 Descripción

Nikté Salón digitaliza y automatiza la operación de un salón de belleza, sustituyendo agendas físicas y seguimiento telefónico por una plataforma centralizada accesible desde cualquier dispositivo.

El sistema permite gestionar reservaciones en tiempo real, controlar pagos, enviar notificaciones automáticas por correo y generar reportes operativos y financieros.

---

## ✨ Funcionalidades principales

- **Gestión de reservaciones** — Creación, reagendado y cancelación con validación de disponibilidad en tiempo real
- **Control de pagos** — Registro de anticipo y saldo restante con cálculo automático de totales
- **Flujo de estados automático** — `pendiente → apartada → en proceso → completada`, gestionado por triggers en base de datos
- **Cancelación automática nocturna** — Proceso programado que cancela reservaciones sin anticipo al vencer el plazo
- **Notificaciones por correo** — Confirmación de reservación, recordatorio de cita y aviso de cancelación
- **Reportes y estadísticas** — Ingresos por período, servicios más solicitados, historial de clientes
- **Control de acceso por roles** — Administrador, Recepcionista, Empleado y Cliente con permisos diferenciados
- **Agenda personal de empleados** — Vista individual de citas confirmadas de la semana

---

## 🛠️ Stack tecnológico

### Frontend
| Tecnología | Uso |
|---|---|
| Vue.js 3 + TypeScript | Framework principal de la interfaz web |
| Tailwind CSS v3 | Estilos y diseño responsivo |
| Pinia | Gestión de estado global |

### Backend
| Tecnología | Uso |
|---|---|
| Laravel 11 (PHP 8.2+) | API REST, lógica de negocio |
| Laravel Sanctum | Autenticación por tokens Bearer |
| MySQL 8.0 | Base de datos relacional |

### Infraestructura
| Tecnología | Uso |
|---|---|
| Digital Ocean (Droplet) | Servidor de producción (Ubuntu + Nginx) |
| Coudfare |
| NameCheap | Dominio|
| Resend / API de correo | Notificaciones automáticas por email |

---

---

## 📋 Estado del proyecto

| Módulo | Estado |
|---|---|
| Autenticación y roles       | ✅ Completado |
| Gestión de reservaciones    | ✅ Completado |
| Notificaciones por correo   | ✅ Completado |
| Cancelación automática      | ✅ Completado |
| Reportes y estadísticas     | ✅ Completado |
| App móvil Android           | ✅ Completado |

> El sistema está actualmente en **fase de pruebas en producción**.

---

## 📄 Documentación

El proyecto fue desarrollado siguiendo el estándar **ISO/IEC/IEEE 29148:2018** para especificación de requisitos de software, incluyendo estimación por Puntos de Función (312 AFP) y Puntos de Caso de Uso (273 UCP).
