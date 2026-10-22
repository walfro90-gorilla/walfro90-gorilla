## Walfre Aguilar · AI Integration Engineer

Llevo IA a sistemas que ya funcionan: conecto LLMs con APIs, CRMs, ERPs y canales de mensajería, y los dejo en
producción con autenticación, manejo de errores, idempotencia y aprobación humana en las acciones delicadas.
Más de 10 años en software, 9 en backend. Fundador de [Gorilla Labs](https://gorillabs.dev), Ciudad Juárez, México.

*I build production LLM integrations (tool calling, RAG, voice, webhooks) in TypeScript and Python.*

### Proyectos públicos

| Proyecto | Qué demuestra | Stack |
|---|---|---|
| [**companero**](https://github.com/walfro90-gorilla/companero) · [demo](https://companero-ten.vercel.app) | RAG que responde solo con el manual de la empresa y valida cada cita; voz a texto y texto a voz; multiempresa con RLS. Recuperación 18/18, estrés 226/226 | Next.js, Vercel AI SDK, Supabase, Whisper, Azure AI Speech |
| [**pokedex-manager**](https://github.com/walfro90-gorilla/pokedex-manager) · [video](https://youtu.be/4EHL-OPYgPo) | Agente con tool calling escrito a mano (~100 líneas), servidor MCP, 3 LLMs con fallback, visión y evals | FastAPI, Next.js, Supabase (RLS), Docker |
| [**garita**](https://github.com/walfro90-gorilla/garita) | Flota de agentes que valida la Carta Porte 3.1; los datos personales se redactan antes de salir de México | Python, Google ADK, Vertex AI, Pydantic |
| [**codice**](https://github.com/walfro90-gorilla/codice) · [codice.mx](https://codice.mx) | Infraestructura cívica abierta: cada dato con su procedencia; el LLM propone y un humano decide | Python, FastAPI, Postgres, MCP, Next.js |
| [**bitcoiner**](https://github.com/walfro90-gorilla/bitcoiner) · [dashboard](https://bitcoiner-three.vercel.app) | Sistema orientado a eventos: WebSockets a 7 exchanges, leader election en Postgres, copiloto de IA con escritura gobernada | Node.js, Supabase Realtime, property-based testing |

### Productos propios en producción (código privado)

| Producto | Qué es | Logros |
|---|---|---|
| [**Ketzal OS**](https://ketzal.tours) | Back-office para agencias de viajes: ventas, abonos en un ledger append-only, recibos foliados, cobranza y marketplace con cobro en línea (Mercado Pago). Asistente que opera el sistema por tool calling, con confirmación humana en lo que mueve dinero | Operando con 2 agencias reales. Servidor MCP publicado en npm: [`ketzal-mcp`](https://www.npmjs.com/package/ketzal-mcp) |
| [**Estampida**](https://estampida.run) | SaaS multi-tenant de inscripción, pagos y check-in para carreras, con subdominio propio por organizador y pagos tipo marketplace (Mercado Pago Split) | En producción con dinero real. Primer cliente: Carrera Comic Fest (29 nov 2026, ~2,000 corredores) |

### Para clientes (código privado, recorrido bajo solicitud)

- **CRM comercial para logística cross-border:** ingesta por eventos desde web, WhatsApp, Messenger y correo
  (webhooks con firma verificada), asistente de ventas con RAG sobre pgvector e integración con GoHighLevel.
- **Middleware CRM ↔ ERP:** GoHighLevel → Odoo por webhooks, en Python sobre funciones serverless.
- **ClawBot / ORION:** SDR autónomo con calificación de leads por IA, máquina de estados y agenda por webhook.

### Stack

`TypeScript` `Python` `Node.js` `FastAPI` `Next.js` `PostgreSQL` `Supabase` `Anthropic` `OpenAI` `Gemini` `Groq`
`MCP` `RAG / pgvector` `Docker` `Vercel` `Azure AI Speech` `AWS` `GCP`

📫 [gorillabs.dev](https://gorillabs.dev) · walfre.am@gmail.com
