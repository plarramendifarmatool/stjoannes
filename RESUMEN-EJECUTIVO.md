# Resumen Ejecutivo - Proyecto E-commerce St Joannes

## ✅ Estado Actual: LISTO PARA DESARROLLO

---

## 📋 Requisitos Confirmados

### 1. Generación Automática de Facturas
- ✅ PDF profesional con cumplimiento fiscal español
- ✅ Numeración secuencial (YYYY-NNNNNN)
- ✅ IVA 21% desglosado
- ✅ Envío automático por email
- ✅ Almacenamiento para contabilidad
- **Plugin recomendado:** Sufio (€19/mes)

### 2. Venta de Vinos (Mínimo 6 Botellas)
- ✅ Mostrar precio por botella
- ✅ Venta mínima: 6 botellas (1 caja)
- ✅ Solo múltiplos de 6 permitidos
- ✅ Cajas mixtas permitidas (diferentes vinos)
- **Plugin:** WooCommerce Min/Max Quantities (Gratis)

### 3. Integración MBE (Logística)
- ✅ **API URL:** https://api.mbeonline.es/ws/e-link.wsdl
- ✅ **Usuario:** StJoannes@Spain
- ✅ **API Passphrase:** FLUFEwVrTLw54Zh6o6S9JlRQHKmNNuXq
- ✅ Tipo: SOAP Web Service
- ✅ Envío automático de pedidos
- ✅ Números de seguimiento integrados
- ✅ Etiquetas de envío descargables
- **Desarrollo:** Plugin personalizado (€400-€800)

### 4. Productos
- ✅ **Archivo:** vinos.csv (formato WooCommerce listo)
- ✅ Imágenes ya en WordPress
- ✅ Listo para importar

---

## 🎯 Plataforma Recomendada: **WooCommerce (WordPress)**

### ¿Por qué WooCommerce?
1. ✅ **Ya conoces WordPress** - Sin curva de aprendizaje
2. ✅ **Económico** - Plugins gratuitos/baratos
3. ✅ **Rápido** - 2-4 semanas hasta lanzamiento
4. ✅ **Mercado español** - Excelente para facturas con IVA
5. ✅ **Flexible** - Fácil personalizar lógica de 6 botellas
6. ✅ **Auto-gestionable** - Puedes administrarlo tú mismo

---

## 💰 Presupuesto

### Costes Únicos (Desarrollo)
| Concepto | Coste |
|----------|-------|
| Theme premium (opcional) | €0-€60 |
| Plugin MBE personalizado | €400-€800 |
| Diseño y configuración inicial | €300-€600 |
| Testing y QA | €100-€200 |
| **TOTAL DESARROLLO** | **€800-€1,660** |

### Costes Mensuales
| Concepto | Coste/Mes |
|----------|-----------|
| Hosting (Cloudways recomendado) | €11 |
| Sufio (facturas) | €19 |
| Backups + Seguridad | €0-€15 |
| **TOTAL MENSUAL** | **€30-€45** |

### Primer Año Total
| Concepto | Coste |
|----------|-------|
| Desarrollo (único) | €800-€1,660 |
| Hosting + Plugins (12 meses) | €360-€540 |
| Dominio | €10-€20 |
| **TOTAL AÑO 1** | **€1,170-€2,220** |

✅ **Dentro del presupuesto estimado: €1,300-€2,760**

---

## 📅 Timeline: 4 Semanas (24 Días)

### 🔵 Semana 1: Fundamentos (Días 1-5)
**Objetivo:** WordPress instalado, WooCommerce configurado, productos importados

**Tareas principales:**
- Contratar hosting (Cloudways €11/mes)
- Instalar WordPress + WooCommerce
- Configurar pasarela de pago (Redsys)
- Configurar impuestos (21% IVA España)
- Elegir e instalar theme (Astra gratuito)
- **Importar vinos desde vinos.csv**
- Verificar imágenes y categorías

**Entregables:**
- Tienda online básica funcionando
- Todos los vinos importados
- Pagos de prueba funcionando

---

### 🟢 Semana 2: Funciones Core (Días 6-10)
**Objetivo:** Facturas automáticas + lógica de 6 botellas

