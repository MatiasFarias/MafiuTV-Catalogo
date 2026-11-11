# MafiuTV · Catálogo de canales

Lista de canales que usa la app **MafiuTV** (TV abierta chilena, señales regionales, internacionales y radios para Android TV, celulares y tablets), con el estado de cada señal.

La app incluye una copia del catálogo y, al abrirse, revisa si aquí hay una versión más nueva. Así, cuando un canal cambia su señal, la corrección llega sin reinstalar la app.

## Contenido

| Archivo | Para qué sirve |
|---|---|
| `catalogo.json` | Canales, secciones y fuentes de cada señal. |
| `catalogo.json.sig` | Firma del catálogo. La app solo acepta un catálogo cuya firma corresponda a la clave del autor; si el archivo se modifica sin esa clave, la app lo ignora y sigue con el que tiene. |
| `logos/` | Logos de los canales (`<id>.png`). |
| `estado.json` | Último resultado conocido de cada fuente. |
| `.github/workflows/estado.yml` | Verificación a pedido desde GitHub Actions. Solo actualiza `estado.json` y este README; no puede cambiar el catálogo, porque no tiene la clave de firma. |

Las señales pertenecen a sus emisores. Este catálogo solo apunta a sus transmisiones públicas y gratuitas en vivo; no aloja ni retransmite contenido.

## Estado de los canales

La verificación se hace a pedido, no de forma automática: desde Chile, o desde GitHub Actions (servidores en EE. UU.) con el workflow *Estado de los canales*. Muchas señales chilenas solo se pueden ver desde Chile, así que:

- Una verificación **desde Chile** actualiza todas las señales.
- Una verificación **desde GitHub Actions** solo actualiza las señales que pudo confirmar funcionando. Las demás conservan su último estado guardado, con la fecha y el lugar desde donde se verificaron.

Las correcciones de fuentes se publican como un catálogo nuevo firmado; no las hace el workflow.

🟢 Funciona · 🟡 Funciona con una fuente de respaldo · 🔴 Caída · ⚪ Sin verificar

<!-- estado:inicio -->
**Catálogo versión 5** · 77 señales · 🟢 77 · 🟡 0 · 🔴 0 · ⚪ 0

Última verificación: 10-11-2026 23:05 (hora de Chile) desde Chile.

### Nacional

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 1 | Canal 13 | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 2 | Mega | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 3 | Chilevisión | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 4 | TVN | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 5 | T13 En Vivo | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 6 | Meganoticias Ahora | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 7 | CHV Noticias | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 8 | 24 Play | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |

### Más Chile

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 10 | NTV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 11 | TV Senado | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 12 | La Red | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 13 | TV+ | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 14 | TVN 3 | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 15 | TV Chile | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 16 | Bío Bío TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 17 | UChile TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 18 | Santiago TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 19 | UCV TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |

### Regionales

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 20 | Iquique TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 21 | Antofagasta TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 22 | Holvoet TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 23 | Thema TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 24 | TVR | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 25 | VTV Aconcagua | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 26 | Canal 2 San Antonio | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 27 | UTalca TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 28 | Contivisión | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 29 | Canal 9 Bío-Bío | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 30 | TVU | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 31 | TV UCT | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 32 | Teleangol | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 33 | Décima TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 34 | Canal 2 Quellón | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 35 | Santa María TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 36 | ITV Patagonia | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 37 | Pingüino TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |

### Internacional

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 100 | DW Español | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 101 | France 24 Español | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 102 | Canal 24 Horas | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 103 | TVE Internacional | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 104 | TV Pública | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 105 | TN | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 106 | teleSUR | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 107 | Señal Colombia | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 108 | Canal Once | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 109 | Canal 22 | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 110 | TV UNAM | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 111 | Ecuador TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 112 | Paraguay TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 113 | DW English | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 114 | France 24 English | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 115 | Al Jazeera English | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 116 | NHK World-Japan | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 117 | CBS News 24/7 | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 118 | Sky News | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 119 | Bloomberg TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 120 | Arirang TV | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |

### Radios

| N.º | Canal | Estado | Última verificación | Detalle |
|---:|---|---|---|---|
| 200 | Cooperativa | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 201 | Radio Bío-Bío | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 202 | ADN Radio | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 203 | Radio Agricultura | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 204 | Tele13 Radio | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 205 | Radio Pauta | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 206 | Radio Duna | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 207 | Radio Futuro | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 208 | Rock & Pop | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 209 | Radio Concierto | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 210 | Radio Pudahuel | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 211 | Radio Infinita | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 212 | Radio Carolina | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 213 | Radio Beethoven | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 214 | Radio U. de Chile | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 215 | Bío-Bío Concepción | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 216 | Radio Festival | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 217 | Radio Maray | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 218 | Radio Polar | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
| 219 | Radio Sol | 🟢 Funciona | 10-11-2026 23:05 · Chile |  |
<!-- estado:fin -->
