# 📋 PROJECT KNOWLEDGE — Fundación Corralco Malalcahuello
> Documento de referencia para Lovable. Usar en todas las decisiones de diseño, contenido y desarrollo.

---

## 🏔️ IDENTIDAD DE LA FUNDACIÓN

| Campo | Detalle |
|---|---|
| **Nombre oficial** | Fundación Corralco Malalcahuello |
| **RUT** | 65.162.886-5 |
| **Fundada** | 2007 |
| **Director** | Jimmy Ackerson |
| **Misión** | Enseñar a esquiar a niños de educación básica de La Araucanía a través del programa "Esquí para Todos" |
| **Escuela beneficiada** | Escuela Ramón Ramírez, Malalcahuello, La Araucanía, Chile |
| **Niños impactados** | 120+ por temporada |
| **Email** | fundacion@corralco.com |
| **Instagram** | @fundacion_corralco |

---

## 🤝 RELACIÓN CON CORRALCO RESORT

- La fundación es una entidad **LEGALMENTE SEPARADA** del resort Corralco
- Corralco resort apoya donando: **skis, transporte, tickets de ski y alimentación** para los niños
- **NO mezclar** la marca comercial del resort con la identidad de la fundación en el sitio
- La fundación tiene su propia identidad visual, dominio y operación independiente

---

## 🎨 IDENTIDAD VISUAL