**Tareas principales:**
- **Días 6-7:** Sistema de facturas
  - Instalar Sufio (o alternativa gratuita)
  - Configurar empresa (CIF, dirección, etc.)
  - Diseñar plantilla de factura
  - Probar generación automática
  - Verificar cumplimiento legal español

- **Días 8-10:** Lógica de 6 botellas
  - Instalar plugin Min/Max Quantities
  - Configurar mínimo 6, paso 6
  - Personalizar selector de cantidad
  - Validación de carrito (total múltiplo de 6)
  - Mensajes de error en español
  - Probar cajas mixtas (diferentes vinos)

**Entregables:**
- Facturas automáticas generándose
- Pedidos solo en múltiplos de 6
- Cajas mixtas funcionando

---

### 🟡 Semana 3: Integración MBE (Días 11-17)
**Objetivo:** Conexión automática con MBE para envíos

**Tareas principales:**
- **Días 11-12:** Análisis API MBE
  - Descargar y analizar WSDL
  - Probar autenticación SOAP
  - Crear envío de prueba
  - Documentar estructura de datos

- **Días 13-15:** Desarrollo plugin
  - Crear plugin "St Joannes MBE Integration"
  - Cliente SOAP para API MBE
  - Hook en WooCommerce (pedido → MBE)
  - Guardar número de seguimiento
  - Descargar etiquetas de envío
  - Panel admin con info MBE
  - Email a cliente con tracking

- **Días 16-17:** Testing MBE
  - Probar con pedidos reales
  - Verificar etiquetas descargables
  - Probar diferentes cantidades (6, 12, 18 botellas)
  - Manejo de errores
  - Botón de sincronización manual

**Entregables:**
- Pedidos se envían automáticamente a MBE
- Números de seguimiento visibles
- Etiquetas de envío descargables
- Emails con tracking a clientes

---

### 🟣 Semana 4: Testing y Lanzamiento (Días 18-24)
**Objetivo:** Probar todo, optimizar, entrenar y lanzar

**Tareas principales:**
- **Días 18-19:** Testing completo end-to-end
  - Flujo completo de compra
  - Diferentes navegadores y dispositivos
  - Validar facturas legales
  - Verificar integración MBE
  - Tests de rendimiento (velocidad)

- **Días 20-21:** Optimización y correcciones
  - Arreglar bugs encontrados
  - Optimizar imágenes (WebP)
  - Configurar caché
  - SEO básico (Yoast)
  - Seguridad (Wordfence)

- **Día 22:** Pulido de contenido
  - Revisar textos (ortografía)
  - Diseño final homepage
  - Footer con info legal
  - Páginas legales (Privacidad, Términos)

- **Día 23:** Formación
  - **Sesión 2-3 horas contigo:**
    - Gestionar pedidos
    - Imprimir facturas
    - Descargar etiquetas MBE
    - Añadir/editar productos
    - Actualizar precios
    - Mantenimiento básico
  - Videos y documentación

- **Día 24:** Lanzamiento
  - Checklist pre-lanzamiento
  - Pasarela de pago a MODO REAL
  - Prueba final de compra
  - Quitar "En construcción"
  - **¡SITIO EN VIVO!**

**Entregables:**
- Sitio web funcionando perfectamente
- Tú capacitado para gestionar
- Documentación y videos
- Plan de soporte

---

## 🛠️ Stack Tecnológico

### Core
- **CMS:** WordPress (última versión)
- **E-commerce:** WooCommerce
- **Theme:** Astra (gratuito) o Kadence
- **Hosting:** Cloudways (€11/mes, VPS optimizado)

### Plugins Esenciales

**Gratuitos:**
- WooCommerce Min/Max Quantities (6 botellas)
- UpdraftPlus (backups)
- Wordfence Security
- Yoast SEO
- Contact Form 7

**Premium:**
- Sufio (facturas españolas) - €19/mes
- WP Rocket (caché, opcional) - €4/mes

**Personalizado:**
- St Joannes MBE Integration (desarrollo propio)

