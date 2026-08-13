# 📖 Manual de Usuario — Gestión Casa v5.0

**Versión:** 5.0  
**Fecha:** 12 de agosto de 2026  
**Propósito:** Guía completa para el uso diario de la aplicación de gestión del hogar.

---

## 📚 Índice

1. Dashboard
2. Compras
3. Stock
4. Recetas
5. Productos
6. Supermercados
7. Finanzas
8. Técnicas de Cocina
9. Robots de Cocina
10. Planificación
11. Comercio en Línea
12. Salud
13. Mascotas
14. Botiquín
15. Mantenimiento

---

## 1. Dashboard

El Dashboard es la pantalla principal tras iniciar sesión. Ofrece una vista general del hogar con alertas, accesos rápidos y resúmenes.

### 1.1. Barra superior de contexto

Nada más entrar, bajo el menú, verás una barra con:

- Nombre de la casa activa (ej: "Casa principal")
- Schema técnico (para referencia)
- Selector de casa: Si gestionas varias casas, puedes cambiar entre ellas
- ⚠️ Si ves "Sin casa seleccionada", debes crear o seleccionar una casa antes de continuar.

### 1.2. Widgets de alerta

Son 6 tarjetas que avisan de un vistazo:

| Widget | ¿Qué indica? |
|--------|--------------|
| Caducan pronto | Productos próximos a caducar |
| Stock bajo | Productos por debajo del mínimo |
| Gastos del mes | Total acumulado del mes actual |
| Próximas comidas | Número de comidas planificadas |
| Pedidos en curso | Pedidos online pendientes de recibir |
| En reparto | Pedidos que ya están en camino |

### 1.3. Acciones rápidas

Seis botones grandes para las operaciones más frecuentes:

| Botón | Acción |
|-------|--------|
| Nueva compra | Registrar un ticket |
| Nueva receta | Crear receta desde cero |
| Plan semanal | Planificar comidas |
| Nuevo pedido | Pedido en comercio online |
| Movimiento | Registrar gasto/ingreso |
| Robots | Acceder a los robots de cocina |

### 1.4. Cargos periódicos pendientes

Si hay gastos automáticos programados para hoy, se muestra un aviso para generarlos o ignorarlos.

### 1.5. Tablas de resumen

| Tabla | Contenido |
|-------|-----------|
| Próximas comidas | Fecha, tipo, receta y comensales |
| Últimas compras | Fecha, supermercado y total |

### 1.6. Listas de compra activas

Muestra las listas de compra pendientes con el número de items.

### 1.7. Personalizar el dashboard

Haz clic en **Personalizar** para activar o desactivar widgets. Los cambios se guardan por usuario.

---

## 2. Compras

### 2.1. Histórico de Tickets

Listado principal de todas las compras.

| Columna | Descripción |
|---------|-------------|
| ID | Número único de la compra |
| Fecha | Día de la compra |
| Supermercado | Dónde se compró |
| Total | Importe total |
| Estado | Borrador / Confirmada / Anulada |

Acciones por compra: ver, confirmar, desconfirmar o anular.

### 2.2. Nueva Compra

1. Ve a **Compras → Nueva compra**
2. Selecciona fecha y supermercado
3. Pulsa **Crear compra y añadir líneas**

### 2.3. Detalle de Compra

Cabecera con número de compra y estado.

| Estado | Acciones posibles |
|--------|-------------------|
| Borrador | Añadir, quitar, editar líneas |
| Confirmada | Solo consulta |
| Anulada | Solo consulta |

Se pueden añadir productos por código EAN, producto nuevo o producto existente.

### 2.4. Editar Línea

Permite modificar todos los campos de una línea. Los descuentos se recalculan en tiempo real.

### 2.5. Gestión de Tickets (OCR)

Para digitalizar tickets físicos o digitales:

1. Ve a **Compras → Gestionar tickets**
2. Sube el archivo (imagen, PDF o HTML)
3. Elige modo de procesado
4. Revisa los productos detectados
5. Confirma e importa

---

## 3. Stock

### 3.1. Despensa

Muestra todos los productos que gestionan stock, con alertas visuales.

Filtros rápidos: todos, con stock, stock bajo, caduca pronto.

| Color | Significado |
|-------|-------------|
| 🔴 Rojo | Sin stock o caduca pronto |
| 🟡 Amarillo | Stock por debajo del mínimo |
| ⚪ Normal | Todo correcto |

### 3.2. Movimientos de Stock

Registro completo de entradas y salidas de la despensa.

---

## 4. Recetas

### 4.1. Listado de Recetas

Filtros por nombre, tipo y dificultad. Cada receta muestra alerta de stock.

### 4.2. Nueva Receta

Creación desde cero con 4 pestañas: datos generales, ingredientes, elaboración y extra.

### 4.3. Detalle de Receta

Pestañas: accesorios, ingredientes, elaboración, variantes y nutrición.

### 4.4. Ficha de Cocina

Pantalla optimizada para cocinar, con modo tradicional y botón de imprimir.

### 4.5. ¿Qué puedo cocinar?

Sugerencias según stock disponible.

### 4.6. Importar Recetas

Desde texto o archivo. También en lote.

### 4.7. Accesorios de Cocina

Gestión de utensilios y accesorios.

---

## 5. Productos

### 5.1. Listado de Productos

Filtros por nombre, alias y tipo.

### 5.2. Detalle de Producto

Ficha completa con 5 pestañas: información, formatos EAN, stock, historial y movimientos.

### 5.3. Comparador de Precios

Compara precios entre supermercados.

### 5.4. Tipos de Producto

Gestión de categorías.

### 5.5. Unidades de Medida

Gestión de unidades.

### 5.6. Conversiones de Unidades

Equivalencias entre unidades.

