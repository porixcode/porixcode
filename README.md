# Carlos Andrés Poris Díaz

**Estudiante de Ingeniería de Software (graduación esperada 2027) · Desarrollador Full-Stack (PHP · JavaScript/TypeScript · Python)**
Villavicencio, Colombia · porixcode@gmail.com · [LinkedIn](https://linkedin.com/in/porixcode)

Desarrollo sistemas de gestión, aplicaciones web y móviles y herramientas de automatización, y también
participo en su despliegue y operación (Linux, Docker, bases de datos, redes). Trabajo con desarrollo
dirigido por especificaciones y con agentes de IA como apoyo en el flujo de desarrollo.

---

## Stack

| Área | Tecnologías |
|---|---|
| Lenguajes | PHP · JavaScript / TypeScript · Python · SQL · Java (formación académica) |
| Frontend / Web | React · Next.js · Tailwind · Materialize |
| Backend / API | NestJS · FastAPI · Prisma |
| Móvil | React Native · Expo · PWA (offline-first) |
| Bases de datos | MariaDB / MySQL · PostgreSQL · PDO / mysqli |
| Servidor / DevOps | Docker · Docker Compose · Nginx · PHP-FPM · Caddy · Linux · Git |
| Automatización | Playwright · paramiko · Bash · TCL/Expect |

---

## Proyectos

### SMIT — gestión operativa para un ISP (caso de estudio, código privado)
Sistema en **PHP 7/8 + MariaDB (PDO con sentencias preparadas)** sobre **Docker (PHP-FPM + Nginx)**.
Módulos de clientes residenciales y corporativos, inventario de equipos, helpdesk, cronograma de
instalaciones y monitoreo. Integración con MikroTik por API RouterOS para activar y suspender servicio;
generación de contratos (HTML2PDF) y exportes a Excel (PhpSpreadsheet). Desarrollado y mantenido
en CSM SAS.

### kafetu.sigc — sistema de gestión para cafetería de especialidad
Monorepo TypeScript: API **NestJS + Prisma**, Admin Web **React**, **POS móvil en Expo/React Native**.
Motor de costeo con 39 pruebas automatizadas. Documentación de soporte: acta de proyecto, EDT,
requisitos con matriz de trazabilidad y ADRs.

### girou — automatización de reportes de mantenimiento
**Python + FastAPI + Playwright**: procesa PDFs de órdenes de trabajo y envía los registros a un
formulario web de forma automática; incluye capa web multiusuario. [Repo](https://github.com/porixcode/girou).

### dataparse — CLI de transformación de datos
**Python** con pruebas en **pytest**. [Repo](https://github.com/porixcode/dataparse).

### kafetu.store — e-commerce
Tienda en línea en **Next.js + React + TypeScript + Tailwind** (código privado).

### porix.cloud — plataforma self-hosted
**Docker Compose + Caddy**, WireGuard, MediaMTX, RustDesk. Despliegue y operación de la infraestructura.

---

## Experiencia

- **CSM SAS** (2020–2026) — Desarrollador Full-Stack · Líder Técnico de Infraestructura. Desarrollo y
  mantenimiento de **SMIT** y del sitio/portal **csmeta.com.co** (PHP con arquitectura MVC + PWA).
  Herramientas de automatización **OPCheck** (TCL/Expect, diagnóstico óptico en OLT Huawei) y
  **VALIDATE-NODES** (Python, validación de nodos MikroTik). Entrega formal a la Dirección de
  Operaciones con acta de alcance y 9 runbooks.
- **Independiente / PORIX** (2026–presente) — Desarrollo full-stack: proyectos propios (kafetu.sigc,
  kafetu.store) y proyectos para clientes (girou, mimisionero, evecontrol).
- **SCM Ltda** (2014–2020) — Especialista en Operaciones de Red y NOC. Diseño e implementación del
  modelo operativo del NOC: monitoreo continuo, escalamiento y respuesta a incidentes. Arquitectura de
  red híbrida (FTTH y enlaces PtP/PtMP) y seguimiento de SLAs y KPIs. Coordinación y mentoría del
  personal técnico; automatización de tareas repetitivas con scripts.

---

## Metodología de trabajo

Requisitos trazables (matriz requisito ↔ módulo ↔ prueba), decisiones de arquitectura documentadas (ADR)
y archivos de contexto para agentes de IA (`AGENTS.md` / `CLAUDE.md`) que facilitan retomar un proyecto.
Proyectos contenerizados con Docker.

---

*El código de proyectos de terceros o del empleador no se publica por confidencialidad; se describe
como caso de estudio.*
