# Grupo Talenti — Manual de marca (extracción para desarrollo web)

Fuente: `MANUAL_DE_MARCA_TALENTI.pdf` (18 páginas, Adobe Illustrator, mayo 2025).
Sector: evaluación y selección de personal / recursos humanos, México.

---

## 1. Identidad verbal

### Tono de voz
| Atributo | Cómo se aplica |
|---|---|
| **Cercana** | Hablamos como expertos que están del lado del cliente. Sin tecnicismos innecesarios, pero con la autoridad que da la experiencia. |
| **Confiable** | Comunicamos con claridad, transparencia y profesionalismo. Somos aliados que dan resultados. |
| **Innovadora** | Siempre mirando hacia adelante: nuevas soluciones, tecnologías y procesos. |
| **Empática** | Entendemos a las personas detrás de las empresas. Escuchamos, adaptamos y resolvemos con sensibilidad humana. |
| **Positiva** | Nos enfocamos en las oportunidades, en el talento y en las soluciones, transmitiendo entusiasmo y compromiso. |

### Objetivos de negocio
1. Consolidar a Grupo Talenti como líder en soluciones de evaluación y selección de personal en México.
2. Mantenerse a la vanguardia tecnológica y metodológica en procesos de recursos humanos.
3. Ofrecer un servicio personalizado, eficaz y medible para cada cliente.
4. Contribuir al desarrollo profesional y humano de los candidatos, creando oportunidades reales de crecimiento.
5. Generar relaciones de largo plazo basadas en la confianza, los resultados y el valor compartido.

> No hay slogan fijo. El rediseño eliminó deliberadamente "WORKING FOR YOU" para que el logo hable por sí mismo y se adapte a distintos contextos. **No inventar un tagline en el sitio sin aprobación.**

---

## 2. Logo e isotipo

### Significado del símbolo
- **Check de verificación:** el diseño central recuerda a una paloma o "check", símbolo de validación, cumplimiento y confianza.
- **Figuras humanas en colaboración:** tres figuras en movimiento que forman un símbolo de conexión y trabajo en equipo — una red humana que colabora y acompaña.
- **"T" implícita:** la composición central sugiere sutilmente la letra "T" de Talenti.
- **Formas redondeadas:** transmiten modernidad, cercanía y humanidad; facilitan la adaptación a medios digitales y físicos.

Fórmula conceptual del manual: `T (talenti) + check (validación) + personal (figuras humanas)`.

### Versiones incluidas en el manual (página 9)
1. Logo a color sobre azul profundo (isotipo naranja + blanco, texto blanco).
2. Logo a color sobre blanco (isotipo naranja + azul, texto azul).
3. Logo monocromo blanco sobre naranja.
4. Logo monocromo blanco sobre azul profundo.

### Reglas de uso derivadas
- Composición **horizontal**: isotipo a la izquierda + lockup "GRUPO / Talenti" a la derecha.
- Jerarquía obligatoria: "GRUPO" en peso ligero y tamaño menor, "Talenti" en peso bold y mayor.
- Sobre fondos oscuros o saturados usar la versión monocroma blanca; nunca la versión a color con azul sobre azul.
- El manual insiste en la **adaptabilidad** como mejora clave frente al logo anterior: debe funcionar en tamaños pequeños. Para favicon y menús móviles usar solo el isotipo.
- Área de respeto sugerida (no especificada explícitamente en el PDF): mínimo el alto del punto naranja superior del isotipo por cada lado.

---

## 3. Paleta de colores

| Rol | Hex | Significado según el manual |
|---|---|---|
| Naranja principal | `#FF6600` | Energía, dinamismo, entusiasmo humano |
| Azul profundo (base) | `#0D1846` | Confianza, profesionalismo, estabilidad |
| Azul intenso | `#020871` | Variante de acento |
| Azul eléctrico | `#010B8E` | Variante de acento |
| Azul muy claro | `#EEF3F7` | Fondo suave / secciones alternas |
| Gris cálido claro | `#F2F2F0` | Fondo suave / tarjetas |
| Blanco | `#FFFFFF` | Limpieza, claridad, transparencia |

> El PDF imprime el blanco como `FFFFF` (cinco dígitos). Es una errata del manual: el valor correcto es `#FFFFFF`.

**Uso observado en las piezas:** el azul `#0D1846` domina como fondo, el naranja `#FF6600` funciona como acento y llamada a la acción (nunca como fondo de párrafos largos), y los claros `#EEF3F7` / `#F2F2F0` alternan secciones. Proporción aproximada 60 azul / 30 claro / 10 naranja.

