📚 Índice
Logotipo
Incidencias
Pull Requests
Hitos
Explorar
enri
/
gestiondelhogardeep
Privado
Código
Incidencias33
Pull Requests
Acciones
Paquetes
Proyectos2
Lanzamientos4
Wiki
Actividad
Guia de Usuario
enri editó esta página hace 11 horas
Este archivo contiene caracteres Unicode ambiguos

Este archivo contiene caracteres Unicode que pueden confundirse con otros caracteres. Si crees que esto es intencional, puedes ignorar esta advertencia. Usa el botón de Escape para revelarlos.

📖 Manual de Usuario — Gestión Casa v5.0

Versión: 5.0
Fecha: 12 de agosto de 2026
Propósito: Guía completa para el uso diario de la aplicación de gestión del hogar.

📚 Índice

Dashboard

Compras

Stock

Recetas

Productos

Supermercados

Finanzas

Técnicas de Cocina

Robots de Cocina

Planificación

Comercio en Línea

Salud

Mascotas

    Dashboard

El Dashboard es la pantalla principal tras iniciar sesión. Te ofrece una vista general de tu hogar con alertas, accesos rápidos y resúmenes. 1.1. Barra superior de contexto

Nada más entrar, bajo el menú, verás una barra con:

Nombre de la casa activa (ej: "Casa principal")

Schema técnico (para referencia)

Selector de casa: Si gestionas varias casas, puedes cambiar entre ellas

⚠️ Si ves "Sin casa seleccionada", debes crear o seleccionar una casa antes de continuar.

1.2. Widgets de alerta

Son 6 tarjetas que te avisan de un vistazo: Widget ¿Qué indica? Caducan pronto Productos próximos a caducar. Si hay, muestra el número y un botón para revisarlos Stock bajo Productos por debajo del mínimo. Si hay, te lleva a la despensa filtrada Gastos del mes Total acumulado del mes actual. Enlace a todos los movimientos Próximas comidas Número de comidas planificadas. Enlace al plan semanal Pedidos en curso Pedidos online pendientes de recibir En reparto Pedidos que ya están en camino 1.3. Acciones rápidas

Seis botones grandes para las operaciones más frecuentes: Botón Acción Nueva compra Registrar un ticket Nueva receta Crear receta desde cero Plan semanal Planificar comidas Nuevo pedido Pedido en comercio online Movimiento Registrar gasto/ingreso Robots Acceder a tus robots de cocina 1.4. Cargos periódicos pendientes

Si hay gastos automáticos programados para hoy (como suscripciones), verás un aviso para Generarlos o Ignorarlos. 1.5. Tablas de resumen Tabla Contenido Próximas comidas Fecha, tipo (comida/cena), receta y número de comensales Últimas compras Fecha, supermercado y total de cada compra reciente 1.6. Listas de compra activas

Muestra las listas de compra que tienes pendientes, con el número de items en cada una. 1.7. Personalizar el dashboard

Haz clic en Personalizar (arriba a la derecha) para abrir un panel donde puedes activar o desactivar los widgets que quieres ver. Los cambios se guardan por usuario. 2. Compras 2.1. Histórico de Tickets

Es el listado principal de todas tus compras.

Información mostrada: Columna Descripción ID Número único de la compra Fecha Día de la compra Supermercado Dónde compraste Total Importe total en negrita Estado Borrador 🟡 / Confirmada 🟢 / Anulada 🔴

Total general: Sobre la tabla ves el total acumulado de todas las compras.

Acciones por compra: Icono Acción ¿Cuándo aparece? 👁️ Ver Abre el detalle Siempre ✅ Confirmar Pasa a confirmada Solo en borrador ↩️ Desconfirmar Vuelve a borrador Solo en confirmada 🗑️ Anular Marca como anulada Siempre 2.2. Nueva Compra

Para crear una compra manualmente:

Ve a Compras → Nueva compra

Selecciona la fecha y el supermercado

Pulsa Crear compra y añadir líneas

Te llevará al detalle de la compra en estado borrador para añadir productos

2.3. Detalle de Compra

Cabecera: Número de compra y estado. Datos principales: fecha, supermercado, total.

Estados: Estado ¿Qué puedo hacer? Borrador Añadir/quitar/editar líneas, escanear EAN, confirmar Confirmada Solo consulta. Desconfirmar o anular Anulada Solo consulta

Añadir productos (solo en borrador): A) Escanear código de barras

Pasa el lector EAN o escribe el código manualmente

Si el EAN existe, se añade automáticamente

Si no existe, puedes crearlo al vuelo

B) Crear producto nuevo (botón naranja)

Modal rápido donde rellenas: Campo Obligatorio Nombre ✅ Tipo ❌ Unidad base ✅ Cantidad ❌ Precio ❌ EAN ❌ Caducidad ❌ Alias en ticket ❌ No gestionar stock ❌ C) Añadir producto existente (botón azul)

Buscas un producto de tu base de datos y configuras:

Cantidad de envases

Precio por envase o por unidad

Unidades por pack

Caducidad y notas

Hasta 3 niveles de descuento (% o €)

Dos modos: Añadir y cerrar o Añadir y seguir

Tabla de líneas: Columna Descripción Producto Nombre y notas Cantidad Nº de envases Uds/envase Desglose de unidades Ud. base kg, L, ud... Caducidad Fecha si se informó Precio Unitario Dto. Descuentos aplicados Subtotal Importe final

Confirmar compra:

Selecciona método de pago

Pulsa Confirmar

La compra se confirma y actualiza el stock

2.4. Editar Línea

Al hacer clic en ✏️ en una línea, accedes al editor completo donde puedes modificar todos los campos. Los descuentos se recalculan en tiempo real con HTMX. 2.5. Gestión de Tickets (OCR)

