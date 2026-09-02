<div align="center">
  <h1>MART Automations</h1>
  <h3>Automatizamos procesos de negocio con IA. Panamá 🇵🇦</h3>
  <p><i>Optimizar antes de automatizar. Si el proceso está roto, automatizarlo solo lo rompe más rápido.</i></p>
</div>

---

### Qué hacemos

Construimos agentes de IA que trabajan dentro de la operación real de una empresa: leen sus
documentos, consultan sus herramientas, preparan sus papeles y reportan lo que necesita atención
sin que nadie se lo pida.

No hacemos demos. Lo que entregamos corre en producción, con datos reales, y alguien lo usa todos
los días para trabajar.

### Cómo trabajamos

Tres reglas que gobiernan todo lo que construimos:

- **Toda escritura en un sistema del cliente necesita aprobación de una persona**, y queda
  registrada separando quién ejecutó (el agente) de quién autorizó (la persona, su canal y la
  hora). Un agente que no puede responder quién movió un dato no es auditable.
- **Los datos operativos nunca viven en la memoria del agente.** Inventario, precios y saldos se
  leen de la fuente conectada en el momento. Un precio recordado es un precio viejo.
- **Primero lo nativo.** Antes de escribir código propio revisamos si el framework ya lo trae. La
  única excepción legítima es la seguridad.

### Cómo construimos

Cada agente que operamos nace de **la misma plantilla**, y de ahí salen tanto el asistente interno
de una empresa como el personal de una persona. Lo que cambia entre uno y otro no es el código: es
el contexto de quien lo usa, que vive en un repositorio propio, privado, y **que le transferimos al
cliente cuando lo pida**. La portabilidad es verificable, no una promesa.

Esa plantilla trae de serie tres cosas que normalmente no vienen en un agente:

- **Traza de autorización.** Cada escritura registra quién ejecutó y quién autorizó, con su canal y
  su hora, y una aprobación autoriza una sola escritura: un reintento no duplica un movimiento.
- **Auditoría de lo que hizo.** Se puede revisar cualquier trabajo contra lo que se pidió, con
  evidencia clasificada en verificada, parcial y pendiente. Que un proceso termine sin error no
  cuenta como verificación: los efectos externos se comprueban volviéndolos a leer.
- **Un bucle de mejora con frenos.** El agente recoge señal de calidad y propone cambios, pero nunca
  los aplica solo, nunca sin que una persona los apruebe, y nunca puede proponer quitar una
  aprobación o un control. Si la única forma de ir más rápido es quitar un freno, es que no se puede
  ir más rápido.

### Lo que ofrecemos

| | Para quién |
|---|---|
| **Agentes gestionados** | Empresas que quieren un asistente operativo propio, conectado a sus herramientas y mantenido por nosotros |
| **Automatización a la medida** | Un problema específico y acotado, con precio cerrado y un repositorio por solución |
| **MART Web Express** | Negocios sin web, o con una web que ya no trabaja para ellos |
| **Capacitación en IA** | Equipos que prefieren aprender a usarla ellos mismos |

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

Nuestros repositorios son privados: contienen la operación de nuestros clientes y esa
operación no es nuestra para publicarla.

### Hablemos

[![Sitio](https://img.shields.io/badge/martautomations.com-0A66C2?style=flat&logo=googlechrome&logoColor=white)](https://martautomations.com)
[![Email](https://img.shields.io/badge/systems@martautomations.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:systems@martautomations.com)
