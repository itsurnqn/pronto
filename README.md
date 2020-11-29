# Permisos

Los grupos de dividen en roles y tareas.

![](.gitbook/assets/ecommerce-pagina-producto.jpg)

Los roles tienen asignados un conjunto de permisos, las tareas solo uno puntual.

Cada usuario debe tener asignado un rol y cero o más tareas.

## Roles y Tareas

### Rol – Gestiones administrativas \[PRONTO\]

Mínimo conjunto de permisos para un administrativo.

Todo usuario nuevo de administración, se tiene que incluir en este grupo.

### Rol – Facturación \[CORE\]

Aca están todos los vendedores que también facturan. Y todos los administrativos.

  

![](.gitbook/assets/e-commerce_boutique.jpg)

### Rol - Administrador de facturación \[CORE\]

Solo Sandra y SG.

### Rol - Mostrar características de contabilidad completas \[CORE\]

Solo Sandra y SG.

### T01 – Recibos FSM

Para filtrar por sucursal.

### T02 – Recibos SMA

Para filtrar por sucursal.

### T1 – Cancelar Recibos

### T2 - Establecer recibo como borrador

### T3 – Modificar cotizaciones

## Requerimientos

### 10/11/2020

.1

Que un usuario de los grupos “Facturación” y “Gestiones administrativas”: pueda acceder a “Contabilidad/Información general”.

¿Se puede agregar el permiso a todo el grupo “Gestiones administrativas”?

Que tarea va a realizar? Tiene que cargar extractos bancarios?

O se podría crear un rol nuevo “Conciliaciones” y darle todos los permisos que necesita para conciliar.

.2

Que un usuario de los grupos “Facturación” y “Gestiones administrativas”: pueda cancelar \(y volver a borrador\) una factura de proveedor.

No hace falta hacer nada. Ya lo puede hacer porque está dentro del grupo “Facturación”

.3

Que un usuario de los grupos “Facturación” y “Gestiones administrativas”: pueda ver completo el menú “Contabilidad / Contabilidad”

Solo tiene que poder consultar o también modificar?

Porque si tiene que modificar conviene ponerla como Administrador de Facturación.

Sino, lo puedo agregar a “Gestiones administrativas”