Para digitalizar tickets físicos o digitales:

Ve a Compras → Gestionar tickets

Sube el archivo:

Tipo Formato 📷 Imagen Foto del ticket 📄 PDF Ticket de Mercadona 🌐 HTML Ticket de Lidl

Elige modo de procesado:

Modo Descripción Procesar OCR clásico Procesar con IA Más preciso (Ollama local)

Revisa los productos detectados en la tabla

Corrige nombres, cantidades o precios si es necesario

Selecciona fecha y supermercado

Pulsa Confirmar e importar

    Stock 3.1. Despensa

La despensa te muestra todos los productos que gestionan stock, con alertas visuales para que nada se te pase.

Filtros rápidos: Filtro ¿Qué muestra? Todos Todos los productos con gestión de stock Con stock Solo los que tienen cantidad > 0 Stock bajo Productos por debajo del mínimo Caduca pronto Productos con fecha de caducidad próxima

Tabla de productos: Columna Descripción Producto Nombre y badge "caduca" si es urgente Tipo Categoría del producto Unidades Nº de unidades/envases Cantidad Total en unidad base (kg, L, ud...) Mín Stock mínimo configurado Ideal Stock ideal configurado

Colores de alerta: Color Significado 🔴 Rojo Sin stock (y tenía mínimo) o producto que caduca pronto 🟡 Amarillo Stock por debajo del mínimo ⚪ Normal Todo correcto

Consumir producto:

Al hacer clic en Consumir se abre un modal donde puedes:

Elegir modo (si el producto tiene unidades):

    Por cantidad: introduces kg, L, etc.

    Por unidades: consumes envases enteros

Seleccionar fecha del consumo

Añadir notas (ej: "merienda niños")

3.2. Movimientos de Stock

Registro completo de todas las entradas y salidas de tu despensa.

Filtros disponibles: Filtro Opciones Producto Cualquiera de tu base de datos Tipo Todos / Entradas / Salidas Desde / Hasta Rango de fechas

Tabla de movimientos: Columna Descripción Fecha Día del movimiento Producto Enlace al detalle del producto Tipo 🟢 Entrada o 🔴 Salida Entrada Cantidad que entró Salida Cantidad que salió Existencias Stock acumulado tras el movimiento Precio ud. Precio por unidad base en ese momento Origen De dónde vino (compra, ajuste manual, receta...) 4. Recetas 4.1. Listado de Recetas

Accede desde Recetas → Ver todas.

Filtros:

Buscador por nombre

Tipo: Principal, Entrante, Postre

Dificultad: Fácil, Media, Difícil

Tarjetas de receta:

Cada receta muestra:

Nombre, tipo, dificultad, raciones, tiempo

Alerta de stock: 🟢 Todos disponibles o 🟡 Faltan X ingredientes

Acciones por receta: Botón Función 👁️ Ver Detalle completo 📋 Ficha Ficha de cocina imprimible ✏️ Editar Modificar datos 🗑️ Eliminar Borrar receta 4.2. Nueva Receta

Crea una receta desde cero con 4 pestañas: Pestaña Contenido Datos generales Nombre, tipo, dificultad, raciones, tiempos, robot, categorías, conservación Ingredientes Se añaden después, desde el detalle de la receta Elaboración Instrucciones generales. Los pasos por robot se añaden después Extra Alérgenos y etiquetas de colores

Tras guardar, accede al detalle para añadir ingredientes y pasos.

4.3. Detalle de Receta

La pantalla más completa, organizada en pestañas:

Pestaña Accesorios: Muestra los accesorios necesarios agrupados por robot.

Pestaña Ingredientes: Columna Descripción Ingrediente Nombre del producto Cantidad Ajustada al nº de comensales Stock Cantidad disponible en despensa Estado 🟢 OK / 🟡 Bajo / 🔴 Sin stock

Puedes cambiar el nº de comensales y las cantidades se recalculan automáticamente.

Pestaña Elaboración:

Pasos agrupados por robot con: Nº de paso, tiempo, temperatura, potencia, velocidad

Filtro para ver solo un robot

Pestaña Variantes: Si la receta tiene versiones alternativas.

Pestaña Nutrición: Tarjetas con: kcal, grasas, saturadas, hidratos, azúcares, fibra, proteínas, sal.

Botones de acción: Botón Función 🍳 Cocinar Descuenta los ingredientes del stock 🛒 Añadir faltantes Crea lista de compra con lo que falta 📋 Ficha cocina Versión imprimible ✏️ Editar datos Modificar receta 🗑️ Eliminar Borrar receta 4.4. Ficha de Cocina

Pantalla especial optimizada para cocinar:

Diseño en naranja con letra grande

Selector de robot: filtra los pasos por robot específico

Modo tradicional: muestra los pasos sin detalles técnicos

Botón Imprimir: para llevarlo en papel a la cocina

Muestra accesorios, ingredientes (con alertas de stock), pasos y nutrición

4.5. ¿Qué puedo cocinar?

Sugerencias basadas en tu stock actual: Sección Descripción 🟢 Recetas disponibles Tienes todos los ingredientes. Puedes cocinar ya 🟡 Casi disponibles Te falta algún ingrediente. Muestra % y botón para añadir faltantes 4.6. Importar Recetas

Importar una receta:

Pega el texto de la receta o sube un archivo (TXT, MD, PDF)

Previsualiza los datos detectados

Confirma y la receta se crea automáticamente

Importar en lote:

Coloca archivos en la carpeta docs/Recetas pendientes/

El sistema los procesa todos de una vez

Muestra resultados: OK, errores, ignorados

4.7. Accesorios de Cocina

Gestión de utensilios y accesorios:

Listado en tarjetas con nombre y descripción

