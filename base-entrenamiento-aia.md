# MANUAL OPERATIVO DE LA PLATAFORMA AIA
## Guía para Managers, Drivers, Regional Managers y Colaboradores

**Versión 1.0 — Actualizada en mayo de 2026**
**AIA Technology Inc.**

---

## 1. INTRODUCCIÓN Y FILOSOFÍA OPERATIVA

Bienvenido a AIA. Este manual tiene como objetivo presentar los procedimientos operativos, criterios de decisión y mejores prácticas para utilizar la plataforma AIA en tu día a día.

AIA es la plataforma integrada de gestión para restaurantes y operaciones de catering, diseñada para unificar pedidos dine-in, takeout, delivery y catering en una sola herramienta. Nuestra misión es que cada operador, desde el driver hasta el regional manager, tenga la información que necesita en el momento exacto en que la necesita.

Nuestros principios operativos son: **claridad operativa por encima del volumen de funciones**, **el cliente espera, por lo tanto el operador no debe esperar a la plataforma**, **toda decisión queda registrada** y **escalamiento temprano es siempre mejor que escalamiento tardío**.

Esperamos que todos los usuarios de la plataforma lean este manual atentamente, pues sirve como la guía principal para la resolución de dudas cotidianas sobre la operación. Cada sección está organizada por rol, pero recomendamos leer también las secciones de los roles adyacentes al tuyo para entender el contexto completo de la operación.

El equipo de Soporte AIA está disponible de lunes a domingo, de 06:00 a 23:00 hora local de cada sucursal, a través del chat embebido en el dashboard (botón "Ayuda" en la esquina inferior derecha) o por el portal de incidencias internas.

---

## 2. ESTRUCTURA DE ROLES EN AIA

La plataforma AIA define cuatro roles operativos principales. Cada rol tiene un conjunto de permisos, pantallas accesibles y responsabilidades específicas.

**Driver**: es el responsable de retirar los pedidos en la sucursal y entregarlos al cliente final. Opera desde la aplicación móvil de AIA. No tiene acceso al dashboard web.

**Manager** (de sucursal): es el responsable de la operación diaria de una sucursal específica. Supervisa cocina, pedidos, staff, inventario y atención al cliente. Opera desde el dashboard web con permisos limitados a su sucursal.

**Regional Manager**: es el responsable de un conjunto de sucursales de un mismo tenant. Toma decisiones de portafolio, aprueba acciones excepcionales y monitorea métricas comparativas. Opera desde el dashboard web con vista multi-sucursal.

**Colaborador**: es el responsable interno (back-office, soporte o administración) que ejecuta tareas transversales: onboarding de restaurantes, soporte a managers y drivers, configuración avanzada y gestión de incidencias escaladas. Opera desde el dashboard web con permisos elevados pero acotados a su tenant.

El acceso a la plataforma se realiza con el correo corporativo asignado durante el onboarding y la contraseña inicial enviada por el equipo de Soporte AIA. La primera vez que ingreses al sistema, deberás cambiar la contraseña obligatoriamente.

---

## 3. ACCESO A LA PLATAFORMA Y GESTIÓN DE CUENTA

### 3.1. Primer ingreso

Para acceder a AIA por primera vez, abrí el navegador (recomendamos Chrome o Edge actualizado) e ingresá a la URL provista por tu Regional Manager o por el equipo de Soporte AIA. Introducí tu correo corporativo y la contraseña temporal recibida por email.

El sistema te pedirá inmediatamente cambiar la contraseña. La nueva contraseña debe tener al menos 10 caracteres, incluir una mayúscula, una minúscula, un número y un carácter especial. Está prohibido reutilizar las últimas 5 contraseñas.

Tras el cambio, el sistema te llevará al dashboard correspondiente a tu rol. La sucursal y el tenant ya vienen pre-configurados.

### 3.2. Recuperación de contraseña

Si olvidaste tu contraseña, hacé clic en "Olvidé mi contraseña" en la pantalla de login. Recibirás un enlace de recuperación al correo asociado a tu cuenta, válido por 30 minutos.

Si no recibís el correo dentro de los 5 minutos, revisá la carpeta de spam. Si tampoco aparece allí, comunicate con tu Regional Manager o con Soporte AIA — probablemente tu correo no esté correctamente asociado a la cuenta.

### 3.3. Cierre de sesión y sesiones concurrentes

Es obligatorio cerrar sesión al final de tu turno desde el menú de usuario en la esquina superior derecha del dashboard. AIA permite hasta dos sesiones concurrentes por usuario (por ejemplo, una en computadora de la sucursal y otra en celular). Una tercera sesión cerrará automáticamente la más antigua.

### 3.4. Cambio de datos personales

Para cambiar tu nombre, foto de perfil o número de teléfono, ingresá a "Mi cuenta" desde el menú de usuario. Los cambios de correo electrónico solo pueden ser realizados por un Colaborador con permisos administrativos — solicitalos por el canal de soporte.

---

## 4. MANUAL DEL MANAGER DE SUCURSAL

El Manager es el corazón operativo de cada sucursal. Esta sección cubre todo lo que un Manager necesita saber para operar AIA durante un turno típico.

### 4.1. Apertura del turno

Cada turno operativo comienza con la apertura de la sucursal en AIA. Sin esta apertura, la sucursal no recibe pedidos online ni dine-in.

Al ingresar al dashboard, hacé clic en el botón "Abrir sucursal" ubicado en la parte superior de la pantalla principal. El sistema te pedirá confirmar:

- El horario de cierre estimado para el día.
- El monto de apertura de caja (efectivo inicial).
- Los canales activos: dine-in, takeout, delivery, catering.
- El estado de los drivers asignados al turno.

Una vez confirmados estos datos, la sucursal queda "Abierta" y comienza a recibir pedidos. El cliente verá la sucursal disponible en la app del consumidor y en los marketplaces conectados.

Recomendamos hacer la apertura al menos 15 minutos antes del horario público de inicio, para tener tiempo de verificar que la cocina esté lista y que el menú esté correcto.

### 4.2. Vista general del dashboard del Manager

El dashboard del Manager está organizado en cinco áreas principales, accesibles desde el menú lateral izquierdo:

**Cola de pedidos**: muestra todos los pedidos activos en tiempo real, agrupados por estado (nuevo, en preparación, listo, en camino, entregado).

**Menú e inventario**: permite gestionar disponibilidad de ítems, precios temporales, modificadores y promociones del día.

**Staff**: muestra el listado de empleados activos en el turno (drivers, runners, cocineros si están registrados) y su estado actual.

**Reportes**: contiene el informe del día, comparativas y herramientas de cierre de caja.

**Catering**: vista específica para órdenes de catering programadas, separada de la operación regular por su naturaleza distinta.

La barra superior del dashboard muestra siempre tres indicadores clave: cantidad de pedidos activos, tiempo promedio de preparación y cantidad de drivers disponibles.

### 4.3. Confirmación de pago de una orden

Una de las dudas más frecuentes del Manager es saber si una orden ya está pagada antes de liberarla al driver o entregarla al cliente.

En la Cola de pedidos, cada orden muestra un indicador de pago a la derecha del total. El indicador puede tomar uno de cuatro estados:

**Verde con check**: la orden está pagada y conciliada. Es seguro liberar al driver o entregar al cliente.

**Amarillo**: la orden está autorizada pero todavía no capturada. Esto es normal en pedidos de delivery: el sistema captura el pago automáticamente cuando marcás la orden como "Lista para pickup". Si el amarillo persiste por más de 5 minutos después de marcar la orden como lista, comunicate con Soporte AIA.

**Rojo**: el pago falló. No entregues la orden bajo ninguna circunstancia. Tocá sobre el indicador rojo para ver el motivo (tarjeta rechazada, fondos insuficientes, error de procesamiento) y seguí el procedimiento de recuperación del pago descrito en la sección 4.4.

**Gris con reloj**: el pago está en proceso de captura. Esperá hasta 2 minutos. Si no cambia a verde, refrescá la pantalla. Si tras refrescar sigue gris, escalá a Soporte AIA.

Recordá: el pago verde es la única autorización válida para liberar la orden. Nunca entregues una orden con el indicador en rojo confiando en una promesa de pago posterior.

### 4.4. Manejo de fallos de pago

Cuando el indicador de pago de una orden está en rojo, el primer paso es identificar el motivo. Tocá sobre el ícono rojo y leé la descripción del error.

Si el error es "Tarjeta rechazada" o "Fondos insuficientes", contactá al cliente por el botón "Llamar cliente" dentro de la tarjeta de la orden. Informá que el pago no fue procesado y ofrecé las dos alternativas: que intente con otra tarjeta desde el botón "Reintentar pago" que recibirá por SMS, o que pague en efectivo al momento del pickup/entrega si la sucursal acepta esa modalidad.

Si el error es "Error de procesamiento" o "Timeout del procesador", esperá 3 minutos y reintentá la captura manual desde el menú de la orden ("Acciones" > "Reintentar captura"). Si el error persiste, escalá a Soporte AIA con el número de la orden.

En todos los casos, registrá el incidente en el campo "Notas operativas" de la orden para que quede trazabilidad. Si terminás cancelando la orden, usá el motivo "Pago no resuelto" en el cancelador.

### 4.5. Aplicación de cupones y descuentos manuales

