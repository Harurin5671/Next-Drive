# Mapa del Sitio - Next Drive

## Estructura del Sitio

```
Next Drive (Sitio Web Estático)
├── index.html (Página Principal)
│   ├── Header (Navbar responsive)
│   ├── Hero Section
│   ├── Productos Destacados (4 cards)
│   ├── Nuestros Servicios (4 cards)
│   ├── Guías de Cuidado (3 videos)
│   ├── Promoción del Mes (3 cards)
│   └── Footer
│
├── nosotros.html (Nosotros)
│   ├── Header (Navbar responsive)
│   ├── Page Header (Breadcrumb + Título)
│   ├── Quiénes Somos (Split layout)
│   ├── Equipo Técnico (4 cards)
│   ├── Sede y Horarios (Mapa + Tabla)
│   └── Footer
│
├── catalogo.html (Catálogo)
│   ├── Header (Navbar responsive)
│   ├── Page Header (Breadcrumb + Título)
│   ├── Navegación de Categorías (Anclas)
│   ├── Lubricantes y Energía (4 cards)
│   ├── Neumáticos y Cuidado (4 cards)
│   └── Footer
│
├── servicios.html (Servicios)
│   ├── Header (Navbar responsive)
│   ├── Page Header (Breadcrumb + Título)
│   ├── Navegación de Servicios (Anclas)
│   ├── Mantenimiento Preventivo (Split layout)
│   ├── Mantenimiento Correctivo (Split layout)
│   ├── Neumáticos (Split layout)
│   ├── Cuidado Estético (Split layout)
│   └── Footer
│
└── contacto.html (Contacto)
    ├── Header (Navbar responsive)
    ├── Page Header (Breadcrumb + Título)
    ├── Formulario de Contacto
    ├── Contacto Directo (Aside)
    ├── FAQ (5 preguntas)
    └── Footer
```

## Páginas y Secciones Detalladas

### 1. index.html (Página Principal)

**Secciones:**
- **Header**: Logo + Navbar responsive (Bootstrap 5.3)
  - Links: Nosotros, Catálogo, Servicios, Contacto
  - Menú hamburguesa en móvil

- **Hero Section**:
  - Título: "Next Drive"
  - Subtítulo: Descripción del servicio
  - CTAs: "Conócenos" (btn-primary), "Ver catálogo" (btn-outline)
  - Nota: Horario de atención
  - Imagen: Vehículo en taller
  - Floating card: "Servicio garantizado"

- **Productos Destacados**:
  - Grid de 4 cards (Bootstrap responsive)
  - Aceite sintético 5W-30 (S/ 189)
  - Batería premium 15 placas (S/ 429)
  - Neumático Touring 205/55 (S/ 319)
  - Kit de limpieza interior (S/ 129)
  - CTA: "Ver catálogo completo"

- **Nuestros Servicios**:
  - Grid de 4 cards (Bootstrap responsive)
  - Mantenimiento preventivo
  - Mantenimiento correctivo
  - Neumáticos
  - Cuidado estético
  - Links a secciones de servicios.html

- **Guías de Cuidado**:
  - Grid de 3 videos (YouTube embeds)
  - 5 errores al cambiar el aceite (3:02 min)
  - Revisión básica de carro (4:07 min)
  - Protección con cera cerámica (5:24 min)

- **Promoción del Mes**:
  - Grid de 3 cards
  - Pack ruta segura (15% descuento)
  - Servicio de frenos (20% descuento)
  - Detailing esencial (25% descuento)
  - CTAs: "Cotizar"

- **Footer**:
  - Logo y descripción
  - Links a servicios
  - Enlaces rápidos
  - Contacto + redes sociales
  - Información legal

### 2. nosotros.html (Nosotros)

**Secciones:**
- **Header**: Logo + Navbar responsive

- **Page Header**:
  - Breadcrumb: Inicio > Nosotros
  - Título: "Conducimos confianza."
  - Descripción

- **Quiénes Somos**:
  - Split layout (texto + imagen)
  - Descripción de la empresa
  - Valores: Transparencia, Excelencia, Cercanía
  - Imagen: Técnico trabajando

- **Equipo Técnico**:
  - Grid de 4 cards
  - Mayra Robles (Especialista de diagnóstico)
  - JeanPiere Oriundo (Técnico automotriz senior)
  - Frank Santos (Desarrollador de software)
  - Manuel Serra (Especialista de diagnóstico)

- **Sede y Horarios**:
  - Mapa (Google Maps embed)
  - Tabla de horarios
  - Dirección: Av. Javier Prado 2450, San Borja

- **Footer**: Igual que index.html

### 3. catalogo.html (Catálogo)

**Secciones:**
- **Header**: Logo + Navbar responsive

- **Page Header**:
  - Breadcrumb: Inicio > Catálogo
  - Título: "Productos para avanzar."
  - Descripción