Crear, editar y eliminar accesorios

Se asignan a las recetas para saber qué necesitas

    Productos 5.1. Listado de Productos

Accede desde Productos → Ver todos.

Barra de acciones: Botón Función Tipos Gestionar categorías de productos Conversiones Gestionar equivalencias de unidades Unidades Gestionar unidades de medida Importar alimentos Carga masiva desde archivo MD Papelera Ver productos desactivados

Filtros: Filtro Descripción Buscador Busca por nombre del producto o por alias Tipo Filtra por categoría (lácteos, verduras, carnes...)

Tabla de productos: Columna Descripción Producto Nombre en azul (enlace al detalle) + alias debajo Tipo Categoría del producto Stock Badge de color: 🟢 OK / 🟡 Bajo mínimo / 🔴 Sin stock Formatos Número de códigos EAN registrados Consumir Botón rápido para descontar stock (solo si hay stock) Acciones 👁️ Ver, ✏️ Editar, 🗑️ Desactivar

Papelera: Productos desactivados. Puedes reactivar, eliminar definitivamente o vaciar papelera. 5.2. Detalle de Producto

Al hacer clic en un producto accedes a su ficha completa con 5 pestañas:

Cabecera: Unidad base, stock actual (con color de alerta), stock mínimo/ideal, precio mínimo, precio medio y precio máximo.

Pestaña 1: Información Campo Descripción Nombre Nombre del producto Tipo Categoría Unidad base kg, L, ud, g, ml... Caducidad estimada Días que dura desde la compra Densidad g/ml para conversiones peso/volumen Stock mínimo / ideal Umbrales de aviso y reposición Notas Información adicional Alias Nombres alternativos (como aparece en tickets)

Pestaña 2: Formatos EAN

Muestra los códigos de barras registrados, agrupados por supermercado. Columna Descripción EAN Código de barras (13 dígitos) Alias ticket Cómo aparece en el ticket del súper Formato Cantidad total en unidad base (ej: 1.5 kg) Precio Precio del pack/envase Precio/ud base Precio por kg, L o unidad

Pestaña 3: Stock

Muestra los lotes activos del producto. Columna Descripción Cantidad En unidad base Unidades Nº de envases Caducidad Fecha de caducidad Días Días restantes (rojo si ≤ 3) Entrada Fecha de entrada al stock Precio ud. Precio unitario Total Valor total del lote

Pestaña 4: Historial

Muestra las últimas compras del producto: fecha, súper, cantidad, precio.

Pestaña 5: Movimientos

Registro de entradas y salidas de stock del producto: fecha, tipo, cantidad, precio, origen. 5.3. Comparador de Precios

Accede desde el menú Productos → Comparador.

Filtros: Filtro Descripción Producto Uno concreto o todos Supermercados Checkboxes para seleccionar varios Tipo Categoría de producto

Tabla comparativa: Columna Descripción Producto Con badge 🏆 "Mejor" en el más barato Supermercado Dónde se vende Formato Uds por envase Precio pack Precio total del envase Precio/ud base Precio por kg, L o ud (el dato clave para comparar)

La fila del producto con mejor precio se resalta en verde. 5.4. Tipos de Producto

Gestión de categorías desde Productos → Tipos.

Cada tipo tiene:

Nombre (ej: Lácteos y huevos, Verduras, Carnes...)

Icono de Bootstrap Icons (ej: bi bi-egg, bi bi-flower1)

Acciones: Nuevo, Editar, Eliminar (con aviso si hay productos asociados). 5.5. Unidades de Medida

Gestión desde Productos → Unidades.

Cada unidad tiene:

Nombre (ej: Kilogramo, Litro, Unidad)

Abreviatura (kg, L, ud)

Tipo: Peso, Volumen u Otro

Acciones: Nueva, Editar, Eliminar (con aviso si hay productos que la usan). 5.6. Conversiones de Unidades

Gestión desde Productos → Conversiones.

Permite definir equivalencias como:

1 cucharada = 7.8 g de harina

1 taza = 240 ml de leche

Listado: Columna Descripción Alimento Nombre del alimento Equivalencias Badges con cada conversión Destino Unidad de destino (g o ml) 5.7. Importar Alimentos Básicos

Carga masiva de productos desde un archivo Markdown con formato tabla. 6. Supermercados 6.1. Listado de Supermercados

Accede desde Supermercados. Se muestran en tarjetas con:

Nombre, tipo, ciudad, dirección

Nº de formatos EAN registrados

Badges de servicios (parking, wifi...)

Acciones por supermercado: Botón Función 👁️ Detalle Ficha completa ✏️ Editar Modificar datos 🗑️ Eliminar Desactivar (va a papelera)

Barra superior: Botón Función Festivos Calendario de festivos Nuevo Crear supermercado Papelera Recuperar o eliminar definitivamente 6.2. Detalle de Supermercado

Organizado en 3 pestañas:

Información: Datos generales, servicios, puntos de recogida. Modales para añadir servicios y puntos de recogida.

Horarios:

Horario general por días de la semana

Festivos con fechas especiales

Modal de horario con selección múltiple de días (Todos, L-V, S-D)

Estadísticas:

Gastos mensuales del año (bruto, descuentos, neto)

Formatos EAN registrados en ese supermercado

6.3. Calendario de Festivos

Gestión centralizada de festivos (Navidad, Año Nuevo...). Columna Descripción Fecha Día festivo Nombre Descripción Tipo 🔴 Estatal / 🟡 Autonómica / 🔵 Local