Hay dos tipos de cupones en AIA: los cupones automáticos (creados desde la sección de Promociones) y los descuentos manuales aplicados por el Manager en el momento.

Para aplicar un descuento manual a una orden ya creada, abrí la orden en la Cola de pedidos y tocá "Acciones" > "Aplicar descuento manual". Seleccioná el tipo (porcentual o monto fijo), ingresá el valor y elegí el motivo desde la lista predefinida (compensación por demora, error de cocina, cortesía a cliente frecuente, etc.).

Los descuentos manuales tienen límites según el rol:

- Hasta el 15% del subtotal: el Manager puede aplicarlo sin aprobación.
- Entre 15% y 30%: el Manager lo aplica pero queda pendiente de aprobación del Regional Manager.
- Más del 30%: requiere aprobación previa del Regional Manager antes de aplicarse.

Estos límites están diseñados para proteger la salud financiera de la sucursal y evitar abusos. Si necesitás aplicar un descuento mayor en una situación crítica, llamá al Regional Manager por el canal de escalamiento.

### 4.6. Reembolsos

Los reembolsos en AIA se procesan desde la orden afectada. Abrí la orden, tocá "Acciones" > "Emitir reembolso" y seleccioná el tipo:

**Reembolso total**: devuelve el 100% del valor cobrado al método de pago original. Usalo cuando la orden no se entregó o fue cancelada por culpa de la sucursal.

**Reembolso parcial**: permite seleccionar ítems específicos o ingresar un monto. Usalo cuando la entrega fue parcial, hubo un error de cocina en un solo ítem o se aplica una compensación.

**Reembolso a crédito**: no devuelve dinero a la tarjeta, sino que genera un crédito en la cuenta del cliente para usar en futuras órdenes. Útil cuando el cliente prefiere seguir comprando y la compensación es menor.

Los reembolsos hasta el 100% del valor de la orden pueden ser procesados por el Manager. Reembolsos que excedan el valor original (por ejemplo, compensación adicional) requieren aprobación del Regional Manager.

El tiempo de procesamiento depende del método de pago: tarjetas de crédito demoran entre 5 y 10 días hábiles en reflejarse en el estado del cliente, mientras que créditos en cuenta son inmediatos. Comunicale este plazo al cliente al momento de procesar el reembolso para evitar reclamos posteriores.

### 4.7. Gestión de la cola de pedidos

La Cola de pedidos es la pantalla que el Manager debe tener abierta durante todo el turno. Cada tarjeta de pedido muestra:

- Número de orden y nombre del cliente.
- Canal de origen (dine-in, takeout, delivery, catering, marketplace específico).
- Items del pedido y modificadores.
- Total y estado de pago.
- Hora de creación y hora prometida.
- Cronómetro visual que cambia de color según el tiempo restante.

El cronómetro tiene tres estados de color: **verde** indica que estás dentro del tiempo objetivo, **amarillo** advierte que se aproxima al límite (la cocina debe estar en plateado final), **rojo** señala que ya pasaste el tiempo prometido al cliente.

Las tarjetas también pueden tener indicadores adicionales: una estrella amarilla para clientes VIP, un ícono de fuego para órdenes urgentes (catering próximo a la hora de evento), un ícono de alerta para órdenes con alguna observación especial del cliente.

Hacé clic en cualquier tarjeta para expandirla y ver todos los detalles. Desde la vista expandida podés:

- Cambiar el estado de la orden (nuevo → en preparación → listo → entregado).
- Asignar o reasignar driver.
- Agregar notas operativas internas (no visibles al cliente).
- Imprimir la comanda (si la sucursal tiene impresora conectada).
- Llamar al cliente.
- Cancelar la orden.

### 4.8. Tiempos de salida de las órdenes

Una de las preguntas más frecuentes es: ¿cuánto tiempo antes de la hora prometida debe salir la orden?

La regla operativa estándar de AIA es la siguiente:

**Delivery normal**: la orden debe estar lista y empaquetada **5 minutos antes** de la hora estimada de pickup del driver. Esta hora ya incluye el buffer hacia el cliente. El driver llega, escanea, retira y sale.

**Catering**: la orden completa debe estar lista y empaquetada **20 minutos antes** de la hora de evento acordada con el cliente. Esto da margen para verificar ítems, cargar al vehículo y manejar imprevistos.

**Pedidos grandes** (más de 10 ítems o más de 6 personas): sumá **10 minutos adicionales** al tiempo de delivery normal. Estos pedidos suelen requerir verificación extra y empaque más cuidadoso.

**Takeout (retiro en local)**: la orden debe estar lista exactamente a la hora prometida al cliente. No antes de 3 minutos (la comida pierde calidad) ni después (el cliente pierde paciencia).

El cronómetro visual en la Cola de pedidos está calibrado con estas reglas. Cuando una tarjeta llega a amarillo, la cocina debería estar finalizando el ítem. Cuando llega a rojo, la orden ya está tarde y hay que activar el protocolo de notificación al cliente descrito en la sección 4.9.

### 4.9. Notificación de retrasos al cliente

Si una orden va a entregarse tarde, el procedimiento correcto es **notificar al cliente antes de que el cliente se queje**. Esto reduce drásticamente los reclamos y mantiene la confianza.

En la tarjeta de la orden, tocá "Acciones" > "Notificar atraso". Seleccioná el motivo desde la lista (alta demanda, falla de equipo, ítem agotado en cocina, etc.) y el tiempo adicional estimado (5, 10, 15, 20 minutos o más).

El cliente recibe automáticamente un mensaje por SMS y/o notificación push en la app, con el motivo y el nuevo tiempo estimado. El sistema también ajusta el cronómetro de la orden para no marcarla como "tarde" sobre el tiempo original.

Recordá que el motivo es visible al cliente, así que sé honesto pero diplomático. No uses motivos como "el cocinero se distrajo" — usá motivos operativos válidos como "alta demanda en este momento".

### 4.10. Verificaciones antes de la salida de una orden

Antes de que cualquier orden salga de la sucursal — sea con driver o en mano del cliente — el Manager debe ejecutar un checklist de verificación. Este checklist es el control de calidad final.

Para órdenes de delivery, antes de liberar al driver verificá lo siguiente:

- El indicador de pago está en verde.
- Los ítems coinciden exactamente con la comanda impresa o digital.
- Los modificadores están aplicados correctamente (sin tomate, salsa aparte, etc.).
- Las bebidas están separadas en bolsa aparte si son frías, o aseguradas si son calientes.
- La bolsa está sellada con sticker o cinta. Una bolsa abierta es un reclamo asegurado.
- La temperatura es la adecuada (caliente lo caliente, frío lo frío, los helados con hielo seco si la sucursal lo provee).
- El nombre del cliente está visible en la bolsa o en la etiqueta.
- El driver escaneó correctamente el QR de la orden y aparece como "asignado".

Para órdenes de takeout, antes de entregar al cliente:

- Confirmá el nombre del cliente preguntándolo (no lo digas vos primero).
- Verificá ítems contra la comanda en presencia del cliente.
- Si hay propina pendiente de cobro, procesala antes de entregar la bolsa.

Para órdenes dine-in, el procedimiento es manejado por los meseros pero el Manager es responsable de que el sistema marque la mesa como cerrada antes de liberarla.

### 4.11. Handoff con el driver

El handoff (entrega de la orden al driver) es uno de los puntos críticos de la operación. Un handoff bien hecho ahorra reclamos y retrasos posteriores.

Cuando un driver llega a la sucursal, tocá la orden correspondiente en la Cola de pedidos y verificá que el sistema ya muestre al driver como "en sucursal". Si no aparece, pedile al driver que escanee el QR de pickup desde su app, que está en la pantalla "Detalle de orden" del Manager.

Si el QR no escanea (cámara con problemas, código dañado), podés hacer el handoff manualmente: tocá "Acciones" > "Confirmar pickup manual", ingresá el nombre del driver y tu PIN de Manager. Esto deja registro de que vos validaste el handoff sin escaneo.

Antes de entregar físicamente la bolsa al driver, confirmá los ítems verbalmente: "tres hamburguesas, dos papas, una gaseosa, todo para Rodriguez". Esto activa una verificación cruzada entre lo que la cocina preparó, lo que el sistema dice y lo que el driver se lleva.

Si el driver llega y la orden no está lista, el sistema le indica el tiempo restante estimado. Pedile que espere en la zona designada y avisale a la cocina para priorizar. No demores más de 5 minutos a un driver — pierde la oportunidad de tomar otros pedidos y la sucursal acumula mala reputación entre la flota.

### 4.12. Reasignación de driver

Si un driver asignado a una orden no llega en tiempo razonable (más de 10 minutos después del horario de pickup), tenés dos opciones:

**Opción A — Esperar y comunicar**: si conocés al driver y sabés que viene en camino, marcá la orden como "Driver en camino con demora" y notificá al cliente del retraso.

**Opción B — Reasignar**: abrí la orden, tocá "Acciones" > "Reasignar driver". El sistema te muestra los drivers disponibles cerca de la sucursal ordenados por distancia. Seleccioná uno y confirmá. El driver anterior recibe la notificación de la reasignación y la orden pasa al nuevo driver automáticamente.

La reasignación es preferible cuando hay otros drivers disponibles a menos de 5 minutos de la sucursal. La espera es preferible cuando no hay alternativas cercanas y el driver original está claramente en camino.

