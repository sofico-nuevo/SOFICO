# Web SOFICO

Sitio de **CONSULTORA SOFICO S.A.C.** (RUC 20602503756).
Reemplaza al sitio actual en WordPress: https://www.sofico.pe

Paquete contratado: Diseño + Autonomía (S/900). Incluye panel de edición y capacitación,
para que el contenido lo cambie el cliente sin tocar código.

## Cómo se trabaja en este repositorio

El repositorio pertenece a la cuenta del cliente. El desarrollo entra por colaborador.

1. Los archivos se escriben en la carpeta local `sofico-web/SOFICO`.
2. Se revisan los cambios en GitHub Desktop.
3. Commit a `main` y Push a `origin`.
4. Cloudflare Pages toma cada push y publica automáticamente (se conecta en la fase de entrega).

No se suben claves, tokens ni credenciales. Todo eso va en variables de entorno de Cloudflare.

## Identidad de marca

Sistema "SOFICO · Estudio Notable", aprobado por el cliente.

| Token | Valor |
|---|---|
| Azul profundo | `#0A1B2E` |
| Azul eléctrico | `#1E4BE8` |
| Naranja premium | `#FF8A00` |
| Tipografía | Satoshi |

Archivos en `marca/`:

| Archivo | Uso |
|---|---|
| `sofico-isotipo.svg` | Isotipo a color con degradados. Uso general en web. |
| `sofico-isotipo-mono.svg` | Isotipo de una sola tinta. Toma el color del contexto con `currentColor`: blanco sobre marino, marino sobre claro. |
| `sofico-isotipo-1024.png` | Fondo transparente. Para redes y usos que no aceptan SVG. |
| `sofico-isotipo-512.png` | Fondo transparente. Para favicon y miniaturas. |

El cliente no conserva el archivo original del logo. El isotipo se reconstruyó en vector
trazando la mitad naranja de la lámina de marca y rotándola 180 grados para generar la azul,
que es la construcción real del símbolo. Si aparece el original, se reemplaza.

## Contenido y datos reales del negocio

Estos son los datos vigentes. No inventar cifras, casos ni testimonios.

- Oferta central: constitución de empresa, pago único de S/600, se empieza con S/100.
- Plazo del trámite: máximo 15 días hábiles.
- Trayectoria: más de 8 años, +3,500 empresas constituidas, +4,000 emprendedores asesorados.
- Teléfono y WhatsApp: 913 926 338 (`wa.link/427wi0`)
- Correo: `informes@estudiosofico.com`
- Dirección: Av. Aviación 2468 int. 402, San Borja, Lima
- Aviso legal obligatorio en el pie: "Empresa privada de asesoría empresarial. No estamos afiliados a SUNAT, SUNARP ni a ninguna entidad gubernamental."