Acciones: Acción Descripción Aplicar Asigna el festivo a todos los supermercados Aplicar todos Asigna todos los festivos a todos los supermercados Importar calendario Desde archivo MD/TXT 6.4. Crear/Editar Supermercado Campo Obligatorio Nombre ✅ Tipo ✅ Ciudad ✅ Dirección ❌ Teléfono ❌ Email ❌ Web ❌ Método de pago por defecto ❌ (se preselecciona al confirmar compras) 7. Finanzas 7.1. Movimientos

El corazón financiero. Accede desde Finanzas → Movimientos.

Resumen superior: Tres tarjetas: Gastos (rojo), Ingresos (verde) y Balance (azul).

Barra de acciones: Botón Función Conciliar Vincula compras con movimientos bancarios Liquidaciones Gestión de ciclos de tarjeta

Filtros: Filtro Opciones Desde / Hasta Rango de fechas Tipo Todos / Gastos / Ingresos Cuenta Filtrar por cuenta bancaria Conciliado Todos / Verificados / Pendientes

Tabla de movimientos: Columna Descripción Fecha Día del movimiento F. Cargo Fecha de cargo en cuenta Concepto Descripción Importe Rojo (gasto) o verde (ingreso) Cuenta Cuenta asociada Método Método de pago Verificado Toggle para marcar conciliado

Acciones por movimiento: Icono Acción 📋 Duplicar — Crea una copia para otro mes ✏️ Editar — Modificar cualquier campo 🗑️ Eliminar — Borrar movimiento 7.2. Conciliación Bancaria

Accede desde Finanzas → Conciliar.

Pantalla dividida en dos columnas:

Columna izquierda: Pendientes de conciliar Sección Contenido 🟡 Compras sin conciliar Compras registradas sin movimiento bancario. Sugiere movimientos coincidentes 🔵 Pedidos sin conciliar Pedidos online sin conciliar

Columna derecha: Movimientos sin conciliar Sección Contenido 🔵 Movimientos sin conciliar Movimientos bancarios sin compra vinculada. Sugiere compras coincidentes

Acciones:

Vincular — Asocia una compra con su movimiento bancario

Marcar conciliado — Marca manualmente sin vincular

Historial de conciliaciones: Compra, movimiento, diferencia (rojo si ≠ 0), estado, fecha. 7.3. Bancos

Accede desde Finanzas → Bancos.

Listado: Tarjetas con: icono del banco, nombre, país, nº de cuentas y tarjetas.

Detalle de banco (2 pestañas):

Info: nombre, código, país

Cuentas: tabla con alias, IBAN, saldo, tarjetas asociadas

Nuevo/Editar banco: nombre, código entidad (4 dígitos), país (código ISO). 7.4. Cuentas

Accede desde Finanzas → Cuentas.

Listado: Tarjetas con: alias, banco, IBAN, saldo actual en grande, nº de tarjetas.

Detalle de cuenta: banco, IBAN, saldo + tabla de tarjetas asociadas.

Nueva/Editar cuenta: banco, alias, IBAN, saldo actual. 7.5. Tarjetas

Accede desde Finanzas → Tarjetas.

Listado: Tarjetas con: icono (naranja si crédito), nombre, tipo, últimos 4 dígitos, banco, límite de crédito.

Detalle de tarjeta:

Nombre, tipo, últimos dígitos, cuenta asociada

Ciclo: día de corte y día de cargo

Límite de crédito: límite, dispuesto, disponible

Comparador App vs Extracto: dos columnas con movimientos de la app y del banco

Importar extracto: sube un PDF para comparar

Toggle de verificación y ocultación de coincidencias

Nueva/Editar tarjeta: cuenta, nombre, tipo (débito/crédito/prepago/virtual), límite de crédito, últimos 4 dígitos. 7.6. Liquidaciones de Tarjeta

Accede desde Finanzas → Liquidaciones.

Panel de tarjetas: Cada tarjeta muestra:

Ciclo configurado (corte y cargo)

Límite, crédito dispuesto, disponible

Última liquidación con estado y total

Acciones: Botón Función Ver detalle Ir al detalle de la tarjeta Configurar Ajustar día de corte y cargo Cerrar ciclo Crear una liquidación del período

Cerrar ciclo: Fechas sugeridas, conteo de movimientos y total del período.

Detalle de liquidación: Tarjeta, período, estado, total (editable) + tabla de movimientos.

Historial de liquidaciones: Tarjeta, período, total, estado, opción de revocar.

Pagar liquidación: Confirma el pago, genera un movimiento y cambia el estado a "Pagada". 7.7. Financiaciones

Accede desde Finanzas → Financiaciones.

Listado (13 columnas): Columna Descripción Tarjeta Nombre y últimos dígitos Fecha inicio Cuándo empieza Importe Total financiado Cuotas Nº total Cuota/mes Importe mensual Interés % y total Comisiones Total Pagadas / Restantes Progreso Pendiente Lo que falta por pagar Pagos Botón para ver historial

Las filas en verde indican que la financiación está completada.

Nueva/Editar financiación: JS que recalcula cuota mensual, comisiones y total a pagar.

Pagar cuota: Progreso (barra + %), importe, fecha, vinculación a movimiento existente.

Historial de pagos: Nº de cuota, fecha, importe, movimiento vinculado, opción de revertir. 7.8. Gastos Periódicos

Accede desde Finanzas → Gastos periódicos.

Listado: Columna Descripción Concepto Nombre del gasto Importe Cantidad Día Día de cobro Pago Tarjeta, cuenta o método Próx. renov. Mes/año próxima generación Último Mes/año última generación Activo Toggle para activar/desactivar

Nuevo/Editar: concepto, importe, día de cobro, periodicidad (1=mensual, 3=trimestral, 12=anual), fecha inicio, cuenta/tarjeta/método, notas.

Próximos cobros: Lista con checkboxes. Botón Generar movimientos marcados para crearlos todos de golpe. 7.9. Métodos de Pago