### 4.13. Gestión del menú e inventario diario

El menú en AIA se configura a nivel de tenant (todas las sucursales lo comparten por defecto) pero el Manager tiene control diario sobre la disponibilidad en su sucursal.

**Agotar un ítem (86)**: cuando un ítem se acaba en cocina, ingresá a "Menú e inventario", buscá el ítem y tocá el switch "Disponible" para apagarlo. El ítem queda invisible para todos los canales de pedido (app, dine-in, marketplaces) de tu sucursal inmediatamente. Esta es la operación más frecuente del día y debe hacerse en el momento exacto en que se agota, no después.

**Reactivar un ítem**: el mismo procedimiento pero encendiendo el switch.

**Cambiar precio temporal**: tocá el ítem, luego "Precio del día". Ingresá el nuevo precio y la fecha hasta cuándo aplica (por defecto, hasta el cierre del turno). El precio temporal solo afecta a tu sucursal y vuelve al precio estándar al día siguiente automáticamente. Útil para happy hour, promociones del día o agotamientos parciales.

**Cambiar precio permanente**: requiere permisos de Regional Manager. Si necesitás cambiar el precio de manera definitiva, escalá la solicitud.

**Modificadores**: los modificadores (extras, sin algo, cocción) están configurados a nivel de menú pero el Manager puede desactivar modificadores específicos si por ejemplo se acabó el queso cheddar pero el ítem que lo lleva sigue disponible con otros quesos.

### 4.14. Promociones del día

Para crear una promoción válida solo para el día, ingresá a "Menú e inventario" > "Promociones del día". Tocá "Nueva promoción" y completá:

- Nombre interno (para tu referencia).
- Mensaje al cliente (lo que verá en la app).
- Tipo: descuento porcentual, descuento monto fijo, 2x1, ítem regalo.
- Items o categorías a las que aplica.
- Horario de validez (todo el día o un rango específico).
- Stock disponible (cuántas veces puede aplicarse en total).

Una vez creada, la promoción está activa inmediatamente. El cliente la ve en la app del consumidor y se aplica automáticamente cuando elige los ítems calificados.

Las promociones del día expiran automáticamente al cierre del turno y no se renuevan. Para promociones recurrentes, hay que escalar al Regional Manager para que las configure a nivel de tenant.

### 4.15. Pausa temporal de pedidos online

En momentos de saturación extrema (rush no anticipado, falla de equipo, falta de personal), el Manager puede pausar la recepción de pedidos online sin cerrar la sucursal.

Tocá el botón "Pausar pedidos" en la parte superior del dashboard. El sistema te pedirá:

- Duración de la pausa (15, 30, 45 minutos o personalizada).
- Canales a pausar (todos o solo algunos: app propia, marketplaces específicos).
- Motivo (visible solo internamente para reportes).

Durante la pausa, los clientes ven la sucursal como "Temporalmente no disponible" en la app. Las órdenes ya en curso siguen procesándose normalmente.

La pausa termina automáticamente al cumplirse el tiempo, o podés cancelarla antes desde el mismo botón ahora etiquetado "Reanudar pedidos".

Recordá que cada pausa queda registrada en el reporte del turno y es revisada por el Regional Manager. Pausas frecuentes o muy largas pueden indicar problemas operativos de fondo que requieren atención.

### 4.16. Modo ocupado (rush)

El modo ocupado es distinto a la pausa: la sucursal sigue recibiendo pedidos pero el sistema extiende automáticamente los tiempos prometidos al cliente.

Activá el modo ocupado desde el botón "Estado: Normal" en la parte superior del dashboard, cambiándolo a "Ocupado" o "Muy ocupado". Cada nivel agrega tiempo a las promesas:

- **Normal**: tiempos estándar de cada ítem.
- **Ocupado**: suma 10 minutos a cada tiempo estimado.
- **Muy ocupado**: suma 20 minutos a cada tiempo estimado.

El cliente ve los tiempos ajustados al momento de pedir, por lo que no se sorprende. Es preferible activar el modo ocupado antes de saturarse que pausar pedidos cuando ya estás colapsado.

### 4.17. Recepción de órdenes de catering por email

Las órdenes de catering pueden llegar de tres formas: por la app del consumidor, por el dashboard del Regional Manager (cuando el cliente llama directamente), o por email (cuando el cliente envía un PDF con la orden, típicamente desde plataformas como ezCater).

Cuando llega una orden de catering por email, AIA la procesa automáticamente: extrae los datos del PDF, los normaliza y crea una orden de catering en estado "Pendiente de confirmación" en la pestaña Catering.

El Manager debe revisar la orden detectada y verificar:

- Que los ítems coincidan con lo que el cliente solicitó (a veces la extracción tiene errores menores).
- Que la fecha y hora del evento sean correctas.
- Que la dirección de entrega esté completa y sea cubierta por la sucursal.
- Que la cantidad de personas sea coherente con la cantidad de ítems.
- Que el total facturable sea correcto.

Si todo está bien, tocá "Confirmar orden". El sistema envía automáticamente un email de confirmación al cliente con los detalles y la fecha de entrega.

Si hay errores, tocá "Solicitar aclaración". El sistema abre un correo pre-redactado dirigido al cliente, que podés ajustar y enviar. La orden queda en estado "Pendiente de aclaración" hasta que el cliente responda.

Nunca confirmes una orden de catering con dudas. Las órdenes de catering tienen volúmenes grandes y errores son caros — preguntar antes evita problemas el día del evento.

### 4.18. Confirmación de orden de catering al cliente

Una vez confirmada internamente la orden, el cliente recibe automáticamente un email con:

- Resumen del pedido.
- Fecha y hora de entrega.
- Dirección y persona de contacto.
- Total y método de pago.
- Política de cancelación.

El Manager no necesita hacer nada adicional en este paso a menos que la sucursal tenga un proceso particular (por ejemplo, llamada telefónica de confirmación para órdenes grandes). En ese caso, configurá un recordatorio en tu agenda 24 horas antes del evento.

### 4.19. Programación de la salida de catering

Las órdenes de catering aparecen en la Cola de pedidos con anticipación, según la regla configurada por el tenant (generalmente 4 horas antes del evento, pero puede ser más para órdenes muy grandes).

Cuando una orden de catering entra a la Cola, el Manager debe asignarle un horario de inicio de preparación. Tocá la orden y luego "Programar preparación". El sistema sugiere automáticamente el horario óptimo basado en la complejidad del pedido, pero podés ajustarlo según la situación de tu cocina.

El cronómetro de catering arranca al inicio de la preparación, no al momento del pedido. Esto te permite ver con claridad cuánto tiempo te queda para tener todo listo 20 minutos antes del evento.

Para órdenes muy grandes (más de 50 personas), recomendamos coordinar con cocina con al menos un turno de anticipación, dividir la preparación en bloques y tener un responsable único del catering durante esas horas para evitar que se mezcle con la operación regular.

### 4.20. Cambios de último momento en órdenes de catering

Es común que el cliente pida cambios el día del evento: más comensales, cambio de hora, agregar un ítem extra. Estos cambios deben procesarse con cuidado.

Abrí la orden de catering desde la pestaña Catering y tocá "Editar orden". Podés agregar ítems, modificar cantidades o cambiar la hora de entrega. Cada cambio recalcula automáticamente el total y notifica al cliente con un resumen actualizado.

Si el cambio es significativo (más del 30% del valor original o cambio de hora con menos de 3 horas de aviso), el sistema te pedirá aprobación del Regional Manager antes de aplicarlo. Esto evita que un cambio de último momento desestabilice toda la operación.

Cancelaciones de catering con menos de 24 horas de aviso siguen la política de cancelación del tenant. El Manager no decide si se cobra cancelación o no — el sistema aplica la política configurada y notifica al cliente.

### 4.21. Visualización de drivers conectados

Desde la pestaña Staff podés ver en tiempo real qué drivers están conectados a tu sucursal, su estado actual y su ubicación si están en una entrega.

Cada driver aparece en una de cinco categorías:

- **Disponible**: conectado y esperando asignación.
- **En sucursal**: vino a hacer pickup, todavía en la sucursal.
- **En camino al cliente**: con orden activa, en ruta de entrega.
- **Volviendo**: regresando a la sucursal después de entrega.
- **En pausa**: conectado pero no aceptando pedidos (almuerzo, descanso).

Tocá sobre un driver para ver sus órdenes activas del día, su tiempo promedio de entrega y su rating reciente. Si necesitás comunicarte con un driver, usá el botón "Contactar driver" — abre un chat directo desde el dashboard, sin necesidad de tener el celular del driver.

### 4.22. Asignación manual de drivers

Por defecto, AIA asigna drivers automáticamente a las órdenes según proximidad, disponibilidad y rating. En algunos casos, el Manager puede asignar manualmente:

- Si querés priorizar a un driver de confianza para un pedido grande o VIP.
- Si un driver pidió expresamente recibir una orden específica.
- Si el sistema automático no encuentra driver y la orden lleva esperando más de 5 minutos.

Para asignar manualmente, abrí la orden y tocá "Asignar driver". El sistema muestra los drivers disponibles ordenados por distancia. Seleccioná uno y confirmá. El driver elegido recibe la notificación con prioridad y dispone de 2 minutos para aceptar antes de que el sistema reabra la asignación.