- **Navegación de Categorías**:
  - Anclas: Lubricantes, Neumáticos
  - Sticky navigation

- **Lubricantes y Energía**:
  - Grid de 4 cards
  - Aceite sintético 5W-30 (S/ 189)
  - Batería premium 15 placas (S/ 429)
  - Lubricante de transmisión (S/ 159)
  - Batería estándar 13 placas (S/ 349)

- **Neumáticos y Cuidado**:
  - Grid de 4 cards
  - Neumático Touring 205/55 (S/ 319)
  - Kit de limpieza interior (S/ 129)
  - Neumático Urbano 195/65 (S/ 279)
  - Cera protectora (S/ 89)

- **Footer**: Igual que index.html

### 4. servicios.html (Servicios)

**Secciones:**
- **Header**: Logo + Navbar responsive

- **Page Header**:
  - Breadcrumb: Inicio > Servicios
  - Título: "Servicio que da confianza."
  - Descripción

- **Navegación de Servicios**:
  - Anclas: Preventivo, Correctivo, Neumáticos, Cuidado estético
  - Sticky navigation

- **Mantenimiento Preventivo** (id="srv-preventivo"):
  - Split layout (imagen + contenido)
  - Descripción
  - Incluye: Aceite y filtros, Revisión por kilometraje, Afinamiento
  - Precio: Desde S/ 000
  - CTA: "Cotizar servicio"

- **Mantenimiento Correctivo** (id="srv-correctivo"):
  - Split layout
  - Incluye: Frenos, Suspensión y dirección, Sistema eléctrico y batería
  - Precio: Desde S/ 000
  - CTA: "Cotizar servicio"

- **Neumáticos** (id="srv-neumaticos"):
  - Split layout
  - Incluye: Alineamiento y balanceo, Cambio y rotación, Inspección de desgaste
  - Precio: Desde S/ 000
  - CTA: "Cotizar servicio"

- **Cuidado Estético** (id="srv-estetico"):
  - Split layout
  - Incluye: Lavado y encerado, Limpieza de interiores, Protección de superficies
  - Precio: Desde S/ 000
  - CTA: "Cotizar servicio"

- **Footer**: Igual que index.html

### 5. contacto.html (Contacto)

**Secciones:**
- **Header**: Logo + Navbar responsive

- **Page Header**:
  - Breadcrumb: Inicio > Contacto
  - Título: "Hablemos de tu vehículo."
  - Descripción

- **Formulario de Contacto**:
  - Nombre y apellido *
  - Teléfono *
  - Correo electrónico *
  - Motivo de contacto * (select)
  - Interés
  - Mensaje
  - Checkbox: Acepto política de privacidad
  - CTA: "Enviar consulta" (con alerta JavaScript)

- **Contacto Directo** (Aside):
  - Teléfono: (01) 555-0148
  - Correo: hola@nextdrive.pe
  - Dirección: Av. Javier Prado 2450, San Borja
  - Horario: Lun—Vie 8:00—18:00 · Sáb 8:00—14:00

- **FAQ** (id="faq"):
  - ¿Necesito agendar una cita?
  - ¿Cuánto demora un mantenimiento preventivo?
  - ¿Los productos tienen garantía?
  - ¿Qué medios de pago aceptan?
  - ¿Puedo llevar mis propios repuestos?

- **Footer**: Igual que index.html

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos personalizados
- **Bootstrap 5.3.3**: Framework CSS para layout y componentes
- **Bootstrap Icons 1.11.3**: Iconos
- **Google Fonts**: Inter y Poppins
- **JavaScript**: Validación de formulario (alerta en contacto)
- **YouTube Embed**: Videos de guías
- **Google Maps**: Mapa en nosotros.html

## Características Responsive

- **Navbar**: Collapsible en móvil (Bootstrap navbar)
- **Grids**: Responsive con Bootstrap (col-6 col-md-3, col-md-4, etc.)
- **Cards**: Altura uniforme con flexbox
- **Imágenes**: 100% width, object-fit cover
- **Media Queries**: Breakpoints en 900px y 640px

## Archivos del Proyecto

```
Next Drive/
├── index.html
├── nosotros.html
├── catalogo.html
├── servicios.html
├── contacto.html
├── CSS/
│   └── index.css
├── image/
│   ├── Mayra.jpeg
│   ├── Jeanpiere.jpeg
│   └── Manuel.jpeg
└── documentacion/
    ├── mapa-sitio.md
    └── wireframes.md
```

## Enlaces Externos

- **Email**: hola@nextdrive.pe
- **Teléfono**: (01) 555-0148
- **Dirección**: Av. Javier Prado 2450, San Borja
- **Redes Sociales**: Instagram, Facebook, YouTube (placeholder URLs)
- **Horario**: Lun—Vie 8:00—18:00 · Sáb 8:00—14:00
