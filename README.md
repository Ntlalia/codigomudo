# codigomudo
¿Que hace la funcion? calcularImpuesto()
Calcula el monto neto de un salario después de aplicar una deducción
basada en una tasa, con un ajuste adicional si la región es El Salvador (SV)  deducción al monto y le suma 13.

¿Que significan los parametros?
salario: Monto base sobre el cual se calcula la deducción.
tasa: Porcentaje utilizado para calcular el descuento (se le aplica un factor del 15%).
region: Código de país. Si es `"SV"`, se aplica la siguiente lógica

Si region no es "SV":
resultado = salario - deduccion 
al salario se le restas la deducción.
Si region SÍ es "SV":
resultado = (salario - deduccion) + 13

¿Como se usa?
Se le pasa el salario, la tasa y la región. La función retorna el
monto neto luego de aplicar la deducción (y un ajuste extra de +13 si la región es SV.