### 5.7. Importar Alimentos Básicos

Carga masiva desde archivo Markdown.

---

## 6. Supermercados

### 6.1. Listado de Supermercados

Tarjetas con nombre, tipo, ciudad y servicios.

### 6.2. Detalle de Supermercado

Información, horarios y estadísticas.

### 6.3. Calendario de Festivos

Gestión centralizada de festivos.

### 6.4. Crear/Editar Supermercado

Formulario con datos generales y método de pago.

---

## 7. Finanzas

### 7.1. Movimientos

Resumen de gastos, ingresos y balance.

### 7.2. Conciliación Bancaria

Vinculación entre compras y movimientos bancarios.

### 7.3. Bancos

Gestión de bancos.

### 7.4. Cuentas

Gestión de cuentas bancarias.

### 7.5. Tarjetas

Gestión de tarjetas de crédito y débito.

### 7.6. Liquidaciones de Tarjeta

Gestión de ciclos de tarjeta.

### 7.7. Financiaciones

Control de compras financiadas.

### 7.8. Gastos Periódicos

Gastos automáticos programados.

### 7.9. Métodos de Pago

Gestión de métodos de pago.

### 7.10. Previsión de Pagos

Vista unificada de pagos futuros.

---

## 8. Técnicas de Cocina

### 8.1. Listado de Técnicas

Filtros por nombre y tipo.

### 8.2. Nueva Técnica

Formulario con nombre, tipo, descripción e ingredientes.

### 8.3. Detalle de Técnica

Descripción y variantes por robot.

### 8.4. Añadir / Editar Variante

Formulario con robot, accesorio, instrucciones, tiempo, temperatura, velocidad y potencia.

### 8.5. Ficha de Técnica

Versión imprimible.

### 8.6. Importar Técnica

Desde texto o archivo.

---

## 9. Robots de Cocina

### 9.1. Listado de Robots

Tarjetas con marca, modelo y accesorios.

### 9.2. Detalle de Robot

Marca, modelo, estado y accesorios.

### 9.3. Nuevo / Editar Robot

Formulario con marca y modelo.

### 9.4. Importar Robots

Desde archivo TXT o texto.

### 9.5. Papelera

Robots desactivados.

---

## 10. Planificación

### 10.1. Plan Semanal

Vista semanal con comidas y cenas.

### 10.2. Listas de la Compra

Listas con items, precios y supermercado.

### 10.3. Comparador de Precios (Matriz)

Comparación entre supermercados.

---

## 11. Comercio en Línea

### 11.1. Pedidos

Listado con estados y colores.

### 11.2. Detalle de Pedido

Datos, flujo de estados, artículos y trackings.

### 11.3. Nuevo / Editar Pedido

Formulario completo.

### 11.4. Entregar Pedido

Confirmación de entrega.

### 11.5. Devolver Pedido / Línea

Registro de devoluciones.

### 11.6. Reembolsar Pedido / Línea

Registro de reembolsos.

### 11.7. Importar Pedido

Desde email de confirmación.

### 11.8. Pedido Amazon (OCR)

Desde captura de Amazon.

### 11.9. Plataformas

Gestión de plataformas online.

### 11.10. Artículos

Catálogo de productos comprados online.

### 11.11. Monederos Virtuales

Gestión de saldos virtuales.

### 11.12. Estadísticas

KPIs y gráficos.

---

## 12. Salud

### 12.1. Vista Diaria

Navegación por fechas, configuración diaria, medicación por turnos, eventos y constantes.

### 12.2. Configuración Diaria

Horarios, sueño, medicación variable y notas.

### 12.3. Medicación Fija

Organizada por turnos.

### 12.4. Tomas de Datos

Constantes, apneas y notas.

### 12.5. Eventos

Dolor, síntomas, constantes y escalas.

### 12.6. Tipos de Dolor

Catálogo personalizable.

### 12.7. Gráficos

Glucosa, tensión, pulso, IAH y sueño.

### 12.8. Historial

Tabla resumen por días.

### 12.9. PDF Diario

Documento imprimible.

---

## 13. Mascotas

### 13.1. Panel de Mascotas

Tarjetas con información principal.

### 13.2. Nueva / Editar Mascota

Formulario con nombre, especie, raza, fecha y chip.

### 13.3. Ficha de la Mascota

Vacunas, desparasitaciones, visitas, alimentación y pesos.

### 13.4. Peso

Registro de peso.

### 13.5. Vacunas

Registro de vacunas.

### 13.6. Desparasitaciones

Registro de desparasitaciones.

### 13.7. Visitas al Veterinario

Registro de visitas.

### 13.8. Alimentación

Registro de alimentación.

### 13.9. Gráficos de Peso

Evolución de peso.

---

## 14. Botiquín (Farmacia)

### 14.1. Panel Principal

Alertas y listado de medicamentos.

### 14.2. Nuevo Medicamento

Formulario completo.

### 14.3. Detalle del Medicamento

Datos e historial de precios.

### 14.4. Editar Medicamento

Formulario con datos precargados.

### 14.5. Escanear Datamatrix

Escáner de códigos.

### 14.6. Añadir Precio

Registro de precios.

### 14.7. Editar Precio

Modificación de precios.

---

## 15. Mantenimiento

### 15.1. Panel Principal

Alertas y elementos del hogar.

### 15.2. Nuevo / Editar Elemento

Formulario completo.

### 15.3. Detalle del Elemento

Datos, revisiones y reparaciones.

### 15.4. Revisiones

Registro de revisiones.

### 15.5. Reparaciones

Registro de reparaciones.

### 15.6. Seguros

Gestión de pólizas.

### 15.7. Gráficos de Gastos

Gastos por elemento.

---

## 👤 Autor

Desarrollado por **Enri** con la asistencia de **DeepSeek**.
