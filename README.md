Descripción General del Proyecto

Este dataset corresponde a los registros de campañas de marketing directo de una institución bancaria portuguesa. Las campañas se realizaron principalmente a través de llamadas telefónicas, con el objetivo de convencer a los clientes de suscribir un depósito a plazo fijo.

Cada fila representa un cliente contactado en una campaña, y contiene tanto información personal y financiera como detalles específicos de la interacción en la campaña.

Número de instancias: 45.211 registros.

Número de variables: 17 (16 predictoras + 1 variable objetivo).

Variable objetivo:

y: indica si el cliente finalmente suscribió el depósito a plazo fijo (yes o no).

Variables incluidas

Datos del cliente:

age (edad),

job (profesión),

marital (estado civil),

education (nivel educativo),

default (si tiene impago de crédito),

housing (si tiene préstamo hipotecario),

loan (si tiene otro préstamo personal).

Datos de contacto/campaña actual:

contact (tipo de comunicación: fijo o celular),

month (mes del último contacto),

day (día del mes del último contacto),

duration (duración de la llamada en segundos),

campaign (número de contactos durante esta campaña).

Historial de campañas previas:

pdays (días desde el último contacto previo, -1 si nunca),

previous (número de contactos previos),

poutcome (resultado de la campaña anterior).

Variable financiera:

balance (saldo medio anual en euros en la cuenta bancaria del cliente).
