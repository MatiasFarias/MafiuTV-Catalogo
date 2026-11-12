<p align="center"><img src="logos/mafiutv.png" alt="MafiuTV" width="320" /></p>

# MafiuTV · Catálogo de canales

Lista de canales que usa la app **MafiuTV** (TV abierta chilena, señales regionales, internacionales y radios para Android TV, celulares y tablets), con el estado de cada señal.

La app incluye una copia del catálogo y, al abrirse, revisa si aquí hay una versión más nueva. Así, cuando un canal cambia su señal, la corrección llega sin reinstalar la app.

## Contenido

| Archivo | Para qué sirve |
|---|---|
| `catalogo.json` | Canales, secciones y fuentes de cada señal. |
| `catalogo.json.sig` | Firma del catálogo. La app solo acepta un catálogo cuya firma corresponda a la clave del autor; si el archivo se modifica sin esa clave, la app lo ignora y sigue con el que tiene. |
| `logos/` | Logos de los canales (`<id>.png`) y el de MafiuTV (`mafiutv.png`). |
| `estado.json` | Último resultado conocido de cada fuente. |
| `.github/workflows/estado.yml` | Verificación diaria (y a pedido) desde GitHub Actions. Solo actualiza `estado.json` y este README; no puede cambiar el catálogo, porque no tiene la clave de firma. |

Las señales pertenecen a sus emisores. Este catálogo solo apunta a sus transmisiones públicas y gratuitas en vivo; no aloja ni retransmite contenido.

## Estado de los canales

GitHub Actions (servidores en EE. UU.) verifica todos los días cerca de las 09:00 de Chile con el workflow *Estado de los canales*, que también se puede ejecutar a pedido. La verificación desde Chile se hace a pedido. Muchas señales chilenas solo se pueden ver desde Chile, así que:

- Una verificación **desde Chile** actualiza todas las señales.
- Una verificación **desde GitHub Actions** solo actualiza las señales que pudo confirmar funcionando. Las demás conservan su último estado guardado, con la fecha y el lugar desde donde se verificaron.

Las correcciones de fuentes se publican como un catálogo nuevo firmado; no las hace el workflow.

🟢 Funciona · 🟡 Funciona con una fuente de respaldo · 🔴 Caída · ⚪ Sin verificar

<!-- estado:inicio -->
**Catálogo versión 5** · 77 señales · 🟢 77 · 🟡 0 · 🔴 0 · ⚪ 0

Última verificación: 12-11-2026 17:00 (hora de Chile) desde GitHub Actions (EE. UU.).

### Nacional

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 1 | Canal 13 | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 2 | Mega | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 3 | Chilevisión | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 4 | TVN | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 5 | T13 En Vivo | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 6 | Meganoticias Ahora | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 7 | CHV Noticias | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 8 | 24 Play | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |

### Más Chile

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 10 | NTV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 11 | TV Senado | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 12 | La Red | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 13 | TV+ | 🟢 Funciona | 10-11-2026 23:24 · GitHub Actions (EE. UU.) | intermitente |
| 14 | TVN 3 | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 15 | TV Chile | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 16 | Bío Bío TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 17 | UChile TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 18 | Santiago TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 19 | UCV TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |

### Regionales

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 20 | Iquique TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 21 | Antofagasta TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 22 | Holvoet TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 23 | Thema TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 24 | TVR | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 25 | VTV Aconcagua | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 26 | Canal 2 San Antonio | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 27 | UTalca TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 28 | Contivisión | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 29 | Canal 9 Bío-Bío | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 30 | TVU | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 31 | TV UCT | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 32 | Teleangol | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 33 | Décima TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 34 | Canal 2 Quellón | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 35 | Santa María TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 36 | ITV Patagonia | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 37 | Pingüino TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |

### Internacional

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 100 | DW Español | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 101 | France 24 Español | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 102 | Canal 24 Horas | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 103 | TVE Internacional | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 104 | TV Pública | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 105 | TN | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 106 | teleSUR | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 107 | Señal Colombia | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 108 | Canal Once | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 109 | Canal 22 | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 110 | TV UNAM | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 111 | Ecuador TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 112 | Paraguay TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 113 | DW English | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 114 | France 24 English | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 115 | Al Jazeera English | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 116 | NHK World-Japan | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 117 | CBS News 24/7 | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 118 | Sky News | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 119 | Bloomberg TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 120 | Arirang TV | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |

### Radios

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 200 | Cooperativa | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 201 | Radio Bío-Bío | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 202 | ADN Radio | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 203 | Radio Agricultura | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 204 | Tele13 Radio | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 205 | Radio Pauta | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 206 | Radio Duna | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 207 | Radio Futuro | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 208 | Rock & Pop | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 209 | Radio Concierto | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 210 | Radio Pudahuel | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 211 | Radio Infinita | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 212 | Radio Carolina | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 213 | Radio Beethoven | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 214 | Radio U. de Chile | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 215 | Bío-Bío Concepción | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 216 | Radio Festival | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 217 | Radio Maray | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 218 | Radio Polar | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
| 219 | Radio Sol | 🟢 Funciona | 12-11-2026 17:00 · GitHub Actions (EE. UU.) |  |
<!-- estado:fin -->