### Pasarela de Pago
- **Principal:** Redsys (tarjetas españolas)
- **Backup:** PayPal

---

## 📊 Archivos del Proyecto

### Repositorio GitHub
**URL:** https://github.com/plarramendifarmatool/stjoannes

### Estructura Auto-Claude
```
web30/
├── .auto-claude/
│   ├── .env                    (configuración Auto-Claude)
│   ├── ideation/
│   │   └── 01-project-vision.md
│   ├── insights/
│   │   ├── 01-brand-analysis.md
│   │   └── 02-technical-requirements.md
│   ├── specs/
│   │   ├── 01-ecommerce-core-requirements.md (200+ líneas detalle)
│   │   └── 02-mbe-integration-details.md     (código SOAP completo)
│   └── roadmap/
│       └── 01-project-roadmap.md             (plan 24 días)
├── CLAUDE.md                   (overview del proyecto)
├── RESUMEN-EJECUTIVO.md        (este archivo)
├── vinos.csv                   (productos listos para importar)
└── README.md
```

### Documentos Clave

1. **[CLAUDE.md](CLAUDE.md)** - Visión general del proyecto, requisitos, recomendaciones de plataforma

2. **[.auto-claude/specs/01-ecommerce-core-requirements.md](.auto-claude/specs/01-ecommerce-core-requirements.md)** - Especificación técnica detallada:
   - Requisitos de facturas (legal español)
   - Lógica de 6 botellas (código PHP incluido)
   - Validaciones de carrito
   - Lista de verificación completa

3. **[.auto-claude/specs/02-mbe-integration-details.md](.auto-claude/specs/02-mbe-integration-details.md)** - Integración MBE completa:
   - Credenciales API (incluidas)
   - Código SOAP cliente PHP
   - Estructura del plugin WooCommerce
   - Manejo de errores y retry logic
   - Admin interface mockups

4. **[.auto-claude/roadmap/01-project-roadmap.md](.auto-claude/roadmap/01-project-roadmap.md)** - Roadmap completo de 24 días con tareas específicas por día

5. **[vinos.csv](vinos.csv)** - Catálogo de productos listo para importar a WooCommerce

---

## ⚠️ Información Crítica MBE

### Credenciales MBE (CONFIDENCIAL)
```
API Type: SOAP Web Service
WSDL URL: https://api.mbeonline.es/ws/e-link.wsdl
Username: StJoannes@Spain
API Passphrase: FLUFEwVrTLw54Zh6o6S9JlRQHKmNNuXq
```

**🔒 IMPORTANTE:** Estas credenciales están almacenadas en:
- Este documento (temporal)
- `.auto-claude/specs/02-mbe-integration-details.md`

**Antes de compartir el repositorio públicamente:**
- Mover credenciales a `wp-config.php`
- O usar variables de entorno
- Eliminar de archivos de documentación

---

## 🎯 Próximos Pasos INMEDIATOS

### Esta Semana (Antes de Empezar Desarrollo)

#### 1. Confirmar Plataforma ✅
**Decisión:** WooCommerce
**Razón:** Ya usas WordPress, es la opción más económica y rápida

#### 2. Contratar Hosting
**Opción Recomendada:** Cloudways
- **Coste:** €11/mes (plan DigitalOcean 1GB)
- **Por qué:** WooCommerce optimizado, rápido, soporte bueno
- **Alternativa:** SiteGround (€6.99/mes, también bueno)

**Acción:** Registrarse en https://cloudways.com

#### 3. Información Necesaria

**Para Facturas (Legal):**
- [ ] Nombre legal empresa: "Bodega St Joannes" (o razón social oficial)
- [ ] CIF/NIF: _______________
- [ ] Dirección fiscal completa
- [ ] ¿Tienes asesor fiscal para revisar formato factura?

**Para Pagos:**
- [ ] ¿Tienes cuenta Redsys? (pasarela tarjetas española)
- [ ] Si no, ¿tienes cuenta bancaria para solicitar TPV?
- [ ] ¿Tienes PayPal Business? (backup)