### 4.23. Manejo de incidencias con clientes

Los reclamos de clientes son inevitables. AIA estructura el manejo de incidencias para que cada caso quede registrado y se resuelva con criterio consistente.

Cuando un cliente reclama por una orden — sea por la app, por teléfono o presencialmente — el primer paso es ubicar la orden en el dashboard. En la Cola de pedidos buscá por número, nombre del cliente o teléfono.

Abrí la orden y tocá "Reportar incidencia". Seleccioná el tipo:

- **No llegó**: la orden nunca fue entregada al cliente.
- **Llegó incompleta**: faltaron ítems.
- **Llegó incorrecta**: ítems equivocados o modificadores no respetados.
- **Llegó en mal estado**: comida fría, derramada, en mal estado de empaque.
- **Llegó tarde**: muy fuera del horario prometido.
- **Mala atención**: queja sobre el driver o el personal de sucursal.
- **Otro**: requiere descripción libre.

El sistema sugiere automáticamente una resolución según el tipo y la severidad: reenvío del pedido, reembolso parcial, reembolso total, crédito en cuenta, cupón de compensación. Podés aceptar la sugerencia o aplicar otra resolución.

Ejecutá la resolución desde la misma pantalla. El cliente recibe la notificación con el detalle y el comprobante si corresponde.

Cada incidencia queda registrada en el historial del cliente y del driver (si aplica). Esto sirve para identificar patrones: clientes con muchos reclamos que pueden estar abusando, drivers con muchas incidencias que requieren capacitación.

### 4.24. Escalamiento al Regional Manager

No todo lo puede resolver el Manager. Hay situaciones que deben escalarse al Regional Manager con claridad y rapidez.

Casos que **siempre** se escalan:

- Descuento o reembolso mayor al 30% del valor de la orden.
- Incidencia grave (intoxicación, denuncia legal, queja en redes sociales con repercusión).
- Falla operativa que afecta a múltiples órdenes simultáneamente (cocina caída, sistema de pago caído, falta de drivers crítica).
- Conflicto serio con un cliente, driver o empleado.
- Solicitud del cliente que excede tu autoridad.

Casos que **a veces** se escalan (criterio del Manager):

- Reclamos recurrentes del mismo cliente.
- Patrones de incidencias con un driver específico.
- Decisiones operativas con impacto en presupuesto del día.

Para escalar, usá el canal de "Escalamiento al Regional" en el menú lateral. Esto crea un ticket que el Regional Manager ve en su dashboard con prioridad. Describí el caso de forma concisa: qué pasó, qué intentaste, qué necesitás del Regional.

Nunca llames al Regional Manager por teléfono para escalar algo escalable por sistema, salvo emergencia real. El ticket queda registrado y permite seguimiento.

### 4.25. Gestión de staff de sucursal

El Manager tiene capacidad limitada de gestión de staff: puede ver, contactar y reportar comportamientos, pero la contratación y desvinculación las maneja el Regional Manager.

Para ver el staff asignado a tu sucursal, ingresá a Staff > Lista de empleados. Podés filtrar por rol (driver, cocinero registrado, mesero, runner, etc.) y por estado (activo, en pausa, desconectado, dado de baja).

Tocá sobre un empleado para ver su perfil, historial reciente y métricas individuales. Si necesitás reportar un comportamiento (faltas, retrasos, conductas inadecuadas), usá el botón "Reportar incidente de staff" en su perfil. El reporte llega al Regional Manager.

### 4.26. Cierre del turno y cuadre de caja

El cierre del turno es el último procedimiento del día y debe ejecutarse con rigor. Sin cierre, el turno queda abierto contablemente y desfasa los reportes.

Antes de cerrar, verificá lo siguiente:

- Todas las órdenes activas están finalizadas (entregadas, canceladas o transferidas a la sucursal de turno siguiente si aplica).
- Todos los drivers cerraron sesión o están en pausa.
- La cocina confirmó que terminó toda preparación.
- La caja física fue contada y cuadrada con la caja del sistema.

Tocá "Cerrar sucursal" en la parte superior del dashboard. El sistema te pedirá:

- Monto de cierre de caja (efectivo final).
- Resumen de ventas del turno (lo muestra el sistema, confirmás visualmente).
- Comentarios u observaciones del turno (opcional pero recomendado para casos atípicos).

El sistema compara automáticamente la caja esperada vs. la caja real. Si hay diferencia mayor al 1%, el sistema te pide justificación.

Una vez cerrado, el turno queda registrado y el reporte se genera automáticamente. La sucursal pasa al estado "Cerrada" y deja de recibir pedidos hasta la próxima apertura.

### 4.27. Reportes operativos del Manager

El Manager tiene acceso a una serie de reportes desde la pestaña Reportes. Los más utilizados en el día a día son:

**Resumen del día**: muestra ventas totales, número de órdenes, ticket promedio, propinas totales, distribución por canal y ranking de ítems más vendidos. Disponible en tiempo real y al cierre del turno.

**Ventas por hora**: gráfico de barras que muestra cuántas órdenes y cuánto facturó la sucursal en cada hora del día. Útil para identificar horas pico y planificar staff.

**Ranking de drivers**: lista los drivers que operaron en el día con su cantidad de entregas, tiempo promedio, propinas totales y rating del día.

**Reporte de incidencias**: detalla todas las incidencias del día, su tipo, resolución aplicada y costo.

**Cierre de caja**: comprobante imprimible del cuadre del turno, con detalle de movimientos en efectivo, tarjeta y otros métodos.

Cada reporte se puede exportar en PDF o Excel desde el botón "Exportar" en la esquina superior derecha del reporte.

### 4.28. Comparativas semanales y mensuales

Para comparar el desempeño actual con períodos anteriores, ingresá a Reportes > Comparativas. Seleccioná el período base (esta semana, este mes) y el período de comparación (semana pasada, mismo mes año pasado).

El sistema muestra variaciones porcentuales en métricas clave: ventas, número de órdenes, ticket promedio, tiempo promedio de preparación, tasa de incidencias.

Si una métrica muestra una variación negativa mayor al 15%, el sistema la marca con un indicador rojo. Esto te ayuda a identificar rápidamente dónde poner atención sin necesidad de leer toda la grilla.

---

## 5. MANUAL DEL DRIVER

El Driver es la cara visible de AIA para el cliente final. Esta sección cubre todo lo que un Driver necesita saber para operar la aplicación móvil y completar entregas con éxito.

### 5.1. Inicio de turno y disponibilidad

Para empezar a recibir pedidos, abrí la app de AIA Driver en tu celular e iniciá sesión. La primera pantalla muestra un switch grande con la opción "Disponible / No disponible".

Antes de ponerte disponible, verificá:

- Tu celular tiene batería al menos al 50% o estás cargándolo en el vehículo.
- Tenés señal GPS activa (el ícono de ubicación arriba a la derecha debe estar verde).
- Tenés datos móviles o estás conectado a una red estable.
- Tu vehículo está en condiciones (combustible, llantas, equipo de delivery limpio).

Tocá el switch a "Disponible". El sistema te ubica geográficamente y comenzás a recibir oportunidades de pedido según tu cercanía a las sucursales que tenés asignadas.

### 5.2. Aceptar o rechazar un pedido

Cuando hay un pedido disponible para vos, recibís una notificación con vibración y sonido. La pantalla muestra:

- Sucursal de pickup (nombre y dirección).
- Distancia y tiempo estimado al pickup.
- Destino final (zona, no dirección exacta hasta aceptar).
- Distancia y tiempo total estimado.
- Ganancia base estimada (sin contar propina).

Tenés **30 segundos** para aceptar o rechazar el pedido. Si no respondés, el sistema lo ofrece al siguiente driver disponible.

Tocá "Aceptar" si querés tomarlo. Tocá "Rechazar" si no te conviene (lejos, ruta complicada, etc.).

Tené en cuenta que tu tasa de aceptación afecta tu prioridad para futuros pedidos. Rechazos ocasionales son normales; rechazos sistemáticos te ponen al final de la cola de asignación.

### 5.3. Ruta al restaurante

Una vez aceptado el pedido, la app muestra la ruta sugerida al restaurante. Tocá "Iniciar navegación" para abrir tu app de mapas preferida (Google Maps, Waze o Apple Maps según configuración).

La ruta sugerida considera tráfico en tiempo real. Si conocés una ruta mejor por experiencia local, podés tomarla — el sistema solo te pide llegar dentro del tiempo estimado.

Mantené la app de AIA Driver abierta en segundo plano durante la navegación. Esto permite que la sucursal vea tu ubicación en tiempo real y se prepare para tu llegada.

### 5.4. Llegada al restaurante

Al llegar a la sucursal, tocá "Llegué al restaurante" en la app. Esto notifica al Manager de tu presencia.

Si la orden ya está lista (estado verde en el dashboard del Manager), procedé directo al mostrador de delivery. Saludá al Manager o al responsable de entrega, identificate con el número de orden visible en tu pantalla y pedí confirmación.

Si la orden todavía no está lista, esperá en la zona designada (si la sucursal tiene una). La app te muestra el tiempo estimado restante. No insistas a la cocina — el Manager ya sabe que estás esperando.

### 5.5. Pickup de la orden con QR