Accede desde Finanzas → Métodos de pago.

Tarjetas con icono personalizado (Bootstrap Icons), nombre y tarjeta asociada. Se usan al confirmar compras y en movimientos. 7.10. Previsión de Pagos

Accede desde Finanzas → Previsión.

Vista unificada de todo lo que viene en un período: Sección Contenido 🔵 Liquidaciones Pagos de tarjeta previstos 🟡 Financiaciones Cuotas de financiaciones 🟢 Gastos periódicos Suscripciones y recibos

Columna derecha: Total previsto en grande con desglose por tipo. Navegación por períodos con flechas < >. 8. Técnicas de Cocina 8.1. Listado de Técnicas

Accede desde Técnicas → Ver todas.

Filtros: Buscador por nombre y filtro por tipo.

Tarjetas de técnica: Nombre (enlace), tipo (badge), descripción truncada, badges de robots con variantes. 8.2. Nueva Técnica Campo Descripción Nombre Obligatorio Tipo Categoría de la técnica Descripción Explicación general Ingredientes Lista de ingredientes típicos

Tras guardar, añade variantes desde el detalle.

8.3. Detalle de Técnica

Columna izquierda: nombre, tipo, descripción, ingredientes, estado (activo/inactivo).

Columna derecha — Variantes por robot: Columna Descripción Robot Modelo del robot Accesorio Accesorio necesario Instrucciones Texto de la variante Tiempo En minutos Temp En °C Vel Velocidad Pot Potencia

Botones de acción: Añadir variante, Ficha, Editar, Eliminar. 8.4. Añadir / Editar Variante Campo Descripción Robot Obligatorio Accesorio Opcional Instrucciones Paso a paso Tiempo En minutos Temperatura En °C Velocidad Ej: 4 Potencia Ej: 8 Notas Información adicional 8.5. Ficha de Técnica

Versión imprimible:

Diseño oscuro (fondo gris azulado)

Selector de robot o modo tradicional

Modo tradicional: oculta badges técnicos

Botón Imprimir

8.6. Importar Técnica Método Cómo funciona Pegar texto Formato TECNICA: nombre / ROBOT: modelo... Subir archivo PDF, TXT o MD

Tras procesar, previsualización con datos detectados antes de guardar.

    Robots de Cocina 9.1. Listado de Robots

Accede desde Robots. Tarjetas con:

Icono del robot, marca y modelo

Nº de accesorios y estado (activo/inactivo)

Notas truncadas

Barra superior: Botón Función Importar Carga desde archivo TXT Nuevo robot Crear manualmente Papelera Robots desactivados 9.2. Detalle de Robot

Marca, modelo, estado, notas

Lista de accesorios con nombre y descripción

Modal para añadir accesorio

Cada accesorio: editar ✏️ o eliminar ✖️

9.3. Nuevo / Editar Robot Campo Descripción Marca Obligatorio Modelo Obligatorio Notas Información adicional 9.4. Importar Robots Método Cómo funciona Subir archivo TXT Se procesa automáticamente Pegar texto Formato: ROBOT: nombre / MARCA: marca / ACCESORIOS: 9.5. Papelera

Robots desactivados. Acciones: reactivar, eliminar definitivamente, vaciar papelera. 10. Planificación 10.1. Plan Semanal

Accede desde Planificación → Plan semanal.

Vista semanal: Scroll horizontal con 7 columnas (una por día). El día actual resaltado en azul.

Cada día muestra:

Comida ☀️: slots para 1er plato, 2do plato y postre

Cena 🌙: slots para 1er plato, 2do plato y postre

Cada slot: tipo, nombre de la receta (enlace), botones editar ✏️ y quitar ✖.

Añadir al plan: Modal con receta y comensales.

Generar lista de la compra: Botón que crea una lista a partir de los ingredientes del plan. 10.2. Listas de la Compra

Accede desde Planificación → Listas de compra.

Listado: Cada lista muestra nombre, supermercado, nº de items.

Tabla de items: Columna Descripción ✅ Toggle comprado/no comprado Producto Nombre Cant. Cantidad Formato Ej: 600 g Precio Precio unitario €/kg Precio por unidad base Súper Supermercado asignado Total Precio total

Acciones por lista: Botón Función ➕ Añadir item 🔲 Comparar precios (matriz) 🖨️ Imprimir PDF 🛒 Crear compra desde la lista ✏️ Editar lista 🗑️ Eliminar lista 10.3. Comparador de Precios (Matriz)

Accede desde una lista de compra.

Selecciona hasta 3 supermercados

Tabla con productos en filas y supermercados en columnas

Para cada producto/súper: formato y precio

Cálculo automático de €/unidad base

Total por supermercado al pie

Botón Guardar precios e Imprimir

    Comercio en Línea 11.1. Pedidos

Accede desde Comercio en Línea → Pedidos.

Listado: Columna Descripción Nº Pedido Enlace al detalle Plataforma Con icono Fecha Fecha del pedido Estado Badge de color Total Importe

Estados y colores: Estado Color Pendiente / Confirmado / Preparando 🟡 Amarillo Enviado / En reparto 🔵 Azul Entregado / Reembolsado 🟢 Verde Cancelado / Devuelto 🔴 Rojo

Acciones según estado: Estado actual Acciones Pendiente → En reparto Entregar Entregado Revertir entrega, Devolver Devuelto Reembolsar 11.2. Detalle de Pedido

Datos: plataforma, nº pedido, fechas, total, gastos envío, método de pago, dirección, URL.

Flujo de estados: text

Pendiente → Confirmado → Preparando → Enviado → En reparto → Entregado ↓ Devuelto → Reembolsado

Artículos (líneas): nombre, cantidad, precio, descuento, subtotal, estado, URL.

