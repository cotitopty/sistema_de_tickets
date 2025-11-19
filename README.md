# 🎫 Implementación de Sistema de Tickets con GLPI

Proyecto de implementación y configuración de un sistema completo de gestión de tickets (IT Service Management) utilizando GLPI para una empresa.

---

## 📋 Descripción del Proyecto

Este proyecto consistió en la implementación integral de **GLPI (Gestión Libre de Parque Informático)** como solución de Help Desk y gestión de activos TI. El sistema fue configurado para centralizar la administración de tickets de soporte técnico, gestión de incidentes y seguimiento de activos informáticos.

**Duración del Proyecto:** 3 meses  
**Usuarios Activos:** 150+  
**Tickets Procesados:** 500+ mensuales

---

## 🎯 Objetivos Alcanzados

✅ Centralizar todos los tickets de soporte en una única plataforma  
✅ Reducir tiempo de respuesta de incidentes en 40%  
✅ Mejorar trazabilidad y documentación de incidentes  
✅ Implementar flujos de trabajo automáticos  
✅ Establecer base de datos de activos informáticos  
✅ Generar reportes de KPI y SLA  
✅ Integración con correo electrónico para notificaciones automáticas  

---

## 🛠️ Tecnologías Utilizadas

| Categoría | Tecnología |
|-----------|-----------|
| **Plataforma** | GLPI v10.0 |
| **Base de Datos** | MySQL 8.0 |
| **Servidor Web** | Apache 2.4 |
| **Sistema Operativo** | Linux (Ubuntu 20.04 LTS) |
| **Autenticación** | LDAP / Active Directory |
| **Email** | SMTP Integration |
| **Backups** | Veeam Backup & Replication |
| **Monitoreo** | NAGIOS |

---

## 📦 Características Implementadas

### 1. **Gestión de Tickets**
- Creación y seguimiento de tickets  
- Categorización automática  
- Asignación inteligente a técnicos  
- Estados: Nuevo, Asignado, En Progreso, Resuelto, Cerrado  
- Prioridades: Crítica, Alta, Media, Baja  
- SLA configurados  

### 2. **Automatización de Flujos**
- Asignación automática por categoría  
- Escalamiento automático por SLA  
- Notificaciones por email  
- Cierre automático por inactividad  

### 3. **Gestión de Activos**
- Inventario completo de equipos  
- Control de garantía y mantenimiento  
- Historial de cada activo  
- Ubicación física por departamento  

### 4. **Base de Conocimiento**
- Wiki interna  
- Artículos FAQ por categoría  
- Búsqueda integrada  
- Reducción de consultas repetitivas  

### 5. **Reportes y Análisis**
- Dashboard con KPI  
- Tickets por técnico/categoría  
- Análisis MTTR  
- Satisfacción de usuarios  
- Tendencias y repetitividad  

### 6. **Integraciones**
- **LDAP/AD:** Gestión centralizada de usuarios  
- **Email:** Tickets creados por correo  
- **NAGIOS:** Alertas automáticas  
- **SQL:** Consultas personalizadas  

---

## 📊 Estructura de Datos Configurada

### Categorías de Tickets
- Acceso a Sistemas  
- Hardware / Periféricos  
- Software / Licencias  
- Conectividad de Red  
- Correo Electrónico  
- Impresoras  
- Otros  

### Grupos de Técnicos
- Soporte Nivel 1 (Help Desk)  
- Soporte Nivel 2 (Especialistas)  
- Administradores de Sistemas  
- Equipo de Redes  

### Niveles de SLA

| Prioridad | Tiempo Respuesta | Tiempo Resolución |
|-----------|------------------|-------------------|
| **Crítica** | 15 min | 2 horas |
| **Alta** | 1 hora | 8 horas |
| **Media** | 4 horas | 24 horas |
| **Baja** | 8 horas | 48 horas |

---

## 📈 Resultados y Métricas

### Antes de la Implementación
- ❌ Tickets administrados en múltiples archivos Excel  
- ❌ Tiempo de respuesta promedio: **8 horas**  
- ❌ Documentación desorganizada  
- ❌ Sin trazabilidad ni auditoría de cambios  

### Después de la Implementación
- ✅ Centralización completa en GLPI  
- ✅ Tiempo de respuesta mejorado a **45 minutos**  
- ✅ Base de conocimiento funcional y alimentada  
- ✅ Auditoría, trazabilidad y control total  
- ✅ **92%** de satisfacción de usuarios  
- ✅ Reducción del **35% de tickets repetitivos**  

---

## 📚 Documentación Incluida

### Archivos Incluidos en el Repositorio