**Accesibilidad:** `#FF6600` sobre blanco da ~3.0:1 de contraste — no cumple AA para texto pequeño. Usar naranja solo en texto grande (≥24px), iconos, o como fondo con texto blanco. Para enlaces en cuerpo de texto, usar azul `#010B8E`.

---

## 4. Tipografía

| Fuente | Uso en el manual | Pesos vistos |
|---|---|---|
| **Goldplay Alt** | Titulares y palabra "GRUPO" | Regular, Medium |
| **Campton** | Cuerpo de texto y palabra "Talenti" | Thin, Light, SemiBold |

Criterio: tipografía moderna, robusta y amigable que transmite claridad, profesionalismo y calidez. La diferencia de peso entre "GRUPO" y "Talenti" genera la jerarquía visual.

### Para web
Ambas son de pago (Goldplay Alt de Latinotype, Campton de Rene Bieder). Opciones:

1. **Con licencia web** (recomendado): comprar licencia webfont y servir `.woff2` propios.
2. **Alternativas gratuitas de Google Fonts** con estructura geométrica y terminaciones redondeadas similares:
   - Sustituto de Goldplay Alt → **Outfit** o **Poppins**
   - Sustituto de Campton → **Figtree** o **Montserrat**

Escala tipográfica sugerida (rem, base 16px): 3.5 / 2.5 / 2 / 1.5 / 1.125 / 1 / 0.875.

---

## 5. Recurso gráfico: patrón

El manual incluye un **patrón de repetición** construido con el isotipo en naranja y azul sobre blanco (página 9, franja inferior; también aparece en la papelería). Sirve como textura de fondo. En el sitio úsalo con opacidad baja (5–10%) en secciones de fondo azul o en cabeceras, nunca detrás de texto a tamaño de lectura.

Archivo: `assets/patron-talenti.png`.

---

## 6. Aplicaciones documentadas (páginas 10–18)

Papelería corporativa (folder, hoja membretada, tarjetas de presentación), playeras azul y naranja con el isotipo a gran escala y recortado por el borde, plumas, tazas, mochilas bicolor, libretas con liga naranja y gafete/credencial con lanyard.

**Lo que esto indica para el sitio:** el isotipo se usa con frecuencia **ampliado y recortado por el borde del lienzo** como elemento decorativo. Es un recurso directamente trasladable a hero sections y cabeceras de sección.

---

## 7. Rediseño: qué cambió y por qué (útil para el copy del sitio)

| Aspecto | Antes | Ahora |
|---|---|---|
| Diseño general | Estático y visualmente complejo | Moderno, limpio y dinámico |
| Símbolo | Figura humana literal dentro de la "i" | Figuras en colaboración formando un check: evaluación, validación y confianza |
| Tipografía | Problemas de legibilidad, combinación rígida | Clara, balanceada y adaptable a múltiples plataformas y tamaños |
| Slogan | "WORKING FOR YOU" (limitaba la identificación nacional) | Sin slogan fijo |
| Adaptabilidad | Difícil en formatos pequeños y fondos variados | Versátil en digital, impreso, redes y presentaciones |
| Mensaje visual | Representación literal de una persona | Metáfora de colaboración, comunidad, evaluación y calidad |

---

## 8. Recomendaciones para la página web

- **Hero:** fondo `#0D1846`, isotipo ampliado recortado al borde derecho con opacidad media, titular en blanco con una palabra clave en naranja, CTA naranja sólido con texto blanco.
- **Secciones:** alternar `#FFFFFF` / `#EEF3F7` para ritmo visual; una sección azul profundo cada 3–4 bloques como respiro.
- **Tarjetas de servicio:** fondo `#F2F2F0`, radio de borde generoso (16–24px) para coincidir con el lenguaje redondeado del isotipo, icono en naranja.
- **Botones:** radio completo o muy alto (pill), coherente con las cápsulas de la paleta del manual.
- **Sombras:** el manual usa sombras suaves y difusas en las cápsulas de color; replicar con `0 8px 24px rgba(13,24,70,.08)`.
- **Favicon / app icon:** isotipo sobre `#0D1846`.
- **Fotografía:** el manual no define estilo fotográfico. Sugerencia coherente con el tono: personas reales en entornos de trabajo, luz natural, sin stock excesivamente posado.

### Vacíos del manual a confirmar con el cliente
- Área de respeto y tamaño mínimo del logo (no especificados).
- Usos incorrectos del logo (no hay página de "no hacer").
- Versión vertical o apilada del logo (no existe en el manual).
- Estilo fotográfico e iconografía.
- Equivalencias CMYK / Pantone para impresión.
