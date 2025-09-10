# Auditoría de Sistemas
## Evaluación de Activos de Información en un Banco

### Instrucciones Generales

 Como auditor externo contratado por un banco, debe evaluar los activos de información, utilizando modelos de lenguaje avanzados ejecutados localmente. Este proceso incluye la generación automática de perfiles de riesgo, análisis de impactos, recomendaciones de mitigación alineadas con ISO 27001 y una interfaz intuitiva para la gestión de casos identificados.

Por tanto deberá:

1. **Crear su propio repositorio en GitHub** (fork o clon del repositorio base) y subir todo el código fuente mejorado.
2. Clonar y ejecutar el repositorio base proporcionado. 🔗 [URL GitHub](https://github.com/OscarJimenezFlores/CursoAuditoria/tree/main/AuditoriaRiesgos)
3. Modificar el sistema para incluir una funcionalidad de **inicio de sesión ficticio sin base de datos** y mejorar el motor de IA en el código.
4. Evaluar **5 activos de información** del entorno bancario (Lista Anexo 1).
5. Elaborar un **informe de auditoría**, según instrucciones del apartado "Entregable",<span style="color: green"> **este informe estará desarrollado en el propio README.md de su proyecto y EXPORTADO a PDF para ser entregado en el aula virtual.**</span>
---

## Entregable

Copie y pegue la siguiente estructura en su README.md para que al términar todo el informe de auditoría lo convierta en PDF y suba al aula virtual.

---
# Informe de Auditoría de Sistemas - Examen de la Unidad I

**Nombres y apellidos:**  
**Fecha:**  
**URL GitHub:**


## 1. Proyecto de Auditoría de Riesgos

### Login
- **Evidencia:**  
  [Captura del login]
- **Descripción:** (Breve explicación de cómo se implementó el inicio de sesión ficticio).  

### Motor de Inteligencia Artificial
- **Evidencia:**  
  [Captura de la sección del código fuente mejorado de IA que permite su funcionamiento]
- **Descripción:** (Breve explicación de la sección de código mejorado que hace posible el funcionamiento de la IA en el sistema).  

## 2. Hallazgos

### Activo 1: (título del activo)
- **Evidencia:** (Captura)
- **Condición:** (Situación encontrada en el activo)  
- **Recomendación:** (Acción correctiva o preventiva)  
- **Riesgo:** Probabilidad (Baja/Media/Alta)


### Activo 2: (título del activo)

### Activo 3: (título del activo)

### Activo 4: (título del activo)

### Activo 5: (título del activo)


---

## Anexo 1: Activos de información
| #  | Activo                                         | Tipo              |
|----|-----------------------------------------------|-------------------|
| 1  | Servidor de base de datos                               | Base de Datos     |
| 2  | API Transacciones                             | Servicio Web      |
| 3  | Aplicación Web de Banca                       | Aplicación        |
| 4  | Servidor de Correo                            | Infraestructura   |
| 5  | Firewall Perimetral                           | Seguridad         |
| 6  | Autenticación MFA                             | Seguridad         |
| 7  | Registros de Auditoría                        | Información       |
| 8  | Backup en NAS                                 | Almacenamiento    |
| 9  | Servidor DNS Interno                          | Red               |
| 10 | Plataforma de Pagos Móviles                   | Aplicación        |
| 11 | VPN Corporativa                               | Infraestructura   |
| 12 | Red de Cajeros Automáticos                    | Infraestructura   |
| 13 | Servidor FTP                                  | Red               |
| 14 | CRM Bancario                                  | Aplicación        |
| 15 | ERP Financiero                                | Aplicación        |
| 16 | Base de Datos Clientes                        | Información       |
| 17 | Logs de Seguridad                             | Información       |
| 18 | Servidor Web Apache                           | Infraestructura   |
| 19 | Consola de Gestión de Incidentes              | Seguridad         |
| 20 | Políticas de Seguridad Documentadas           | Documentación     |
| 21 | Módulo KYC (Know Your Customer)               | Aplicación        |
| 22 | Contraseñas de Usuarios                       | Información       |
| 23 | Dispositivo HSM                               | Seguridad         |
| 24 | Certificados Digitales SSL                    | Seguridad         |
| 25 | Panel de Administración de Usuarios           | Aplicación        |
| 26 | Red Wi-Fi Interna                             | Red               |
| 27 | Sistema de Control de Acceso Físico           | Infraestructura   |
| 28 | Sistema de Video Vigilancia                   | Infraestructura   |
| 29 | Bot de Atención al Cliente                    | Servicio Web      |
| 30 | Código Fuente del Core Bancario               | Información       |
| 31 | Tabla de Usuarios y Roles                     | Información       |
| 32 | Documentación Técnica                         | Documentación     |
| 33 | Manuales de Usuario                           | Documentación     |
| 34 | Script de Backups Automáticos                 | Seguridad         |
| 35 | Datos de Transacciones Diarias                | Información       |
| 36 | Herramienta SIEM                              | Seguridad         |
| 37 | Switches y Routers                            | Red               |
| 38 | Plan de Recuperación ante Desastres           | Documentación     |
| 39 | Contratos Digitales                           | Información Legal |
| 40 | Archivos de Configuración de Servidores       | Información       |
| 41 | Infraestructura en la Nube                    | Infraestructura   |
| 42 | Correo Electrónico Ejecutivo                  | Información       |
| 43 | Panel de Supervisión Financiera               | Aplicación        |
| 44 | App Móvil para Clientes                       | Aplicación        |
| 45 | Token de Acceso a APIs                        | Seguridad         |
| 46 | Base de Datos Histórica                       | Información       |
| 47 | Entorno de Desarrollo                         | Infraestructura   |
| 48 | Sistema de Alertas de Seguridad               | Seguridad         |
| 49 | Configuración del Cortafuegos                 | Seguridad         |
| 50 | Redundancia de Servidores                     | Infraestructura   |


## Anexo 2: Rúbrica de Evaluación

La nota final es la suma de todos los criterios (máx. 20 puntos).

| Criterio | 0 pts | 5 pts | Puntaje Máximo |
|----------|-------|-------|----------------|
| **Login** | No presenta evidencia o está incorrecto | Login ficticio completo, funcional y con evidencia clara | 5 |
| **IA Funcionando** | No presenta IA o está incorrecta | IA implementada, funcionando y con evidencia clara | 5 |
| **Evaluación de 5 Activos** | Menos de 5 activos evaluados o sin hallazgos válidos | 5 activos evaluados con hallazgos claros y evidencias | 5 |
| **Informe claro y completo** | Informe ausente, incompleto o poco entendible | Informe bien estructurado y completo según lo requerido | 5 |