- **Color primario:** Azul marino oscuro (referencia: sitio actual https://descubre.corralco.com/escuela)
- **Color secundario:** Blanco nieve
- **Acento:** Celeste/hielo
- **Estilo:** Cálido, inspirador, causa social — NO corporativo
- **Tipografía:** Limpia y moderna, legible
- **Imágenes:** Fotografías reales de niños esquiando y montaña (assets disponibles)
- **Logo:** Archivo local disponible para subir

---

## 🌐 IDIOMA Y AUDIENCIA

- **Idioma:** Solo español
- **Audiencia primaria:** Empresas y personas en Chile que quieran colaborar o asistir al evento
- **Audiencia secundaria:** Voluntarios y colaboradores potenciales

---

## 📁 ASSETS DISPONIBLES

| Asset | Estado |
|---|---|
| Logo de la fundación | ✅ Archivo local — subir a Lovable |
| Fotos de niños y eventos | ✅ Archivos locales — subir a Lovable |
| Video YouTube principal | ✅ https://www.youtube.com/watch?v=KDAfdLm5qH8 |
| Logos de sponsors | ❌ No disponibles aún |

---

## 🏗️ ESTRUCTURA DEL SITIO

### Navegación principal (5 páginas):
1. **Inicio** — Página principal con hero, misión e impacto
2. **Nuestra Fundación** — Historia, programa y valores
3. **Evento 3 de Junio** — Detalles del evento con compra de tickets
4. **Colabora** — Donaciones y voluntariado
5. **Admin** — Panel CRM protegido con contraseña (solo uso interno)

---

## 🏠 PÁGINA 1 — INICIO

- **Hero:** "Abrimos Caminos, Despertamos Talentos" con fondo de montaña/nieve
- **CTA principal:** Botón "Conoce Nuestro Evento" → página Evento 3 de Junio
- **Resumen misión:** Fundada 2007, 120+ niños, Escuela Ramón Ramírez
- **Impacto en números:** 120+ niños / 18+ años / 1 escuela transformada
- **Video embed:** https://www.youtube.com/watch?v=KDAfdLm5qH8
- **Instagram:** Embed o link a @fundacion_corralco
- **Footer:** Datos de transferencia bancaria + email

---

## 🏔️ PÁGINA 2 — NUESTRA FUNDACIÓN

- Historia: fundada 2007 con el sueño de abrir caminos a través del esquí
- Programa "Esquí para Todos": más que deporte, una aventura de crecimiento personal
- **Beneficios del programa:**
  - Mejora habilidades físicas y emocionales
  - Fomenta autoestima, compromiso y sentido de pertenencia
  - Alumnos destacados son becados en clubes competitivos
  - Crea vocación profesional en deporte y turismo
- **Equipamiento necesario** (campaña de donación):
  - Parkas térmicas e impermeables
  - Pantalones de nieve
  - Casco
  - Antiparras
  - Guantes

---

## 🎉 PÁGINA 3 — EVENTO 3 DE JUNIO

| Campo | Detalle |
|---|---|
| **Nombre del evento** | Noche por La Araucanía *(o el nombre oficial que se confirme)* |
| **Formato** | After office + Show de comedia + Rifa + Remate/Subasta |
| **Fecha** | Martes 3 de junio de 2025 |
| **Lugar** | Mall Sport, Santiago, Chile |
| **Idioma** | Español |

### Tickets:
| Tipo | Precio CLP |
|---|---|
| Entrada General | $10.000 |

### Elementos de la página:
- Countdown timer hasta el 3 de junio
- Descripción del formato del evento (after office, comedia, rifa, remate)
- Formulario de compra: nombre, email, teléfono, cantidad de tickets
- Botón de pago: **"Pagar con WebPay"** (placeholder por ahora — integración futura)
- Sección de sponsors con logos (placeholders)
- Mapa o dirección de Mall Sport Santiago

---

## 💙 PÁGINA 4 — COLABORA

### Sección 1 — Donación por transferencia:
- Banco: Banco de Chile
- Cuenta Corriente N°: 8002958700
- Titular: Fundación Corralco Malalcahuello
- RUT: 65.162.886-5
- Email comprobante: fundacion@corralco.com

### Sección 2 — Voluntariado:
Formulario con campos:
- Nombre completo
- Teléfono / WhatsApp
- Email
- Área de interés: Deporte / Arte / Educación / Logística
- Disponibilidad
- Habilidades / Propuestas
- Botón: "Quiero Participar"

---

## 🔐 PÁGINA 5 — ADMIN (CRM Interno)

- **Acceso:** Protegido con contraseña
- **Usuarios:** 1 usuario base / hasta 5 si el plan lo permite
- **Base de datos:** Supabase

### Módulo 1 — Contactos:
| Campo | Tipo |
|---|---|
| Nombre | Texto |
| Email | Email |
| Teléfono | Texto |
| Tipo | Persona / Empresa |
| Monto donado | Número (CLP) |
| Año | Número |
| Notas | Texto largo |

Funciones: agregar / editar / eliminar / buscar / filtrar por año y tipo

### Módulo 2 — Venta de Tickets:
| Campo | Tipo |
|---|---|
| Nombre comprador | Texto |
| Email | Email |
| Teléfono | Texto |
| Tipo de ticket | Selector |
| Cantidad | Número |
| Monto total | Número (CLP) |
| Estado de pago | Pendiente / Confirmado / Cancelado |
| Año del evento | Número |

Funciones: agregar / editar / eliminar + **totales al tope** (tickets vendidos, recaudación total)

### Módulo 3 — Empresas y Sponsors:
| Campo | Tipo |
|---|---|
| Nombre empresa | Texto |
| Persona de contacto | Texto |
| Email | Email |
| Teléfono | Texto |
| Nivel de auspicio | Oro / Plata / Bronce / Especie |
| Monto comprometido | Número (CLP) |
| Monto pagado | Número (CLP) |
| Año | Número |
| Notas | Texto largo |

Funciones: agregar / editar / eliminar / filtrar por año y nivel

---

## 💳 PAGOS

- **Plataforma:** WebPay Plus (Transbank Chile)
- **Estado actual:** Placeholder — botón visible pero sin funcionalidad
- **Integración:** A desarrollar en fase posterior con Claude
- **Moneda:** CLP (pesos chilenos)
- **Merchant RUT:** 65.162.886-5

---

## 📌 NOTAS TÉCNICAS

- Mobile responsive obligatorio
- Formularios deben guardar datos en Supabase
- Deploy en Vercel (conectado desde Lovable)
- No incluir sistema de login público — solo admin interno
- Incluir todo el contenido del sitio actual (nada excluido)

---

## ✅ PRIORIDADES DE DESARROLLO

1. Página principal + Evento 3 de junio ← **urgente, evento es el 3 de junio**
2. Página Colabora con formulario funcional
3. CRM Admin con Supabase
4. WebPay integración ← fase final

---

*Documento creado: Mayo 2026 | Proyecto: Sitio web independiente Fundación Corralco Malalcahuello*