**Assets Gráficos:**
- [ ] Logo St Joannes (alta resolución PNG/SVG)
- [ ] ¿Hay guía de marca? (colores, fuentes)
- [ ] ¿Imágenes adicionales? (bodega, viñedos, equipo)

**Contenido Legal:**
- [ ] Política de Privacidad
- [ ] Términos y Condiciones
- [ ] Política de Cookies
- [ ] Política de Envíos y Devoluciones

#### 4. Contacto MBE
**Opcional pero recomendado:**
- Contactar MBE para solicitar documentación API completa
- Preguntar si hay entorno de pruebas (sandbox)
- Confirmar que las credenciales proporcionadas son las correctas

---

## 🚀 Cronograma Propuesto

| Fecha | Fase | Actividades |
|-------|------|-------------|
| **Semana del 13 Ene** | Preparación | Contratar hosting, reunir información legal/fiscal |
| **Semana del 20 Ene** | Semana 1 - Fundamentos | WordPress, WooCommerce, importar productos |
| **Semana del 27 Ene** | Semana 2 - Features | Facturas + lógica 6 botellas |
| **Semana del 3 Feb** | Semana 3 - MBE | Integración logística |
| **Semana del 10 Feb** | Semana 4 - Testing | Pruebas, formación, lanzamiento |
| **17 Feb (aprox)** | 🎉 LANZAMIENTO | Sitio en vivo |

---

## ✅ Checklist Pre-Desarrollo

Antes de empezar el Día 1, necesitas:

### Hosting y Dominio
- [ ] Hosting contratado (Cloudways o similar)
- [ ] Dominio configurado (¿usas stjoannes.com actual o nuevo?)
- [ ] DNS apuntando al nuevo hosting (si migración)
- [ ] SSL configurado (normalmente automático con hosting)

### Información Legal
- [ ] CIF/NIF empresa
- [ ] Dirección fiscal completa
- [ ] Datos para facturación

### Pagos
- [ ] Pasarela de pago seleccionada (Redsys recomendado)
- [ ] Credenciales TPV obtenidas (del banco)
- [ ] PayPal Business (opcional backup)

### Contenido
- [ ] Logo (PNG/SVG alta res)
- [ ] Políticas legales (Privacidad, Términos, Cookies)
- [ ] Textos homepage (bienvenida, sobre bodega)
- [ ] Imágenes bodega/viñedos (opcional pero recomendado)

### MBE
- [ ] Confirmar credenciales correctas
- [ ] Contacto soporte MBE (por si hay problemas)

---

## 🆘 Soporte y Contacto

### Durante Desarrollo (4 semanas)
- **Comunicación:** Email / WhatsApp (definir)
- **Check-ins:** Diarios primera semana, luego cada 2-3 días
- **Entregables:** Al final de cada semana

### Post-Lanzamiento
- **Soporte incluido:** 30 días
- **Tipo:** Corrección de bugs, dudas sobre gestión
- **No incluido:** Nuevas funcionalidades, cambios de diseño mayores

### Mantenimiento Continuo (Opcional)
Si quieres que alguien más gestione actualizaciones y mantenimiento:
- **Coste estimado:** €50-€150/mes
- **Incluye:** Actualizaciones, backups, monitoreo, soporte

---

## 📈 Expectativas Post-Lanzamiento

### Primeros Días
- **Monitoreo intensivo:** Revisar cada pedido
- **Verificar:** Facturas correctas, MBE funcionando
- **Respuesta rápida:** Cualquier problema se soluciona en <24h

### Primera Semana
- **Objetivo:** 5-10 pedidos sin problemas
- **Verificar:** Proceso completo (compra → factura → envío MBE → entrega)

### Primer Mes
- **Métricas clave:**
  - Tasa de conversión: >2%
  - Valor medio pedido: €75+ (6 botellas × €12.50)
  - Satisfacción cliente: Sin quejas sobre proceso compra
  - Integración MBE: >95% éxito

### Mejoras Futuras (Post-Lanzamiento)
Ideas para Fase 2 (opcionales):
- Multi-idioma (Catalán, Inglés)
- Blog de vinos y maridajes
- Programa de fidelización / club de vinos
- Suscripción mensual de vinos
- Integración con redes sociales (Instagram shop)
- Marketing automation (email campaigns)