Una vez que la orden está lista, el Manager o un responsable te muestra el código QR de pickup en su pantalla. Abrí tu app de AIA Driver y tocá "Escanear QR de pickup". Apuntá la cámara al código.

Al escanear con éxito, la app muestra:

- Confirmación del número de orden.
- Lista de ítems del pedido.
- Nombre del cliente.
- Dirección de entrega (ahora completa, no solo zona).
- Instrucciones especiales si las hay (timbre que no funciona, dejar en portería, etc.).

Antes de salir de la sucursal, verificá los ítems contra la lista. Si falta algo, decilo al Manager — no salgas con una orden incompleta confiando en arreglarlo después.

### 5.6. Qué hacer si el QR no escanea

Si el QR no escanea (cámara con problemas, código en pantalla dañada, problema técnico), pediile al Manager que haga "Confirmación manual de pickup". Es un procedimiento estándar que toma 30 segundos.

El Manager ingresa tu nombre y un PIN, y el pickup queda confirmado en el sistema igual que si hubieras escaneado. No salgas de la sucursal sin que el pickup esté confirmado de alguna de las dos formas — si lo hacés, el sistema te marca como "perdido" y la sucursal puede reasignar la orden a otro driver mientras vos ya la llevás.

### 5.7. Verificación antes de salir del restaurante

Antes de subir al vehículo y arrancar la ruta, hacé este check rápido:

- ¿La cantidad de bolsas o paquetes coincide con lo que dijo el Manager?
- ¿Las bolsas están selladas?
- ¿Las bebidas frías están aparte de la comida caliente?
- ¿Tenés el nombre del cliente visible en la bolsa o etiqueta?
- ¿La app dice que ya tenés el pickup confirmado?

Si todo está bien, tocá "Salir hacia el cliente" en la app y arrancá la ruta de entrega.

### 5.8. Ruta hacia el cliente

La app muestra ahora la ruta del restaurante al cliente. Iniciá la navegación.

Durante la ruta, el cliente recibe actualizaciones automáticas de tu ubicación en su app del consumidor. No necesitás llamarlo ni avisarle que estás en camino — el sistema lo hace.

Mantené la app abierta en segundo plano. Si por algún motivo la app se cierra (batería, error), abrila apenas puedas para retomar el tracking.

### 5.9. Llegada al cliente

Al llegar a la dirección del cliente, tocá "Llegué al cliente" en la app. Esto notifica al cliente y arranca un cronómetro de 5 minutos.

Tocá el timbre o golpeá la puerta. Si el cliente no abre dentro de los primeros 2 minutos, llamalo usando el botón "Llamar cliente" en la app. No uses tu número personal — el botón llama a través de un número intermedio que protege tu privacidad.

Si después de los 5 minutos el cliente no responde y no contestó la llamada, seguí el protocolo de cliente ausente descrito en la sección 5.13.

### 5.10. Entrega y foto

Cuando el cliente abre y le entregás la bolsa, tocá "Entregar pedido" en la app. El sistema te pide:

- **Foto de entrega** (obligatoria en la mayoría de tenants): tomá una foto de la bolsa entregada en la puerta del cliente o en sus manos. Esta foto es prueba de entrega y protege tanto al cliente como a vos.
- **Confirmación visual del cliente** (en algunos casos): el cliente confirma desde su app que recibió el pedido.

Una vez confirmada la entrega, la orden se marca como "Entregada" en el sistema y vos quedás disponible para el siguiente pedido.

### 5.11. Propinas

Las propinas se pueden recibir de dos formas:

**Propina anticipada**: el cliente la agregó al pagar el pedido. Ya está descontada de su tarjeta y se acredita a tu cuenta automáticamente al completar la entrega.

**Propina al momento**: el cliente decide darte una propina en efectivo o pide cargarla a su tarjeta al entregarte la bolsa. Para propina en efectivo, simplemente recibila — no entra al sistema, es tuya directamente. Para propina por tarjeta agregada al momento, pedile al cliente que la agregue desde su app dentro de las 24 horas (recibe un recordatorio automático).

Nunca pidas propina al cliente. Es voluntaria. Pedirla afecta tu rating y puede generar reportes contra vos.

### 5.12. Cliente con cambios o pedidos adicionales

A veces el cliente al recibir la orden pide cambios: cambiar un ítem, agregar algo, devolver algo. Esto no se maneja en el momento.

Decile al cliente, con amabilidad, que vos como driver no podés modificar la orden, pero que puede llamar a la sucursal o reportar la incidencia desde la app del consumidor. Entregá la orden tal como salió.

Si el cliente se niega a recibir la orden, seguí el protocolo de la sección 5.14.

### 5.13. Cliente ausente

Si el cliente no abrió la puerta ni contestó la llamada después de 5 minutos, tenés tres opciones según las instrucciones del pedido:

**Si las instrucciones dicen "dejar en puerta sin contacto"**: dejá la bolsa en la puerta, tomá la foto de entrega y marcá como entregada. Aviso al cliente automáticamente.

**Si no hay instrucciones específicas y el lugar es seguro**: podés dejarla en la puerta solo si el cliente lo autoriza expresamente por llamada o chat. Si no logras contactarlo, no la dejes.

**Si no se puede dejar (lugar inseguro, edificio sin portería, sin autorización del cliente)**: tocá "Cliente ausente" en la app. El sistema te dice qué hacer: generalmente devolver la orden a la sucursal de origen, donde se reembolsa al cliente o se reprograma. La sucursal asume el costo del retorno.

Nunca dejes una orden con un vecino, en un negocio cercano o en una recepción sin instrucción explícita del cliente confirmada por la app.

### 5.14. Cliente que se niega a recibir

Si el cliente, al verte, se niega a recibir la orden (alegando que no la pidió, que se demoró demasiado, que la quiere reembolsada), no discutas.

Tocá "Cliente rechaza orden" en la app y seleccioná el motivo. La orden queda en estado "Rechazada" y el sistema asigna automáticamente:

- Si la sucursal está cerca y todavía abierta: te indica devolverla a la sucursal.
- Si la sucursal está lejos o cerrada: te autoriza a descartar la orden (con foto de descarte como evidencia).

En ambos casos, vos cobrás la entrega completa. El reclamo del cliente lo maneja la sucursal o el equipo de soporte.

### 5.15. Comida derramada o accidentes

Si durante el trayecto la bolsa se cae, se derrama o sufre algún accidente:

- Detené el vehículo en lugar seguro.
- Evaluá si el contenido es entregable o no.
- Si **no** es entregable, tocá "Reportar incidente de transporte" en la app y elegí el tipo (derrame, caída, accidente vehicular).
- El sistema te indica si volver a la sucursal para que reprepare el pedido (el cliente recibe notificación del retraso) o cancelar y devolver, según la situación.

Nunca entregues comida en mal estado al cliente. Es peor que llegar tarde y deteriora la confianza en la marca.

### 5.16. Visualización de ganancias

Desde la app, tocá "Mis ganancias" en el menú principal. Vas a ver:

- **Día actual**: cuánto llevás ganado hoy, en base + propinas.
- **Semana**: total de la semana en curso.
- **Histórico**: ganancias por día, semana, mes.

Cada entrega aparece detallada: fecha y hora, sucursal de origen, monto base, propinas, total ganado.

Si una entrega no aparece después de 24 horas o aparece con un monto distinto al esperado, reportalo desde "Soporte" > "Reclamo de pago" con el número de orden.

### 5.17. Calendario de pagos

Los drivers cobran según el calendario configurado por el tenant, que generalmente es uno de los siguientes:

- **Semanal**: pago todos los lunes por el período lunes a domingo anterior.
- **Quincenal**: pago los días 1 y 16 de cada mes.
- **Diario**: disponible en algunos tenants, requiere cuenta bancaria asociada.

El método de pago es transferencia bancaria a la cuenta que cargaste durante tu onboarding. Si necesitás cambiar la cuenta, ingresá a "Mi perfil" > "Datos bancarios" y actualizá. Los cambios entran en vigor para el próximo ciclo de pago, no el actual.

### 5.18. Pausa del turno

Durante un turno largo es normal necesitar pausas para comer, descansar o atender un imprevisto. La pausa es un estado intermedio entre "Disponible" y "No disponible".

En la app, tocá tu estado actual y elegí "En pausa". El sistema deja de ofrecerte pedidos nuevos pero seguís logueado y conectado. Las órdenes que ya tenías asignadas debés completarlas antes de pausar.

Para retomar, tocá nuevamente y elegí "Disponible". Volvés a recibir oportunidades.

Las pausas no se descuentan ni se penalizan, pero pausas muy largas o frecuentes pueden afectar tu rating de actividad.

### 5.19. Cierre de turno

Para cerrar tu turno, tocá "Cerrar turno" en el menú principal de la app. El sistema te muestra el resumen:

- Cantidad de entregas completadas.
- Tiempo total conectado.
- Ganancias del día.
- Rating recibido (si los clientes calificaron).

Confirmá el cierre. La app te desconecta del sistema de asignación y podés cerrarla.

Si hay órdenes activas al momento de querer cerrar, el sistema no te deja cerrar hasta completarlas o cancelarlas con motivo válido.

### 5.20. Rating y calificaciones

Cada cliente puede calificarte de 1 a 5 estrellas después de la entrega. Tu rating se calcula como promedio de las últimas 100 calificaciones.

El rating afecta:

- Tu prioridad para recibir órdenes (mayor rating = mayor prioridad).
- Tu acceso a sucursales premium o eventos de catering grandes.
- Permanencia en la plataforma (rating consistentemente bajo puede llevar a desvinculación).

Para mantener buen rating: sé puntual, sé amable, llevá la orden en buen estado, comunicate claramente y respetá las instrucciones del cliente.

---

## 6. MANUAL DEL REGIONAL MANAGER

El Regional Manager supervisa múltiples sucursales y toma decisiones de portafolio. Esta sección cubre las funciones específicas del rol.

### 6.1. Vista multi-sucursal

Al ingresar al dashboard, el Regional Manager ve la pantalla de "Resumen Regional" en lugar del dashboard de sucursal individual. Esta pantalla muestra todas las sucursales bajo su responsabilidad en una grilla.

Cada tarjeta de sucursal muestra:

- Nombre de la sucursal.
- Estado actual (abierta, cerrada, en pausa).
- Ventas del día.
- Cantidad de órdenes activas y completadas.
- Tiempo promedio de preparación.
- Indicador de salud operativa (verde, amarillo, rojo).

El indicador de salud combina varios factores: tiempos de preparación, tasa de incidencias, cantidad de pausas, performance vs. semana anterior. Una sucursal en rojo requiere tu atención prioritaria.

Tocá cualquier sucursal para entrar a su dashboard de Manager con permisos elevados (podés hacer todo lo que el Manager hace, más las funciones de Regional).

### 6.2. Comparación de sucursales

Desde el menú lateral, ingresá a "Comparar sucursales". Seleccioná dos o más sucursales y un período (día, semana, mes, trimestre).

El sistema muestra una tabla comparativa con métricas clave: ventas totales, número de órdenes, ticket promedio, tasa de incidencias, propinas totales, tiempo promedio de preparación, calificación de clientes.

También se muestra un gráfico de tendencia para cada métrica. Útil para identificar qué sucursal está creciendo, cuál está estancada y cuál está en declive.

Si una sucursal muestra resultados sistemáticamente por debajo del resto, agendá una reunión con su Manager para entender causas raíz: staff, ubicación, calidad del producto, problemas de operación.

### 6.3. Aprobación de descuentos y reembolsos escalados

Cuando un Manager solicita un descuento mayor al 15% o un reembolso atípico, el caso aparece en tu pestaña "Aprobaciones pendientes".

Cada solicitud muestra:

- Sucursal y Manager solicitante.
- Orden afectada con detalles.
- Tipo de aprobación pedida.
- Justificación dada por el Manager.
- Impacto monetario estimado.

Revisá el caso y tomá una de tres acciones:

- **Aprobar**: el Manager recibe la luz verde y procede. El descuento o reembolso se aplica.
- **Rechazar**: el Manager debe encontrar otra solución. Agregá comentario explicando el motivo.
- **Aprobar con condición**: aprobás pero ajustás el monto o exigís información adicional.

Tu velocidad de respuesta en estas aprobaciones afecta directamente la experiencia del cliente. La meta es resolver toda aprobación en menos de 15 minutos durante horario operativo.

### 6.4. Aprobación de cancelaciones de catering

Las cancelaciones de catering con menos de 24 horas de aviso o que excedan ciertos montos requieren tu aprobación.

Cada solicitud llega a "Aprobaciones pendientes" con el detalle del evento, el motivo de cancelación del cliente, la política aplicable según el tenant y el monto a devolver o a cobrar como penalidad.

Aprobá o rechazá según la política y el contexto. Si el cliente es VIP o tiene historial relevante, considerá excepciones — pero documentá el motivo.

### 6.5. Lanzamiento de promociones regionales

A diferencia de las promociones del día (que el Manager configura por sucursal), las promociones regionales aplican a múltiples sucursales y suelen tener mayor duración.

Ingresá a "Promociones" > "Nueva promoción regional". Configurá:

- Nombre interno y mensaje al cliente.
- Tipo de promoción (descuento, 2x1, ítem regalo, combo especial).
- Sucursales aplicables (todas las de tu región o un subconjunto).
- Período de validez (fechas y horarios).
- Stock total disponible.
- Restricciones (clientes nuevos, monto mínimo de orden, canales específicos).

Antes de lanzar, calculá el impacto estimado en margen usando la herramienta "Simulador de promoción". El sistema te muestra cuántas órdenes esperás que apliquen la promo y cuánto margen perdés.

Una vez lanzada, la promoción se activa automáticamente en las sucursales seleccionadas a la hora indicada.

### 6.6. Reportes ejecutivos

Desde la pestaña Reportes, el Regional Manager tiene acceso a reportes más amplios que el Manager:

**Reporte regional semanal**: ventas, órdenes, incidencias y rentabilidad de toda la región, con desglose por sucursal.

**Performance comparativa**: ranking de sucursales por múltiples métricas.

**Análisis de drivers**: ranking de drivers en la región, identificación de top performers y drivers en riesgo.

**Análisis de catering**: volumen de catering por sucursal, clientes recurrentes, valor promedio.

**Análisis de incidencias**: tipos de incidencias más frecuentes, costo asociado, sucursales con más problemas.

Cada reporte se puede exportar y agendar para envío automático por email semanal o mensual.

### 6.7. Análisis de tendencias

Para decisiones de mediano plazo, ingresá a Reportes > Tendencias. Seleccioná la métrica (ventas, tickets, incidencias, drivers, etc.) y el rango temporal (3 meses, 6 meses, 1 año).

El sistema muestra gráficos de tendencia con anotaciones automáticas de eventos relevantes: promociones lanzadas, cambios de menú, aperturas de sucursal, períodos especiales.

Esto te ayuda a entender qué intervenciones funcionaron, cuáles no, y cómo planificar las próximas.

### 6.8. Aprobación de apertura de nueva sucursal

Cuando se decide abrir una nueva sucursal en tu región, el proceso involucra varios pasos pero tu aprobación es uno de los críticos.

El equipo de Colaboradores prepara la nueva sucursal en la plataforma (configura datos, menú, zona, etc.) y la marca como "Pendiente de aprobación regional". Vos recibís la notificación.

Revisá:

- Configuración general (dirección, horarios, zona de cobertura).
- Menú asignado (debe coincidir con el menú regional o tener justificación de diferencias).
- Manager asignado (su perfil y experiencia).
- Capacidad inicial (cocina, staff, drivers).

Si todo está en orden, aprobá. La sucursal queda "Lista para apertura" y el Colaborador la activa en la fecha planificada.

### 6.9. Revisión de performance de Managers

Cada Manager tiene un perfil con métricas históricas: ventas, incidencias, satisfacción de cliente, performance vs. metas.

Ingresá a Staff > Managers de mi región para ver el listado. Tocá un Manager para ver su detalle.

Recomendamos hacer una revisión formal trimestral con cada Manager, usando estas métricas como base. Identificá fortalezas, áreas de mejora y plan de acción concreto.

### 6.10. Reasignación de Managers entre sucursales

En algunos casos es necesario mover un Manager de una sucursal a otra. Esto puede hacerse desde Staff > Managers, seleccionando el Manager y tocando "Reasignar sucursal".

El sistema te pide:

- Nueva sucursal asignada.
- Fecha efectiva de la reasignación.
- Manager interino para la sucursal anterior (si aplica).

Una vez confirmado, el Manager pierde acceso a la sucursal anterior y gana acceso a la nueva en la fecha indicada. El equipo de Colaboradores recibe la notificación para gestionar comunicación interna y traspaso operativo.

### 6.11. Auditoría de conversaciones de catering

Para tenants que usan el asistente de catering automatizado, el Regional Manager puede auditar las conversaciones que el sistema tuvo con clientes.

Ingresá a Catering > Auditoría de conversaciones. Filtrá por sucursal, fecha o cliente. Cada conversación muestra el intercambio completo entre el cliente y el asistente.

Revisá especialmente:

- Conversaciones que terminaron sin orden (por qué no convirtió).
- Conversaciones con quejas o frustración del cliente.
- Conversaciones con valor alto donde el cliente fue VIP.

Si encontrás patrones de error del asistente, reportalos al equipo de Colaboradores para ajuste.

### 6.12. Monitoreo de zonas de cobertura

Cada sucursal tiene una zona de cobertura definida. Desde Operaciones > Mapa regional podés ver todas las zonas de tu región superpuestas en un mapa.

Esto te permite identificar:

- Zonas con cobertura solapada (dos sucursales compitiendo por las mismas órdenes).
- Zonas sin cobertura (clientes potenciales no atendidos).
- Zonas con pocas órdenes vs. mucha cobertura (sucursal sobredimensionada).

Cambios en zonas de cobertura los configura el equipo de Colaboradores, pero vos podés solicitar ajustes desde esta pantalla.

---

## 7. MANUAL DEL COLABORADOR (BACK-OFFICE Y SOPORTE)

El Colaborador es el rol transversal que sostiene la operación de toda la plataforma. Esta sección cubre las tareas administrativas, de configuración y de soporte.

### 7.1. Onboarding de un nuevo restaurante

Cuando se incorpora un nuevo restaurante a AIA (un nuevo tenant), el proceso comienza con un kick-off comercial y termina con la primera orden procesada exitosamente.

El Colaborador responsable del onboarding ingresa a "Administración" > "Nuevo tenant" y completa:

- Datos legales del restaurante (razón social, RFC/RUT/NIT/equivalente, dirección legal).
- Persona de contacto principal y secundaria.
- Plan contratado y condiciones comerciales.
- Modalidad de payouts (plataforma, pool, directo a sucursal).
- Documentación de respaldo cargada (contrato firmado, identificación, comprobante bancario).

Una vez creado el tenant, el sistema asigna un ID único y abre la posibilidad de cargar sucursales, usuarios, menú y configuración operativa.

### 7.2. Creación de sucursales

Para cada tenant, ingresá a "Administración" > "Sucursales" > "Nueva sucursal". Configurá:

- Nombre comercial de la sucursal.
- Dirección física completa.
- Coordenadas GPS exactas (verificar en mapa).
- Horarios de atención por canal (puede tener horarios distintos para dine-in vs. delivery).
- Zonas de cobertura para delivery (dibujadas en mapa).
- Métodos de pago aceptados.
- Cuenta bancaria de payout (si el modelo es directo a sucursal).
- Configuración de impresoras y dispositivos.

Cada sucursal queda inicialmente en estado "Configurada — Pendiente de prueba". Antes de activarla, ejecutá las pruebas operativas descritas en la sección 7.8.

### 7.3. Carga del menú inicial

El menú puede cargarse de tres formas:

**Manualmente, ítem por ítem**: útil para menús chicos o cuando se quiere control total sobre cada detalle. Tocá "Nuevo ítem" y completá nombre, descripción, foto, precio, categoría, modificadores, tiempo de preparación.

**Importando desde plantilla**: si el restaurante tiene su menú en Excel o CSV con el formato de AIA, podés cargarlo de una vez. Descargá la plantilla desde "Menú" > "Importar", completala y subila.

**Desde menú de plataforma asociada**: si el restaurante ya está en alguna plataforma compatible (Uber Eats, Rappi, etc.), AIA puede importar el menú directamente con su API. Requiere autorización del restaurante.

Después de cargar, revisá ítem por ítem para verificar que precios, descripciones y fotos sean correctos.

### 7.4. Configuración de modificadores

Los modificadores son las opciones que el cliente puede ajustar al pedir un ítem: tamaño, cocción, extras, sin algo, salsa aparte, etc. Son críticos para que la operación de cocina sea precisa.

Ingresá a "Menú" > "Modificadores" y creá grupos de modificadores reutilizables. Por ejemplo, un grupo "Cocción" con opciones (jugoso, a punto, bien hecho). Después asignás estos grupos a los ítems que correspondan.

Configurá si cada grupo es de selección única u opciones múltiples, si es obligatorio responder o no, y si cada opción agrega costo o es gratis.

Hacé pruebas reales: pedí mentalmente cada ítem con cada modificador y verificá que la comanda salga clara y correcta.

### 7.5. Creación del primer usuario Manager

Una vez configurada al menos una sucursal, creá el usuario Manager. Ingresá a "Administración" > "Usuarios" > "Nuevo usuario".

Completá:

- Datos personales (nombre, DNI o equivalente, foto).
- Datos de contacto (email corporativo del restaurante, teléfono).
- Rol asignado: Manager.
- Sucursal asignada.
- Permisos específicos dentro del rol Manager (si el tenant tiene customizaciones).

El sistema envía un email al Manager con su contraseña temporal y un enlace al primer login.

Hacé un seguimiento 24 horas después de creado el usuario para confirmar que pudo ingresar y entiende las funciones básicas. Si no, agendá una sesión de capacitación.

### 7.6. Configuración de payouts

Los payouts son los pagos que el restaurante recibe por sus ventas. AIA soporta tres modalidades configurables por tenant:

**Plataforma**: AIA cobra todo, retiene su comisión y paga al restaurante en lote periódico. Modelo simple pero el restaurante no ve el dinero hasta el ciclo.

**Pool de restaurante**: el dinero se acumula en una cuenta del tenant y se distribuye según reglas internas. Útil para cadenas con múltiples sucursales.

**Directo a sucursal**: cada venta va directamente a la cuenta bancaria de la sucursal que la generó, menos la comisión. Modelo más complejo pero da liquidez inmediata.

La configuración inicial la define el equipo comercial y el Colaborador la implementa en el sistema. Cualquier cambio posterior debe ser solicitado formalmente por el cliente y aprobado por comercial.

### 7.7. Configuración de comisiones

Las comisiones se configuran a nivel de tenant y, opcionalmente, a nivel de sucursal o canal. Ingresá a "Administración" > "Comisiones" y definí:

- Comisión base por venta (típicamente un porcentaje).
- Comisión específica por canal (delivery, dine-in, catering pueden tener distintas).
- Comisión específica por tipo de pago (efectivo vs. tarjeta vs. otros).
- Comisiones especiales por convenio (clientes corporativos, marketplaces).

Toda configuración de comisiones queda registrada con fecha de inicio y fecha de fin. Cambios futuros no afectan órdenes ya procesadas.

### 7.8. Pruebas previas a la activación

Antes de activar comercialmente una nueva sucursal, ejecutá las siguientes pruebas:

**Prueba de orden completa**: creá una orden de prueba desde la app del consumidor (con cuenta de testing), procesala en la sucursal, asignale un driver de prueba y completá la entrega. Verificá que cada paso funcione.

**Prueba de pago**: probá los métodos de pago habilitados (tarjeta, efectivo, otros). Verificá que el dinero impacte correctamente según el modelo de payout configurado.

**Prueba de modificadores**: pedí ítems con todos los modificadores configurados. Verificá que la comanda imprima o muestre todo correctamente.

**Prueba de incidencias**: simulá una incidencia y procesala. Verificá que el flujo de reembolso funcione.

**Prueba de reportes**: generá reportes del día de prueba. Verificá que los números cuadren.

Solo después de pasar estas pruebas activá la sucursal comercialmente.

### 7.9. Soporte a Managers — flujos típicos

Los Managers contactan a Soporte por una variedad de razones. Estos son los flujos más frecuentes:

**"No veo mis pedidos"**: el Manager dice que no le aparecen órdenes nuevas. Verificá:

- ¿La sucursal está abierta en el sistema? (revisá estado)
- ¿Los canales están todos activos? (a veces se desactiva uno por error)
- ¿Hay alguna pausa activa que el Manager no recuerda?
- ¿El navegador del Manager está actualizado? (sugerí refrescar y verificar)

Si nada de esto resuelve, revisá si hay un incidente abierto en la plataforma (caída de algún componente) y comunicá el estado.

**"No me imprime la comanda"**: revisá:

- ¿La impresora está conectada y encendida?
- ¿Hay papel?
- ¿La integración entre AIA y la impresora está activa? (en "Configuración de sucursal" > "Dispositivos")
- ¿La impresora aparece online en la sección de dispositivos?

Si todo está bien y sigue sin imprimir, escalá al equipo técnico.

**"No me llegan los emails de catering"**: verificá:

- ¿El email configurado en el tenant es el correcto?
- ¿Hay reglas de spam o filtros en el email del cliente que estén bloqueando?
- ¿La integración del proveedor de catering está activa?

**"Un cliente dice que le cobraron dos veces"**: pedile al Manager:

- Número de orden y nombre del cliente.
- Captura de pantalla del extracto del cliente si la tiene.
- Verificá en el detalle de la orden si hay doble captura o doble autorización.

Si efectivamente hubo doble cobro, procesá el reembolso del cobro duplicado y comunicá al cliente con el número de comprobante.

### 7.10. Soporte a Drivers — flujos típicos

Los Drivers contactan a Soporte generalmente por estos motivos:

**"No aparezco en el mapa"**: el GPS no está reportando. Pedile al Driver:

- Verificar que la app tenga permisos de ubicación activos.
- Verificar que el GPS del celular esté encendido.
- Reiniciar la app y volver a ponerse disponible.
- Si persiste, instalar la última versión de la app.

**"No me llegan pedidos"**: verificá:

- ¿El Driver está marcado como disponible?
- ¿Su rating está por encima del mínimo del tenant?
- ¿Está dentro de la zona operativa de alguna sucursal abierta?
- ¿Tiene la documentación al día?

**"No me pagaron una entrega"**: pedí el número de orden, verificá en el sistema si está marcada como entregada y si el pago al driver está procesado. Si hay error, registrá el reclamo y aplicá el pago manualmente o escalá a finanzas.

### 7.11. Escalamiento al equipo técnico

Algunas situaciones requieren intervención del equipo técnico (desarrolladores). El Colaborador es el responsable de filtrar y escalar correctamente.

Situaciones que **deben** escalarse:

- Caída completa de una funcionalidad (nadie puede facturar, ningún driver ve pedidos, no se pueden generar reportes).
- Errores que afectan a múltiples tenants simultáneamente.
- Pérdida o inconsistencia de datos.
- Sospecha de intrusión o problema de seguridad.

Para escalar, abrí un ticket en el canal interno "#aia-soporte-tecnico" en Slack o usá la herramienta interna de tickets. Incluí:

- Descripción clara del problema.
- Quién lo reporta y cómo lo detectó.
- Cuántos tenants/sucursales/usuarios afectados.
- Hora de inicio.
- Pasos para reproducirlo si es posible.
- Capturas de pantalla.

No escales por escalar — un mal triage retrasa la atención de problemas reales.