Cada línea: editar ✏️, devolver, reembolsar, eliminar 🗑️.

Añadir artículo: modal con artículo existente o nuevo + cantidad, precio, descuento, URL, estado, notas.

Trackings: transportista, nº seguimiento, estado, fecha estimada/real, bultos.

Añadir tracking: modal con transportista, nº seguimiento, URL, estado, bultos, fechas. 11.3. Nuevo / Editar Pedido

Plataforma, nº pedido, fechas, estado, total, gastos envío, nº artículos, URL, dirección, método de pago, notas. 11.4. Entregar Pedido

Confirma la entrega. Si tiene método de pago: crea movimiento bancario. Si es tarjeta de crédito: actualiza crédito dispuesto. 11.5. Devolver Pedido / Línea

Registra devolución con ticket/código y motivo. 11.6. Reembolsar Pedido / Línea

Pedido completo: importe y notas. Línea individual: importe y destino (cuenta o monedero). Crea movimiento de ingreso. 11.7. Importar Pedido

Pega el texto del email de confirmación. El sistema analiza y muestra previsualización para confirmar. 11.8. Pedido Amazon (OCR)

Sube captura de "Detalles del pedido" de Amazon. Extrae: nº pedido, fecha, método pago, productos. Tabla editable antes de confirmar. 11.9. Plataformas

Listado: icono, nombre, tipo (Marketplace/Tienda/Outlet/Fabricante directo/Segunda mano), web.

Nueva/Editar: nombre, icono, tipo, web, método de pago por defecto, notas.

Papelera: desactivar, reactivar, eliminar definitivamente. 11.10. Artículos

Catálogo de productos comprados online: nombre, marca, modelo, categoría, nº serie, garantía, notas. 11.11. Monederos Virtuales

Listado: nombre, plataforma, cuenta, saldo, divisa, caducidad.

Detalle: saldo + movimientos (entradas/salidas) con enlace al pedido.

Nuevo/Editar: nombre, plataforma, cuenta, saldo, divisa, caducidad, notas. 11.12. Estadísticas

KPIs: total del mes, nº pedidos, ticket medio, total anual.

Gráficos Chart.js: donut (gasto por plataforma) y barras (evolución 6 meses). 12. Salud 12.1. Vista Diaria

Accede desde Salud → Diario.

Navegación: flechas < >, selector de fecha, botón Hoy. La flecha derecha se desactiva en días futuros.

Barra de acciones: Botón Función Hoy Vista diaria Historial Todos los registros Configuración Ajustes del día Medicación Gestionar medicación fija Tipos dolor Configurar tipos de dolor Tomas Registrar constantes Evento Registrar un evento/síntoma Gráficos Ver evolución PDF Exportar el día a PDF

Escalas de referencia: Badge Rango Significado 🟢 0-2 Leve Dolor/estrés bajo 🟡 3-5 Moderado Atención media 🔴 6-8 Severo Atención alta ⚫ 9-10 Máximo Atención urgente

Configuración diaria: despertar, acostarse, horas sueño, IAH, temperatura (rojo >37.5°C, azul <36.0°C, verde normal), medicación variable, nota del día.

Medicación por turnos: Turno Color ☀️ Mañana Verde ☀️ Tarde Naranja 🌙 Noche Azul

Checkboxes para marcar tomas. Botón Guardar tomas.

Eventos del día: hora, dolor (intensidad 0-10, tipo, zona), síntomas (badges), constantes. Editar ✏️ y eliminar 🗑️.

Últimas tomas: badges con glucosa, TA, pulso, O₂, IAH. 12.2. Configuración Diaria

Horarios: despertar, acostarse, horas sueño.

Sueño: IAH, temperatura al despertar.

Medicación variable: pares dinámicos nombre-dosis (añadir/quitar filas).

Nota del día: texto libre. 12.3. Medicación Fija

Organizada por 4 turnos: Mañana 🟢, Tarde 🟠, Noche 🔵, Personalizado 🔷.

Cada medicamento: nombre, dosis, hora, badge del turno.

Acciones: Icono Acción ✏️ Editar inline (nombre, dosis, turno, hora) 🔔/🔕 Activar/silenciar notificaciones ⏻ Activar/desactivar

Agregar: formulario con nombre, dosis, turno, hora. 12.4. Tomas de Datos

Constantes: glucosa, TA sistólica/diastólica, pulso, O₂.

Apneas: IAH, obstructivas, centrales, mixtas, hipopneas, horas sueño, observaciones.

Notas: texto libre.

Historial de tomas: tabla con todas las métricas. Editar ✏️ y eliminar 🗑️. 12.5. Eventos

Dolor: intensidad 0-10, tipo (seleccionable), zona.

Síntomas (checkboxes): mareo, inestabilidad, náuseas, visión alterada, debilidad.

Constantes: glucosa, TA, pulso, O₂, temperatura.

Escalas (0-10): dolor, estrés, ánimo.

Notas: texto libre. 12.6. Tipos de Dolor

Catálogo personalizable: nombre, descripción, estado (activo/inactivo).

Acciones: editar inline ✏️, toggle activar/desactivar ⏻.

Agregar: formulario con nombre y descripción. 12.7. Gráficos

5 gráficos Chart.js: Gráfico Tipo Color 🩸 Glucosa Línea Rojo ❤️ Tensión Arterial Doble línea Rojo + Azul 💓 Pulso y O₂ Doble línea Naranja + Verde 😴 IAH Línea Morado 🕐 Horas de sueño Barras Azul 12.8. Historial

Tabla resumen: fecha, día semana, despertar/acostarse, horas sueño, temperatura (coloreada), medicación variable, IAH (badge: 🟢<5, 🟡<15, 🔴<30, ⚫≥30).

