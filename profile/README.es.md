<div align="center">

<br/>

```
 ███╗   ██╗ █████╗ ██╗   ██╗███╗   ██╗███████╗██╗  ██╗
 ████╗  ██║██╔══██╗╚██╗ ██╔╝████╗  ██║██╔════╝╚██╗██╔╝
 ██╔██╗ ██║███████║ ╚████╔╝ ██╔██╗ ██║█████╗   ╚███╔╝ 
 ██║╚██╗██║██╔══██║  ╚██╔╝  ██║╚██╗██║██╔══╝   ██╔██╗ 
 ██║ ╚████║██║  ██║   ██║   ██║ ╚████║███████╗██╔╝ ██╗
 ╚═╝  ╚═══╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝
```

**Local-first. Architecture-grade.**


[![Estado](https://img.shields.io/badge/estado-activo-22d3ee?style=flat-square)](https://github.com/naynex)
[![Foco](https://img.shields.io/badge/foco-fullstack%20%7C%20infra%20%7C%20IA-3b82f6?style=flat-square)](https://github.com/naynex)
[![Stack](https://img.shields.io/badge/stack-Go%20%7C%20Java%20%7C%20Python%20%7C%20TS%20%7C%20Kotlin-0a0f1e?style=flat-square&labelColor=1e293b)](https://github.com/naynex)

<br/>

> 🌐 [README in English](./README.md)

</div>

---

## ¿Qué es Naynex?

Naynex es un estudio de desarrollo de software que construye sistemas completos y listos para producción — desde la interfaz que toca el usuario hasta la infraestructura que nunca se detiene. Trabajamos con colegios, institutos y negocios que se toman la tecnología en serio: no solo digitalizando el caos existente, sino rediseñándolo con principios modernos.

Cubrimos toda la superficie del producto — frontend, backend, cloud y móvil — con una especialización deliberada en lo que corre por debajo: **sistemas concurrentes, arquitectura basada en eventos e IA como infraestructura**.

> *"La mayoría de los estudios construyen features. Nosotros construimos el sistema que hace posibles los features."*

---

## Principios fundamentales

```
  architecture-first    →   decisiones antes que código, contratos antes que implementación
  async por naturaleza  →   I/O no bloqueante, event-driven desde la base
  concurrencia explícita →  goroutines, thread pools, worker queues — nunca como ocurrencia
  performance como req. →   latencia y throughput son requisitos, no benchmarks opcionales
  IA como capa          →   inteligencia integrada al sistema, no pegada como demo
  local-first           →   tu infraestructura, tus datos, tu control
```

---

## Qué construimos

**Frontend** — interfaces que comunican con claridad y funcionan de forma consistente. Basadas en componentes, accesibles y diseñadas para evolucionar sin acumular deuda técnica.

**Backend** — donde ponemos más foco. APIs, workers, procesadores de eventos y lógica de dominio diseñados con arquitectura explícita, comportamiento observable y concurrencia como ciudadano de primera clase. No scaffoldeado — arquitecturado.

**Cloud e Infraestructura** — cargas de trabajo en contenedores, pipelines de CI/CD, brokers de mensajería e infraestructura como código. Sistemas reproducibles, auditables y aburridos de la mejor manera posible.

**Mobile** — aplicaciones Android nativas para clientes que necesitan una presencia móvil de primera clase junto a sus sistemas web.

---

## Stack tecnológico

| Capa | Tecnologías |
|---|---|
| **Frontend** | React · Next.js · Angular · TypeScript |
| **Backend** | Go · Java / Spring Boot · Python / FastAPI |
| **Concurrencia y Eventos** | goroutines · asyncio · Kafka · reactive streams |
| **Cloud y Serverless** | Python · TypeScript · Docker · CI/CD |
| **Mobile** | Kotlin / Android |
| **Datos** | PostgreSQL · Redis · vector stores |
| **Observabilidad** | logging estructurado · tracing distribuido · métricas |

> **Donde más profundizamos:** sistemas concurrentes, diseño basado en eventos y backends de alto rendimiento. Go para servicios sensibles al throughput, Java para sistemas con dominio complejo, Python para pipelines con IA integrada.

---

## Estándares de ingeniería

Decisiones deliberadas, no preferencias de estilo.

**Sobre arquitectura**
- La lógica de dominio siempre está aislada de la capa de transporte. Las rutas no son lógica de negocio.
- Async-first en cargas I/O-bound. Sync cuando el tradeoff es justificado y explícito.
- Explícito sobre implícito. Configuración como código. Sin magia, sin comportamiento oculto.

**Sobre concurrencia y performance**
- El estado compartido se identifica en tiempo de diseño, no se descubre en producción.
- Toda cola tiene capacidad acotada. El backpressure no es opcional.
- Las goroutines y workers async son baratos — diseña muchas unidades pequeñas de trabajo, no pocas grandes.
- Los presupuestos de latencia se definen antes de escribir una línea de código.

**Sobre eventos y mensajería**
- Comandos y eventos son cosas distintas. Se modelan de forma distinta.
- Los schemas de eventos son contratos. Se versionan como APIs.
- Los consumidores deben ser idempotentes. El broker va a reintentar.

**Sobre integración de IA**
- Los LLMs son I/O no determinístico — trátelos como servicios externos, con timeouts, reintentos y fallbacks.
- El prompt engineering es ingeniería. Los prompts se versionan, prueban y revisan.
- Los embeddings y la búsqueda vectorial son decisiones de infraestructura, no de modelos.

---

## Cómo trabajamos

```
Discovery  →  entender el problema real, no el enunciado
Diseño     →  docs de arquitectura y ADRs antes de implementar
Build      →  iterativo, testeado y observable desde el día uno
Operar     →  logs estructurados, runbooks y métricas — no conocimiento tribal
```

Equipos pequeños. Comunicación directa. Sin intermediarios entre el cliente y el ingeniero.

---
<div align="center">

*Construido en Perú. Diseñado para cualquier lugar.*

<sub>© Naynex · All systems running.</sub>

</div>