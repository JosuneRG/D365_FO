# Performance Notes D365FO

## Buenas prácticas

- Preferir `update_recordset` sobre loops
- Evitar `while select` innecesarios
- Usar índices correctamente
- Minimizar llamadas a base de datos

## Evitar

- lógica dentro de loops pesados
- `doUpdate()` (salta lógica estándar)
- selects sin filtros