# Iconos — Nueva web Sofico (Propuesta A)

Set: **Phosphor Icons**, licencia **MIT** (archivo `LICENSE`).
Se pueden usar en la web del cliente sin pagar ni acreditar. La licencia se
conserva en el repositorio por buena práctica, no por obligación de crédito.

## Carpetas

- `linea/` — trazo (peso *regular*)
- `duotono/` — cuerpo + contorno (peso *duotone*): el cuerpo es el `<path>` que
  lleva `opacity="0.2"`. Para dos colores, se le pone `fill` propio y `opacity:1`.
- `solido/` — silueta llena (peso *fill*), para el icono blanco dentro de la pastilla

Todos son `viewBox="0 0 256 256"` con `fill="currentColor"`: heredan el color del CSS.

## Qué icono va en cada línea

### Cómo avanza tu trámite
| Paso | Icono |
|---|---|
| Nos escribes por WhatsApp | `whatsapp-logo` |
| Definimos tu tipo de empresa | `buildings` |
| Inicias con S/100 | `wallet` |
| Empresa lista para operar | `seal-check` |

### Por qué con nosotros
| Tarjeta | Icono |
|---|---|
| Todo incluido | `receipt` |
| Te acompañamos | `handshake` |
| Rápido y seguro | `shield-check` |
| Ocho años haciéndolo | `medal` |

### Todo esto ya está dentro de los S/600
| Ítem | Icono |
|---|---|
| Asesoría para elegir tu tipo de empresa | `chats` |
| Reserva de nombre en SUNARP | `signature` |
| Minuta y escritura pública | `scroll` |
| Derechos RENIEC e identificación biométrica | `fingerprint` |
| Derechos notariales e inscripción en SUNARP | `stamp` |
| Costo de subsanación cubierto | `shield-check` |
| Entrega de tus documentos | `folder-open` |
| Trámite del RUC y la Clave SOL | `key` |

### Para qué te sirve formalizarte
| Pastilla | Icono |
|---|---|
| Participar en licitaciones del Estado | `bank` |
| Proteger tu patrimonio personal | `shield-check` |
| Abrir mercados fuera del país | `globe-hemisphere-west` |
| Generar más confianza en tus clientes | `seal-check` |
| Acceder a productos financieros | `piggy-bank` |

Sobrantes por si cambia algún texto: `clock`, `users-three`.

## Colores de marca

| Token | Valor |
|---|---|
| Azul profundo | `#0A1B2E` |
| Azul eléctrico | `#1E4BE8` |
| Azul claro (sobre fondo oscuro) | `#4C7BFF` |
| Naranja | `#FF8A00` |
| Placa clara (opción C) | `#F4F1EA` |

Set completo de Phosphor (1512 iconos por peso), por si hace falta otro:
`npm i @phosphor-icons/core`
