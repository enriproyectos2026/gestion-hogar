# 📖 Manual de Usuario — Gestión Casa v5.0

**Versión:** 5.0  
**Fecha:** 12 de agosto de 2026  
**Propósito:** Guía completa para el uso diario de la aplicación de gestión del hogar.

---

<h2 id="indice">📚 Índice</h2>

- [1. Dashboard](#sec-1)
  - [1.1. Barra superior de contexto](#sec-1-1)
  - [1.2. Widgets de alerta](#sec-1-2)
  - [1.3. Acciones rápidas](#sec-1-3)
  - [1.4. Cargos periódicos pendientes](#sec-1-4)
  - [1.5. Tablas de resumen](#sec-1-5)
  - [1.6. Listas de compra activas](#sec-1-6)
  - [1.7. Personalizar el dashboard](#sec-1-7)
- [2. Compras](#sec-2)
  - [2.1. Histórico de Tickets](#sec-2-1)
  - [2.2. Nueva Compra](#sec-2-2)
  - [2.3. Detalle de Compra](#sec-2-3)
  - [2.4. Editar Línea](#sec-2-4)
  - [2.5. Gestión de Tickets (OCR)](#sec-2-5)
- [3. Stock](#sec-3)
  - [3.1. Despensa](#sec-3-1)
  - [3.2. Movimientos de Stock](#sec-3-2)
- [4. Recetas](#sec-4)
  - [4.1. Listado de Recetas](#sec-4-1)
  - [4.2. Nueva Receta](#sec-4-2)
  - [4.3. Detalle de Receta](#sec-4-3)
  - [4.4. Ficha de Cocina](#sec-4-4)
  - [4.5. ¿Qué puedo cocinar?](#sec-4-5)
  - [4.6. Importar Recetas](#sec-4-6)
  - [4.7. Accesorios de Cocina](#sec-4-7)
- [5. Productos](#sec-5)
  - [5.1. Listado de Productos](#sec-5-1)
  - [5.2. Detalle de Producto](#sec-5-2)
  - [5.3. Comparador de Precios](#sec-5-3)
  - [5.4. Tipos de Producto](#sec-5-4)
  - [5.5. Unidades de Medida](#sec-5-5)
  - [5.6. Conversiones de Unidades](#sec-5-6)
  - [5.7. Importar Alimentos Básicos](#sec-5-7)
- [6. Supermercados](#sec-6)
  - [6.1. Listado de Supermercados](#sec-6-1)
  - [6.2. Detalle de Supermercado](#sec-6-2)
  - [6.3. Calendario de Festivos](#sec-6-3)
  - [6.4. Crear/Editar Supermercado](#sec-6-4)
- [7. Finanzas](#sec-7)
  - [7.1. Movimientos](#sec-7-1)
  - [7.2. Conciliación Bancaria](#sec-7-2)
  - [7.3. Bancos](#sec-7-3)
  - [7.4. Cuentas](#sec-7-4)
  - [7.5. Tarjetas](#sec-7-5)
  - [7.6. Liquidaciones de Tarjeta](#sec-7-6)
  - [7.7. Financiaciones](#sec-7-7)
  - [7.8. Gastos Periódicos](#sec-7-8)
  - [7.9. Métodos de Pago](#sec-7-9)
  - [7.10. Previsión de Pagos](#sec-7-10)
- [8. Técnicas de Cocina](#sec-8)
  - [8.1. Listado de Técnicas](#sec-8-1)
  - [8.2. Nueva Técnica](#sec-8-2)
  - [8.3. Detalle de Técnica](#sec-8-3)
  - [8.4. Añadir / Editar Variante](#sec-8-4)
  - [8.5. Ficha de Técnica](#sec-8-5)
  - [8.6. Importar Técnica](#sec-8-6)
- [9. Robots de Cocina](#sec-9)
  - [9.1. Listado de Robots](#sec-9-1)
  - [9.2. Detalle de Robot](#sec-9-2)
  - [9.3. Nuevo / Editar Robot](#sec-9-3)
  - [9.4. Importar Robots](#sec-9-4)
  - [9.5. Papelera](#sec-9-5)
- [10. Planificación](#sec-10)
  - [10.1. Plan Semanal](#sec-10-1)
  - [10.2. Listas de la Compra](#sec-10-2)
  - [10.3. Comparador de Precios (Matriz)](#sec-10-3)
- [11. Comercio en Línea](#sec-11)
  - [11.1. Pedidos](#sec-11-1)
  - [11.2. Detalle de Pedido](#sec-11-2)
  - [11.3. Nuevo / Editar Pedido](#sec-11-3)
  - [11.4. Entregar Pedido](#sec-11-4)
  - [11.5. Devolver Pedido / Línea](#sec-11-5)
  - [11.6. Reembolsar Pedido / Línea](#sec-11-6)
  - [11.7. Importar Pedido](#sec-11-7)
  - [11.8. Pedido Amazon (OCR)](#sec-11-8)
  - [11.9. Plataformas](#sec-11-9)
  - [11.10. Artículos](#sec-11-10)
  - [11.11. Monederos Virtuales](#sec-11-11)
  - [11.12. Estadísticas](#sec-11-12)
- [12. Salud](#sec-12)
  - [12.1. Vista Diaria](#sec-12-1)
  - [12.2. Configuración Diaria](#sec-12-2)
  - [12.3. Medicación Fija](#sec-12-3)
  - [12.4. Tomas de Datos](#sec-12-4)
  - [12.5. Eventos](#sec-12-5)
  - [12.6. Tipos de Dolor](#sec-12-6)
  - [12.7. Gráficos](#sec-12-7)
  - [12.8. Historial](#sec-12-8)
  - [12.9. PDF Diario](#sec-12-9)
- [13. Mascotas](#sec-13)
  - [13.1. Panel de Mascotas](#sec-13-1)
  - [13.2. Nueva / Editar Mascota](#sec-13-2)
  - [13.3. Ficha de la Mascota (Detalle)](#sec-13-3)
  - [13.4. Peso](#sec-13-4)
  - [13.5. Vacunas](#sec-13-5)
  - [13.6. Desparasitaciones](#sec-13-6)
  - [13.7. Visitas al Veterinario](#sec-13-7)

---

<h2 id="sec-1">1. Dashboard</h2>

El Dashboard es la pantalla principal tras iniciar sesión. Te ofrece una vista general de tu hogar con alertas, accesos rápidos y resúmenes.

<h3 id="sec-1-1">1.1. Barra superior de contexto</h3>

Nada más entrar, bajo el menú, verás una barra con:
- **Nombre de la casa activa** (ej: "Casa principal")
- **Schema técnico** (para referencia)
- **Selector de casa:** Si gestionas varias casas, puedes cambiar entre ellas

> [!WARNING]  
> Si ves "Sin casa seleccionada", debes crear o seleccionar una casa antes de continuar.

<h3 id="sec-1-2">1.2. Widgets de alerta</h3>

Son 6 tarjetas que te avisan de un vistazo:

| Widget | ¿Qué indica? |
| :--- | :--- |
| **Caducan pronto** | Productos próximos a caducar. Si hay, muestra el número y un botón para revisarlos |
| **Stock bajo** | Productos por debajo del mínimo. Si hay, te lleva a la despensa filtrada |
| **Gastos del mes** | Total acumulado del mes actual. Enlace a todos los movimientos |
| **Próximas comidas** | Número de comidas planificadas. Enlace al plan semanal |
| **Pedidos en curso** | Pedidos online pendientes de recibir |
| **En reparto** | Pedidos que ya están en camino |

<h3 id="sec-1-3">1.3. Acciones rápidas</h3>

Seis botones grandes para las operaciones más frecuentes:

| Botón | Acción |
| :--- | :--- |
| **Nueva compra** | Registrar un ticket |
| **Nueva receta** | Crear receta desde cero |
| **Plan semanal** | Planificar comidas |
| **Nuevo pedido** | Pedido en comercio online |
| **Movimiento** | Registrar gasto/ingreso |
| **Robots** | Acceder a tus robots de cocina |

<h3 id="sec-1-4">1.4. Cargos periódicos pendientes</h3>

Si hay gastos automáticos programados para hoy (como suscripciones), verás un aviso para **Generarlos** o **Ignorarlos**.

<h3 id="sec-1-5">1.5. Tablas de resumen</h3>

| Tabla | Contenido |
| :--- | :--- |
| **Próximas comidas** | Fecha, tipo (comida/cena), receta y número de comensales |
| **Últimas compras** | Fecha, supermercado y total de cada compra reciente |

<h3 id="sec-1-6">1.6. Listas de compra activas</h3>

Muestra las listas de compra que tienes pendientes, con el número de items en cada una.

<h3 id="sec-1-7">1.7. Personalizar el dashboard</h3>

Haz clic en **Personalizar** (arriba a la derecha) para abrir un panel donde puedes activar o desactivar los widgets que quieres ver. Los cambios se guardan por usuario.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-2">2. Compras</h2>

<h3 id="sec-2-1">2.1. Histórico de Tickets</h3>

Es el listado principal de todas tus compras.

**Información mostrada:**

| Columna | Descripción |
| :--- | :--- |
| **ID** | Número único de la compra |
| **Fecha** | Día de la compra |
| **Supermercado** | Dónde compraste |
| **Total** | Importe total en negrita |
| **Estado** | Borrador 🟡 / Confirmada 🟢 / Anulada 🔴 |

**Total general:** Sobre la tabla ves el total acumulado de todas las compras.

**Acciones por compra:**

| Icono | Acción | ¿Cuándo aparece? |
| :---: | :--- | :--- |
| 👁️ | **Ver** (Abre el detalle) | Siempre |
| ✅ | **Confirmar** (Pasa a confirmada) | Solo en borrador |
| ↩️ | **Desconfirmar** (Vuelve a borrador) | Solo en confirmada |
| 🗑️ | **Anular** (Marca como anulada) | Siempre |

<h3 id="sec-2-2">2.2. Nueva Compra</h3>

Para crear una compra manualmente:
1. Ve a **Compras → Nueva compra**
2. Selecciona la fecha y el supermercado
3. Pulsa **Crear compra y añadir líneas**
4. Te llevará al detalle de la compra en estado borrador para añadir productos

<h3 id="sec-2-3">2.3. Detalle de Compra</h3>

**Cabecera:** Número de compra y estado. Datos principales: fecha, supermercado, total.

**Estados:**

| Estado | ¿Qué puedo hacer? |
| :--- | :--- |
| **Borrador** | Añadir/quitar/editar líneas, escanear EAN, confirmar |
| **Confirmada** | Solo consulta. Desconfirmar o anular |
| **Anulada** | Solo consulta |

**Añadir productos (solo en borrador):**

- **A) Escanear código de barras:** Pasa el lector EAN o escribe el código manualmente. Si el EAN existe, se añade automáticamente; si no existe, puedes crearlo al vuelo.
- **B) Crear producto nuevo (botón naranja):** Modal rápido para completar Nombre (obligatorio), Unidad base (obligatorio), Tipo, Cantidad, Precio, EAN, Caducidad, Alias en ticket y No gestionar stock.
- **C) Añadir producto existente (botón azul):** Buscas un producto de tu base de datos y configuras cantidad de envases, precio por envase/unidad, unidades por pack, caducidad, notas y hasta 3 niveles de descuento (% o €). Puedes usar *Añadir y cerrar* o *Añadir y seguir*.

**Tabla de líneas:**

| Columna | Descripción |
| :--- | :--- |
| **Producto** | Nombre y notas |
| **Cantidad** | Nº de envases |
| **Uds/envase** | Desglose de unidades |
| **Ud. base** | kg, L, ud... |
| **Caducidad** | Fecha si se informó |
| **Precio** | Unitario |
| **Dto.** | Descuentos aplicados |
| **Subtotal** | Importe final |

**Confirmar compra:**
1. Selecciona método de pago
2. Pulsa **Confirmar**
3. La compra se confirma y actualiza el stock automáticamente.

<h3 id="sec-2-4">2.4. Editar Línea</h3>

Al hacer clic en ✏️ en una línea, accedes al editor completo donde puedes modificar todos los campos. Los descuentos se recalculan en tiempo real con HTMX.

<h3 id="sec-2-5">2.5. Gestión de Tickets (OCR)</h3>

Para digitalizar tickets físicos o digitales:
1. Ve a **Compras → Gestionar tickets**
2. Sube el archivo:
   - 📷 **Imagen:** Foto del ticket
   - 📄 **PDF:** Ticket de Mercadona
   - 🌐 **HTML:** Ticket de Lidl
3. Elige modo de procesado:
   - **Procesar:** OCR clásico
   - **Procesar con IA:** Más preciso (Ollama local)
4. Revisa los productos detectados en la tabla
5. Corrige nombres, cantidades o precios si es necesario
6. Selecciona fecha y supermercado
7. Pulsa **Confirmar e importar**

[⬆ Volver al índice](#indice)

---

<h2 id="sec-3">3. Stock</h2>

<h3 id="sec-3-1">3.1. Despensa</h3>

La despensa te muestra todos los productos que gestionan stock, con alertas visuales para que nada se te pase.

**Filtros rápidos:**

| Filtro | ¿Qué muestra? |
| :--- | :--- |
| **Todos** | Todos los productos con gestión de stock |
| **Con stock** | Solo los que tienen cantidad > 0 |
| **Stock bajo** | Productos por debajo del mínimo |
| **Caduca pronto** | Productos con fecha de caducidad próxima |

**Tabla de productos:**

| Columna | Descripción |
| :--- | :--- |
| **Producto** | Nombre y badge "caduca" si es urgente |
| **Tipo** | Categoría del producto |
| **Unidades** | Nº de unidades/envases |
| **Cantidad** | Total en unidad base (kg, L, ud...) |
| **Mín** | Stock mínimo configurado |
| **Ideal** | Stock ideal configurado |

**Colores de alerta:**
- 🔴 **Rojo:** Sin stock (y tenía mínimo) o producto que caduca pronto
- 🟡 **Amarillo:** Stock por debajo del mínimo
- ⚪ **Normal:** Todo correcto

**Consumir producto:** Al hacer clic en **Consumir** se abre un modal donde puedes elegir el modo (*Por cantidad* o *Por unidades*), la fecha del consumo y notas adicionales.

<h3 id="sec-3-2">3.2. Movimientos de Stock</h3>

Registro completo de todas las entradas y salidas de tu despensa.

- **Filtros disponibles:** Producto, Tipo (Todos / Entradas / Salidas), Rango de fechas (Desde / Hasta).
- **Tabla de movimientos:** Fecha, Producto, Tipo (🟢 Entrada / 🔴 Salida), Entrada, Salida, Existencias, Precio ud., Origen.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-4">4. Recetas</h2>

<h3 id="sec-4-1">4.1. Listado de Recetas</h3>

Accede desde **Recetas → Ver todas**.

- **Filtros:** Buscador por nombre, Tipo (Principal, Entrante, Postre), Dificultad (Fácil, Media, Difícil).
- **Tarjetas de receta:** Nombre, tipo, dificultad, raciones, tiempo, alerta de stock (🟢 Todos disponibles o 🟡 Faltan X ingredientes).
- **Acciones:** 👁️ Ver, 📋 Ficha (imprimible), ✏️ Editar, 🗑️ Eliminar.

<h3 id="sec-4-2">4.2. Nueva Receta</h3>

Crea una receta desde cero con 4 pestañas:

| Pestaña | Contenido |
| :--- | :--- |
| **Datos generales** | Nombre, tipo, dificultad, raciones, tiempos, robot, categorías, conservación |
| **Ingredientes** | Se añaden después, desde el detalle de la receta |
| **Elaboración** | Instrucciones generales. Los pasos por robot se añaden después |
| **Extra** | Alérgenos y etiquetas de colores |

<h3 id="sec-4-3">4.3. Detalle de Receta</h3>

Organizada en las siguientes pestañas:
- **Pestaña Accesorios:** Accesorios necesarios agrupados por robot.
- **Pestaña Ingredientes:** Nombre, cantidad ajustada, stock disponible y estado (🟢 OK / 🟡 Bajo / 🔴 Sin stock). Al cambiar los comensales, se recalculan automáticamente.
- **Pestaña Elaboración:** Pasos agrupados por robot con nº de paso, tiempo, temperatura, potencia y velocidad.
- **Pestaña Variantes:** Versiones alternativas de la receta.
- **Pestaña Nutrición:** Tarjetas con kcal, grasas, saturadas, hidratos, azúcares, fibra, proteínas y sal.

**Botones de acción:**
- 🍳 **Cocinar:** Descuenta los ingredientes del stock
- 🛒 **Añadir faltantes:** Crea lista de compra con lo que falta
- 📋 **Ficha cocina:** Versión imprimible
- ✏️ **Editar datos** / 🗑️ **Eliminar**

<h3 id="sec-4-4">4.4. Ficha de Cocina</h3>

Pantalla especial optimizada para cocinar:
- Diseño en naranja con letra grande.
- Selector de robot: filtra los pasos por robot específico.
- Modo tradicional: muestra los pasos sin detalles técnicos.
- Botón **Imprimir** para llevarlo a papel.

<h3 id="sec-4-5">4.5. ¿Qué puedo cocinar?</h3>

Sugerencias basadas en tu stock actual:
- 🟢 **Recetas disponibles:** Tienes todos los ingredientes. Puedes cocinar ya.
- 🟡 **Casi disponibles:** Te falta algún ingrediente. Muestra el % disponible y botón para añadir faltantes.

<h3 id="sec-4-6">4.6. Importar Recetas</h3>

- **Individual:** Pega el texto de la receta o sube un archivo (TXT, MD, PDF), previsualiza y confirma.
- **En lote:** Coloca archivos en la carpeta `docs/Recetas pendientes/` para procesarlos de una vez.

<h3 id="sec-4-7">4.7. Accesorios de Cocina</h3>

Gestión de utensilios y accesorios asignables a las recetas.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-5">5. Productos</h2>

<h3 id="sec-5-1">5.1. Listado de Productos</h3>

Accede desde **Productos → Ver todos**.

- **Barra de acciones:** Tipos, Conversiones, Unidades, Importar alimentos (MD), Papelera.
- **Filtros:** Buscador (nombre/alias), Tipo de categoría.
- **Tabla de productos:** Nombre, Tipo, Stock (🟢 OK / 🟡 Bajo / 🔴 Sin stock), Formatos EAN, Consumir rápido y Acciones.

<h3 id="sec-5-2">5.2. Detalle de Producto</h3>

Ficha completa organizada en 5 pestañas:
1. **Información:** Nombre, tipo, unidad base, caducidad estimada, densidad, stock mínimo/ideal, alias.
2. **Formatos EAN:** Códigos de barras de 13 dígitos asociados por supermercado.
3. **Stock:** Lotes activos con cantidad, unidades, caducidad, días restantes y precios.
4. **Historial:** Últimas compras realizadas del producto.
5. **Movimientos:** Registro detallado de entradas y salidas de stock.

<h3 id="sec-5-3">5.3. Comparador de Precios</h3>

Accede desde **Productos → Comparador**.

Permite filtrar por producto, tipo y supermercados para obtener una tabla comparativa basada en el **precio por unidad base (€/kg, €/L o €/ud)**. La mejor opción se marca con la insignia 🏆 **"Mejor"** en verde.

<h3 id="sec-5-4">5.4. Tipos de Producto</h3>

Gestión de categorías con iconos de *Bootstrap Icons*.

<h3 id="sec-5-5">5.5. Unidades de Medida</h3>

Gestión de unidades (Kilogramo, Litro, Unidad) y sus abreviaturas.

<h3 id="sec-5-6">5.6. Conversiones de Unidades</h3>

Definición de equivalencias (ej: 1 cucharada = 7.8 g de harina; 1 taza = 240 ml de leche).

<h3 id="sec-5-7">5.7. Importar Alimentos Básicos</h3>

Carga masiva desde tablas en Markdown.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-6">6. Supermercados</h2>

<h3 id="sec-6-1">6.1. Listado de Supermercados</h3>

Tarjetas con nombre, tipo, ciudad, dirección, formatos EAN y servicios (parking, wifi...).
- **Barra superior:** Festivos, Nuevo supermercado, Papelera.

<h3 id="sec-6-2">6.2. Detalle de Supermercado</h3>

- **Información:** Datos generales, servicios y puntos de recogida.
- **Horarios:** Horario general semanal y selección múltiple de festivos.
- **Estadísticas:** Gastos mensuales del año (bruto, descuentos, neto) y EANs registrados.

<h3 id="sec-6-3">6.3. Calendario de Festivos</h3>

Gestión de festivos (Estatal 🔴, Autonómica 🟡, Local 🔵) con opciones para aplicar a todos los supermercados o importar calendarios.

<h3 id="sec-6-4">6.4. Crear/Editar Supermercado</h3>

Formulario con campos obligatorios: Nombre, Tipo, Ciudad; y opcionales: Dirección, Teléfono, Email, Web y Método de pago por defecto.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-7">7. Finanzas</h2>

<h3 id="sec-7-1">7.1. Movimientos</h3>

El corazón financiero (acceso desde **Finanzas → Movimientos**).
- **Tarjetas de resumen:** Gastos (rojo), Ingresos (verde) y Balance (azul).
- **Acciones:** Conciliar y Liquidaciones.
- **Tabla:** Muestra Fecha, F. Cargo, Concepto, Importe, Cuenta, Método y Toggle de Verificado. Acciones de duplicar, editar y eliminar.

<h3 id="sec-7-2">7.2. Conciliación Bancaria</h3>

Pantalla dividida en dos columnas:
- **Pendientes de conciliar (Izquierda):** Compras y pedidos sin movimiento bancario vinculado.
- **Movimientos sin conciliar (Derecha):** Movimientos bancarios sin compra asociada.
- Permite **Vincular** o **Marcar conciliado** manualmente.

<h3 id="sec-7-3">7.3. Bancos</h3>

Listado y detalle de entidades bancarias (código de 4 dígitos, país ISO) y sus cuentas asociadas.

<h3 id="sec-7-4">7.4. Cuentas</h3>

Administración de cuentas con saldo en tiempo real, alias e IBAN.

<h3 id="sec-7-5">7.5. Tarjetas</h3>

Tarjetas de débito, crédito, prepago o virtuales. Muestra ciclos de corte/cargo, límite de crédito, dispuesto y disponible. Incluye comparador entre la app y extracto PDF.

<h3 id="sec-7-6">7.6. Liquidaciones de Tarjeta</h3>

Gestión del cierre de ciclos de tarjetas de crédito. Permite verificar el periodo, generar la liquidación y pagarla creando el movimiento bancario.

<h3 id="sec-7-7">7.7. Financiaciones</h3>

Listado de compras financiadas con progreso de cuotas, intereses, comisiones y botón de pago individualizado por cuota.

<h3 id="sec-7-8">7.8. Gastos Periódicos</h3>

Control de suscripciones y recibos recurrentes. Puedes establecer la periodicidad y generar movimientos masivos para el mes.

<h3 id="sec-7-9">7.9. Métodos de Pago</h3>

Creación de accesos rápidos con iconos personalizados utilizados en compras y movimientos.

<h3 id="sec-7-10">7.10. Previsión de Pagos</h3>

Vista unificada con el total previsto a futuro desglosado por liquidaciones, financiaciones y gastos periódicos.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-8">8. Técnicas de Cocina</h2>

<h3 id="sec-8-1">8.1. Listado de Técnicas</h3>

Buscador y listado por categorías con tarjetas explicativas y variantes por robot.

<h3 id="sec-8-2">8.2. Nueva Técnica</h3>

Formulario básico: Nombre (obligatorio), Tipo, Descripción e Ingredientes recomendados.

<h3 id="sec-8-3">8.3. Detalle de Técnica</h3>

Muestra la información de la técnica y las variantes por robot (accesorio, tiempo, temperatura, velocidad, potencia).

<h3 id="sec-8-4">8.4. Añadir / Editar Variante</h3>

Permite definir los parámetros exactos de preparación para un modelo de robot concreto.

<h3 id="sec-8-5">8.5. Ficha de Técnica</h3>

Diseño oscuro imprimible adaptable a modo robot o tradicional.

<h3 id="sec-8-6">8.6. Importar Técnica</h3>

Acepta texto estructurado o archivos PDF/TXT/MD.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-9">9. Robots de Cocina</h2>

<h3 id="sec-9-1">9.1. Listado de Robots</h3>

Tarjetas con marca, modelo, recuento de accesorios y estado activo/inactivo.

<h3 id="sec-9-2">9.2. Detalle de Robot</h3>

Ficha del robot con lista de accesorios. Permite añadir, editar o eliminar accesorios.

<h3 id="sec-9-3">9.3. Nuevo / Editar Robot</h3>

Campos: Marca (obligatorio), Modelo (obligatorio) y Notas.

<h3 id="sec-9-4">9.4. Importar Robots</h3>

Vía archivo TXT o mediante pegado de texto plano con formato: `ROBOT: nombre / MARCA: marca / ACCESORIOS:`.

<h3 id="sec-9-5">9.5. Papelera</h3>

Sección para recuperar o purgar robots desactivados.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-10">10. Planificación</h2>

<h3 id="sec-10-1">10.1. Plan Semanal</h3>

Vista tipo cuadrícula horizontal de 7 días:
- **Comida ☀️:** Slots para 1er plato, 2do plato y postre.
- **Cena 🌙:** Slots para 1er plato, 2do plato y postre.
- Incluye el botón **Generar lista de la compra** directamente desde el plan.

<h3 id="sec-10-2">10.2. Listas de la Compra</h3>

Listado de items con toggles para marcar productos comprados, comparador de precios inter-supermercados y exportación a PDF o conversión a **Compra**.

<h3 id="sec-10-3">10.3. Comparador de Precios (Matriz)</h3>

Matriz comparativa de productos frente a hasta 3 supermercados para calcular cuál es el carro de la compra más económico.

[⬆ Volver al índice](#indice)

---

<h2 id="sec-11">11. Comercio en Línea</h2>

<h3 id="sec-11-1">11.1. Pedidos</h3>

Listado con seguimiento de pedidos por plataforma y badges de estado:
- 🟡 **Amarillo:** Pendiente / Confirmado / Preparando
- 🔵 **Azul:** Enviado / En reparto
- 🟢 **Verde:** Entregado / Reembolsado
- 🔴 **Rojo:** Cancelado / Devuelto

<h3 id="sec-11-2">11.2. Detalle de Pedido</h3>

Vista completa con importes, flujo de estados, artículos asociados y códigos de seguimiento (trackings).
