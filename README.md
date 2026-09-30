# UCSUR-IA\_EC2\_MERC

Script de Dynamo (Python) para Revit que audita la nomenclatura de muros de drywall: identifica tipo y nivel de cada muro, y clasifica su estado según la sigla en el nombre del tipo — "OK" si contiene RH, "Fuera de estándar" si contiene ST o RF. Genera una tabla (Id, Nombre, Nivel, Estado) lista para exportar a Excel.