Acciones: ⚙️ configuración, ⚠️ eventos, 👁️ ver día. 12.9. PDF Diario

Documento imprimible con 4 secciones:

Configuración diaria

Medicación con checks (✓/⏳)

Tomas de datos

Eventos con constantes y escalas

    Mascotas 13.1. Panel de Mascotas

Accede desde Mascotas.

Tarjetas de mascota: Información Descripción Nombre Nombre de la mascota Especie Badge: Perro, Gato, Ave, Roedor, Reptil, Pez, Otro Raza Si está registrada Fecha nacimiento 🎂 Chip 🔍 Número de identificación Último peso ⚖️ Con fecha Próxima vacuna 🟡 Tipo y fecha Próxima desparasitación 🔵 Fecha

Acciones: 👁️ Detalle, ✏️ Editar, ⏻ Desactivar. 13.2. Nueva / Editar Mascota Campo Descripción Nombre Obligatorio Especie Perro, Gato, Ave, Roedor, Reptil, Pez, Otro Raza Texto libre Fecha de nacimiento Selector de fecha Chip Número de identificación Notas Texto libre 13.3. Ficha de la Mascota (Detalle)

Barra de acciones: Botón Función ⚖️ Peso Registrar nuevo peso 🛡️ Vacuna Registrar nueva vacuna 🐛 Desparasitar Registrar nueva desparasitación 🏥 Visita Registrar visita al veterinario 🥚 Alimento Registrar alimentación

Vacunas: tipo, fecha, próxima, veterinario. Editar ✏️, eliminar 🗑️.

Desparasitaciones: tipo (🟡 Interna / 🔵 Externa), fecha, próxima, producto. Editar ✏️, eliminar 🗑️.

Visitas: fecha, veterinario, motivo, coste (€). Editar ✏️, eliminar 🗑️.

Alimentación: producto, cantidad/día (g). Editar ✏️, toggle ⏻, eliminar 🗑️.

Columna derecha: datos generales + últimos 10 pesos. 13.4. Peso Campo Descripción Fecha Por defecto: hoy Peso (kg) Obligatorio, decimales Notas Texto libre 13.5. Vacunas Campo Descripción Tipo Texto libre (Rabia, Pentavalente...) Fecha Por defecto: hoy Próxima dosis Fecha siguiente Veterinario Quién la administró Notas Texto libre 13.6. Desparasitaciones Campo Descripción Tipo Interna / Externa Fecha Por defecto: hoy Próxima Fecha siguiente Producto Nombre del producto Notas Texto libre 13.7. Visitas al Veterinario Campo Descripción Fecha Por defecto: hoy Coste (€) Importe Veterinario / Clínica Profesional o centro Motivo Razón de la consulta Notas Texto libre 13.8. Alimentación Campo Descripción Producto / Alimento Obligatorio Cantidad diaria (g) Decimales Notas Texto libre 13.9. Gráficos de Peso

Gráfico de líneas Chart.js:

Evolución últimos 90 días

Una línea por mascota, cada una de un color

Eje Y: kg, Eje X: fechas

Leyenda con nombres

    Botiquín (Farmacia) 14.1. Panel Principal

Accede desde Botiquín en el menú principal. Alertas

El panel muestra alertas en la parte superior si hay medicamentos en situación crítica: Alerta Color ¿Cuándo aparece? Caducados 🔴 Rojo Medicamentos cuya fecha de caducidad ya ha pasado Caducan en ≤30 días 🟡 Amarillo Medicamentos que caducan en el próximo mes. Muestra los días restantes Stock bajo 🔵 Azul Medicamentos con pocas unidades (columna derecha) Todos los medicamentos

Tabla principal con: Columna Descripción Medicamento Nombre y dosis Principio Principio activo Stock Cantidad de cajas Caducidad Fecha de caducidad

Acciones por medicamento: Botón Función 👁️ Ver Ficha completa del medicamento ✏️ Editar Modificar datos

Los medicamentos inactivos aparecen atenuados (opacidad reducida).

Escanear

Botón en la columna derecha que abre el escáner de códigos Datamatrix para capturar datos directamente del envase. 14.2. Nuevo Medicamento

Formulario para registrar un medicamento en el botiquín: Campo Descripción Nombre Nombre comercial (obligatorio) Principio activo Sustancia activa del medicamento Dosis Concentración (ej: 650 mg) Forma Selector: Comprimido, Cápsula, Jarabe, Crema, Inyectable, Spray, Gotas, Supositorio, Otro Laboratorio Fabricante CN Código Nacional del medicamento Lote Número de lote Stock Cantidad de cajas (por defecto: 1) Fecha caducidad Selector de fecha Prospecto URL Enlace al prospecto online Notas Texto libre 14.3. Detalle del Medicamento

Accede desde el botón 👁️ en el panel principal. Barra de acciones Botón Función 💰 Añadir precio Registrar un precio de compra ✏️ Editar Modificar datos del medicamento ⏻ Toggle Activar/desactivar medicamento Datos del medicamento Campo Descripción Principio activo Sustancia activa Dosis Concentración Laboratorio Fabricante Forma Forma farmacéutica CN Código Nacional Lote Número de lote Caducidad Fecha con color: 🔴 caducado, 🟡 ≤30 días, 🟢 vigente Stock Cantidad de cajas Notas Información adicional Historial de precios

Tabla con todos los precios registrados: Columna Descripción Fecha Día del registro Farmacia Dónde se compró Precio En euros (€)

Acciones: ✏️ Editar, 🗑️ Eliminar (con confirmación). 14.4. Editar Medicamento

Mismo formulario que Nuevo Medicamento con todos los campos precargados. Incluye todos los campos: nombre, principio activo, dosis, forma farmacéutica, laboratorio, CN, lote, stock, fecha caducidad, prospecto URL y notas. 14.5. Escanear Datamatrix