---

## ❓ Preguntas Frecuentes

### ¿Puedo gestionar la web yo mismo después del lanzamiento?
**Sí, 100%.** WooCommerce es intuitivo. Después de la formación del Día 23, podrás:
- Gestionar pedidos
- Añadir/editar productos
- Actualizar precios
- Ver facturas
- Descargar etiquetas MBE
- Actualizar contenido

### ¿Qué pasa si tengo un problema técnico después del lanzamiento?
Soporte incluido 30 días. Después, opciones:
- Mantenimiento mensual (€50-€150/mes)
- Soporte puntual por horas
- Auto-gestión (mayoría de problemas solucionables con Google/YouTube)

### ¿Puedo cambiar precios o añadir vinos nuevos fácilmente?
**Sí, muy fácil.** WooCommerce permite:
- Editar precio en 2 clics
- Añadir nuevo vino: copiar producto existente, cambiar nombre/imagen/precio
- Importar productos masivamente desde CSV

### ¿La integración MBE es 100% automática?
**Sí.** Cuando un cliente paga:
1. Se genera factura automáticamente
2. Se envía pedido a MBE automáticamente
3. MBE devuelve número seguimiento
4. Cliente recibe email con tracking

**Backup manual:** Si falla, botón en admin para reenviar a MBE.

### ¿Qué pasa si un cliente intenta comprar 7 botellas?
**El sistema lo bloquea.** Mostrará mensaje:
> "La cantidad debe ser múltiplo de 6. Añade X botellas más."

No podrá completar compra hasta ajustar a 6, 12, 18, etc.

### ¿Puedo vender cajas mixtas (diferentes vinos)?
**Sí.** Cliente puede añadir:
- 6 blanco + 6 tinto = 12 total ✅
- 3 blanco + 3 tinto = 6 total ✅
- 6 blanco + 4 tinto = 10 total ❌ (bloqueado)

### ¿Las facturas cumplen con la ley española?
**Sí.** Plugin Sufio está diseñado para mercado español:
- IVA desglosado correctamente
- Toda información legal requerida
- Numeración secuencial (obligatorio)
- Formato PDF estándar

**Recomendación:** Que tu asesor fiscal revise una factura de prueba antes del lanzamiento.

---

## 📞 Contacto Proyecto

**Cliente:** Bodega St Joannes
**Email:** bodega@stjoannes.com
**Teléfono:** +34 609 022 753 / +34 616 942 321

**Repositorio GitHub:** https://github.com/plarramendifarmatool/stjoannes

**Auto-Claude Configurado:** ✅ (Token añadido en .env)

---

## 🎯 Resumen Final

### Lo que tienes ahora:
✅ Proyecto completamente documentado
✅ Especificaciones técnicas detalladas
✅ Código de ejemplo para MBE (SOAP)
✅ Roadmap día a día (24 días)
✅ Presupuesto claro (€1,170-€2,220 año 1)
✅ Productos listos para importar (vinos.csv)
✅ Credenciales MBE documentadas
✅ Auto-Claude configurado para asistencia

### Lo que necesitas hacer:
1. ✅ Confirmar que WooCommerce es la plataforma (CONFIRMADO)
2. 📌 Contratar hosting (Cloudways €11/mes)
3. 📌 Reunir información legal (CIF, dirección fiscal)
4. 📌 Obtener credenciales pasarela de pago (Redsys)
5. 📌 Preparar assets (logo, textos legales)
6. 🚀 **Empezar Semana 1 (Día 1)**

### Resultado final (4 semanas después):
🎉 **E-commerce profesional de vinos**
- Facturas automáticas legales
- Venta mínima 6 botellas (cajas mixtas OK)
- Integración MBE automática
- Tú puedes gestionarlo completamente
- Coste mensual: €30-€45

---

**¿Listo para empezar?** 🍷

Cuando tengas hosting contratado e información legal lista, ¡comenzamos con el Día 1!

---

*Documento creado: 10 Enero 2026*
*Versión: 1.0*
*Estado: Listo para ejecución*