### 7.12. Activación y desactivación de sucursales

Para activar o desactivar una sucursal:

**Activar**: solo después de pasar las pruebas operativas. Ingresá a "Administración" > "Sucursales", buscá la sucursal y tocá "Activar". El sistema te pide la fecha efectiva (puede ser inmediato o programado).

**Desactivar temporalmente**: usá esta opción cuando una sucursal cierra por mantenimiento, vacaciones u otra razón temporal. La sucursal desaparece del cliente pero su configuración se preserva.

**Desactivar definitivamente**: solo cuando el cierre es permanente. El sistema preserva el historial pero la sucursal no puede reactivarse sin un proceso especial.

Comunicá siempre el cambio al Manager y al Regional Manager de la sucursal afectada.

### 7.13. Cambio de cuenta bancaria de payout

Cuando un restaurante cambia su cuenta bancaria para recibir payouts:

- Recibí la solicitud formalmente (email o ticket) firmada por el contacto autorizado del tenant.
- Verificá la documentación bancaria nueva (comprobante de cuenta, identificación del titular).
- Validá que los datos coincidan con el titular legal del tenant.
- Ingresá los nuevos datos en "Administración" > "Tenants" > [tenant] > "Datos bancarios".
- Programá la fecha efectiva (recomendamos hacer el cambio al inicio de un nuevo ciclo de payout).

Documentá todo el proceso. Cambios bancarios son la operación más sensible — un error puede derivar dinero a una cuenta equivocada.

### 7.14. Gestión de disputas

Cuando un cliente disputa un cobro con su banco (chargeback), AIA recibe la notificación y el Colaborador debe armar la respuesta.

Ingresá a "Administración" > "Disputas". Cada disputa muestra:

- Orden afectada.
- Motivo alegado por el cliente.
- Monto disputado.
- Plazo para responder.

Recolectá la evidencia:

- Detalle de la orden con timestamps.
- Confirmación de entrega (foto del driver, firma si aplica).
- Comunicaciones con el cliente.
- Historial del cliente (¿es recurrente? ¿tiene otras disputas?).

Cargá la evidencia en el sistema y enviá la respuesta antes del plazo. Si ganás la disputa, el dinero permanece. Si la perdés, se debita la suma más una penalidad bancaria.

### 7.15. Reportes globales de la plataforma

El Colaborador con permisos elevados tiene acceso a reportes globales que cruzan múltiples tenants:

**Reporte de uso de la plataforma**: cuántas órdenes, cuántos tenants activos, cuántos usuarios conectados.

**Reporte de incidencias globales**: tipos de incidencias más frecuentes en toda la plataforma, identificación de problemas sistémicos.

**Reporte de performance técnico**: tiempos de respuesta de la plataforma, errores frecuentes, calidad del servicio.

Estos reportes son insumo para reuniones operativas y de mejora del producto. Generalmente se revisan semanalmente con el equipo técnico y comercial.

---

## 8. POLÍTICAS TRANSVERSALES

### 8.1. Confidencialidad de datos de clientes

Todos los usuarios de AIA (managers, drivers, regionales y colaboradores) manejan datos personales de clientes: nombres, direcciones, teléfonos, historial de compras, métodos de pago parcialmente visibles.

Está terminantemente prohibido:

- Compartir datos de clientes con terceros no autorizados.
- Usar datos de clientes para fines personales (contactarlos fuera del sistema, agregarlos a redes sociales).
- Tomar capturas de pantalla con datos de cliente y enviarlas por canales no oficiales.
- Discutir órdenes específicas con detalles identificables del cliente en redes sociales o conversaciones públicas.

La violación de esta política es causal de desvinculación inmediata y puede tener consecuencias legales según la legislación local de protección de datos.

### 8.2. Manejo de propinas

Las propinas son del Driver o del staff de sucursal, no de la empresa. AIA solo administra el flujo de cobro pero la propina se traspasa íntegra al destinatario.

Está prohibido a cualquier rol (Manager, Regional, Colaborador) retener, redistribuir o usar propinas para otros fines. Los reportes de propinas son auditados periódicamente.

### 8.3. Política de contraseñas

Toda contraseña en AIA debe cumplir:

- Mínimo 10 caracteres.
- Al menos una mayúscula, una minúscula, un número y un carácter especial.
- No reutilizar las últimas 5 contraseñas.
- Cambio obligatorio cada 90 días.

Está prohibido compartir contraseñas entre colegas o anotarlas en lugares visibles. Si necesitás que alguien acceda temporalmente, gestioná un usuario propio para esa persona.

### 8.4. Uso responsable del dashboard

El dashboard de AIA contiene información operativa sensible. Está prohibido:

- Dejar la sesión abierta en computadoras públicas o compartidas sin supervisión.
- Acceder al dashboard desde redes Wi-Fi públicas sin VPN (si tu tenant la provee).
- Compartir capturas del dashboard con personas ajenas a la operación.

Cerrá sesión al terminar tu turno. Bloqueá la pantalla si te alejás del puesto, aunque sea por minutos.

### 8.5. Reporte de irregularidades

Si detectás una irregularidad — pago no procesado, orden duplicada, comportamiento sospechoso de algún usuario, posible fraude — tenés la obligación de reportarla.

Usá el canal "Reportar irregularidad" en el menú de tu dashboard. Describí el caso con la mayor cantidad de detalle posible. Las irregularidades son revisadas por el equipo de cumplimiento dentro de las 48 horas.

Los reportes pueden ser anónimos si preferís. No hay represalias por reportar de buena fe.

### 8.6. Capacitación continua

Todo usuario de AIA debe completar:

- **Capacitación inicial** al ingresar, según su rol.
- **Capacitación trimestral** sobre nuevas funcionalidades y cambios.
- **Capacitación anual** sobre cumplimiento, manejo de datos y seguridad.

Las capacitaciones se notifican por email y deben completarse en plazo. La no realización puede implicar suspensión temporal de acceso al dashboard.

---

## 9. ANEXOS Y REFERENCIAS RÁPIDAS

### 9.1. Estados de orden — diccionario

- **Nuevo**: orden recibida, todavía no aceptada por la cocina.
- **Aceptado**: la cocina vio el pedido y empezó la preparación.
- **En preparación**: actualmente siendo preparado.
- **Listo**: terminado y esperando pickup o entrega.
- **En camino**: driver salió hacia el cliente.
- **Entregado**: completado exitosamente.
- **Cancelado**: anulado antes de completarse.
- **Devuelto**: salió pero volvió a la sucursal.
- **En disputa**: con reclamo abierto, sin resolución.

### 9.2. Estados de pago — diccionario

- **Pendiente**: aún no se intentó el cobro.
- **Autorizado**: el banco aprobó pero todavía no se descontó.
- **Capturado**: el dinero salió de la cuenta del cliente.
- **Conciliado**: AIA verificó que el dinero llegó.
- **Fallido**: el cobro no se procesó.
- **Reembolsado total**: se devolvió el 100%.
- **Reembolsado parcial**: se devolvió una parte.
- **En disputa**: chargeback abierto.

### 9.3. Códigos de colores en el dashboard

- **Verde**: todo en orden, podés proceder.
- **Amarillo**: atención, requiere monitoreo o aproximándose a un límite.
- **Rojo**: problema o límite excedido, requiere acción inmediata.
- **Gris**: pendiente, en proceso o estado neutro.
- **Azul**: información relevante pero no requiere acción.

### 9.4. Tiempos operativos estándar

| Acción | Tiempo objetivo |
|---|---|
| Aceptación de orden por cocina | < 1 minuto |
| Preparación de delivery normal | 15-20 minutos |
| Preparación de takeout | 12-15 minutos |
| Pickup del driver en sucursal | < 5 minutos en sucursal |
| Entrega al cliente desde pickup | 15-25 minutos según distancia |
| Respuesta a reclamo de cliente | < 5 minutos |
| Aprobación de Regional Manager | < 15 minutos |
| Resolución de incidencia técnica nivel 1 | < 30 minutos |

### 9.5. Canales de soporte

- **Soporte operativo en vivo**: chat embebido en el dashboard, botón "Ayuda" abajo a la derecha. Horario 06:00 a 23:00 hora local.
- **Soporte técnico crítico**: canal interno "#aia-soporte-tecnico" para Colaboradores.
- **Reporte de irregularidades**: opción dedicada en el menú del dashboard.
- **Soporte a Drivers**: dentro de la app móvil, sección "Soporte".

### 9.6. Contactos clave

- **Equipo comercial AIA**: para temas de plan, comisiones, condiciones contractuales.
- **Equipo de cumplimiento**: para temas legales, protección de datos, denuncias.
- **Equipo técnico AIA**: para incidentes de plataforma. Acceso solo a Colaboradores.
- **Tu Regional Manager**: primera línea de escalamiento operativo.

---

## 10. CIERRE

Este manual cubre los procedimientos operativos esenciales de AIA. La plataforma evoluciona constantemente, por lo que recomendamos consultar las notas de versión publicadas en el portal interno cada vez que el sistema notifique una actualización.

Para sugerencias de mejora a este manual, dudas no cubiertas o capacitaciones específicas, contactá al equipo de Operaciones de AIA por el canal habitual.

Operá bien. Cuidá al cliente. Cuidá al equipo.

**Fin del manual.**