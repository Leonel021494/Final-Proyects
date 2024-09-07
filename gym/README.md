Objetivo del proyecto
La cadena de gimnasios Model Fitness está desarrollando una estrategia de interacción con clientes basada en datos analíticos.

Uno de los problemas más comunes que enfrentan los gimnasios y otros servicios es la pérdida de clientes. ¿Cómo descubres si un/a cliente ya no está contigo? Puedes calcular la pérdida en función de las personas que se deshacen de sus cuentas o no renuevan sus contratos. Sin embargo, a veces no es obvio que un/a cliente se haya ido: puede que se vaya de puntillas.

Los indicadores de pérdida varían de un campo a otro. Si un usuario o una usuaria compra en una tienda en línea con poca frecuencia, pero con regularidad, no se puede decir que ha huido. Pero si durante dos semanas no ha abierto un canal que se actualiza a diario, es motivo de preocupación: es posible que tu seguidor o seguidor/a se haya aburrido y te haya abandonado.

En el caso de un gimnasio, tiene sentido decir que un/a cliente se ha ido si no viene durante un mes. Por supuesto, es posible que estén en Cancún y retomen sus visitas cuando regresen, pero ese no es un caso típico. Por lo general, si un/a cliente se une, viene varias veces y luego desaparece, es poco probable que regrese.

Con el fin de combatir la cancelación, Model Fitness ha digitalizado varios de sus perfiles de clientes. Tu tarea consiste en analizarlos y elaborar una estrategia de retención de clientes.

Descripción de datos
Model Fitness te aportó archivos CSV que contienen los datos sobre la cancelación de un mes en concreto e información del mes que lo precedía. El dataset incluye los siguientes campos:

'Churn' — la cancelación para el mes en cuestión
Campos de dataset actuales:

Datos de usuario del mes anterior
'gender'
'Near_Location' — si el usuario vive o trabaja en el vecindario donde se encuentra el gimnasio
'Partner' — si el usuario es un trabajador de una compañía asociada (el gimnasio tiene empresas asociadas cuyos empleados obtienen descuentos; en esos casos el gimnasio almacena información sobre los empleadores de los clientes)
Promo_friends — si el usuario originalmente se inscribió mediante una oferta "trae a un amigo" (se utilizó el código promocional de un amigo cuando pagaron el primer abono)
'Phone' — si el usuario aportó el número de teléfono
'Age'
'Lifetime' — el tiempo (en meses) desde que el usuario llegó por primera vez al gimnasio
Datos del registro de visitas y compras y datos sobre el estado actual de la membresía

'Contract_period' — 1 mes, 3 meses, 6 meses o 1 año
'Month_to_end_contract' — los meses que faltan hasta que expire el contrato
'Group_visits' — si el usuario participa en sesiones grupales
'Avg_class_frequency_total' — frecuencia media de visitas por semana a lo largo de la vida del cliente
'Avg_class_frequency_current_month' — frecuencia media de visitas por semana en el mes anterior
'Avg_additional_charges_total' — cantidad total de dinero gastado en otros servicios del gimnasio: cafetería, productos deportivos, cosméticos, masajes, etc.