Accede desde el botón Escanear en el panel principal. Funcionamiento

La página activa la cámara del dispositivo

Apunta al código Datamatrix del envase del medicamento

Al detectar el código, muestra el contenido en pantalla

Los datos quedan listos para copiar al formulario de nuevo medicamento

⚠️ Requiere conexión HTTPS para acceder a la cámara.

Resultado

Muestra el código detectado en formato texto para que puedas trasladarlo manualmente a los campos correspondientes del formulario. 14.6. Añadir Precio

Accede desde el detalle del medicamento (botón 💰). Campo Descripción Farmacia Nombre de la farmacia donde se compró Fecha Día de la compra (por defecto: hoy) Precio (€) Importe en euros (obligatorio, permite decimales) Notas Texto libre 14.7. Editar Precio

Mismo formulario que Añadir Precio con los datos precargados: farmacia, fecha, precio y notas.

    Mantenimiento 15.1. Panel Principal

Accede desde Mantenimiento en el menú principal. Barra superior Botón Función 🛡️ Seguros Gestión de pólizas ➕ Elemento Añadir un nuevo electrodoméstico o elemento del hogar Alertas Alerta Color ¿Cuándo aparece? Próximas revisiones 🟡 Amarillo Revisiones programadas con fecha próxima Garantías expiran 🟢 Verde Garantías a punto de vencer (columna derecha) Elementos del hogar

Tabla principal con: Columna Descripción Nombre Nombre del elemento + marca Tipo Categoría (electrodoméstico, instalación...) Garantía Fecha de vencimiento

Acciones por elemento: Botón Función 👁️ Ver Detalle completo ✏️ Editar Modificar datos ⏻ Desactivar Ocultar elemento Estadísticas

Botón en columna derecha que abre el gráfico de gastos. 15.2. Nuevo / Editar Elemento Campo Descripción Nombre Obligatorio (ej: "Caldera", "Frigorífico") Tipo Selector: Electrodoméstico, Calefacción, Fontanería, Electricidad, Gas, Otro Marca Fabricante Modelo Modelo específico Fecha compra Día de adquisición Garantía hasta Fecha de vencimiento Vida útil En años Notas Texto libre 15.3. Detalle del Elemento Barra de acciones Botón Función 🕐 Revisión Registrar una nueva revisión 🔧 Reparación Registrar una nueva reparación ✏️ Editar Modificar datos del elemento Datos del elemento Campo Descripción Marca Fabricante Modelo Modelo específico Tipo Categoría Compra Fecha de adquisición Garantía Vencimiento Vida útil En años Notas Información adicional Revisiones

Tabla con: Columna Descripción Fecha Día de la revisión Tipo Tipo de revisión Próxima Fecha programada Coste En euros (€)

Acciones: ✏️ Editar, 🗑️ Eliminar. Reparaciones

Tabla con: Columna Descripción Fecha Día de la reparación Técnico Profesional o empresa Coste En euros (€) Estado 🟢 Resuelto / 🟡 Pendiente

Acciones: ✏️ Editar, 🗑️ Eliminar. 15.4. Revisiones Nueva / Editar Revisión Campo Descripción Tipo Selector de tipo de revisión Fecha Día de la revisión (por defecto: hoy) Próxima Fecha programada para la siguiente Técnico Profesional que la realizó Coste En euros (€) Notas Texto libre 15.5. Reparaciones Nueva / Editar Reparación Campo Descripción Fecha Día de la reparación (por defecto: hoy) Coste En euros (€) Técnico / Empresa Quién la realizó Descripción del problema Qué fallaba Resuelto Checkbox (marcado por defecto en nueva) Notas Texto libre 15.6. Seguros

Accede desde Seguros en la barra superior. Próximas renovaciones

Alerta amarilla con los seguros que renuevan pronto: Columna Descripción Tipo Tipo de seguro Compañía Aseguradora Fecha Fecha de renovación Todos los seguros

Tabla completa: Columna Descripción Tipo Hogar, Vida, Salud, Decesos... Compañía Aseguradora Póliza Número de póliza Renovación Fecha Prima Importe en € Periodicidad Mensual, Trimestral, Semestral, Anual

Acciones: ✏️ Editar, ⏻ Toggle activar/desactivar, 🗑️ Eliminar. Nuevo / Editar Seguro Campo Descripción Tipo de seguro Texto libre (por defecto: "Hogar") Compañía Obligatorio Póliza Número de póliza Fecha renovación Obligatorio Prima (€) Importe Periodicidad Mensual/Trimestral/Semestral/Anual (por defecto: Anual) Cobertura Texto libre Notas Texto libre 15.7. Gráficos de Gastos

Accede desde el botón Gastos por elemento del panel principal.

Gráfico de barras con Chart.js:

Eje X: nombres de los elementos

Eje Y: gasto total en €

Color: naranja

🏠 Inicio

    📄 Home

📅 Desarrollo

    📅 Historial de Desarrollo
    🐛 Registro de Bugs

📖 Documentación

    🏗️ Arquitectura
    🌐 Acceso Exterior
    📋 Reglas de Diseño
    🚀 Guía de Instalación
    📖 Guía de Usuario
    🔧 Soluciones
    📊 Estructura de la Base de Datos
    📋 Procedimientos
    📋 Plan Migración v5.0

📋 Roadmap

    📋 Mejoras Pendientes
    🗺️ Roadmap v5.0
    🗺️ Plan Maestro

🛠️ Ayuda

    📖 Guía de Usuario
    🔧 Soluciones

Impulsado por Gitea
Versión:
1.23.1
Página:
88ms
Plantilla:
4ms
Licencias
API
