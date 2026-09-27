# Excel / Spreadsheet Design Guide

## Paleta corporativa
| Uso | Color | Hex |
|---|---|---|
| Navy principal | Encabezados y navegación | #0B1F3A |
| Azul corporativo | Acciones y progreso | #1769E0 |
| Azul claro | Planificado y fondos | #EAF2FF |
| Verde | En tiempo / correcto | #159570 |
| Ámbar | Atención | #D89520 |
| Rojo | Crítico / bloqueado | #D94B62 |
| Gris línea | Separadores | #E6EBF2 |

## Reglas de formato para Excel
1. Congelar la primera fila.
2. Aplicar filtros a todos los encabezados.
3. Usar formato de fecha `dd-mmm-yyyy`.
4. Mostrar `% Complete` como porcentaje.
5. Aplicar formato condicional a `Status` y `Risk Level`.
6. Mantener títulos en navy con texto blanco.
7. Utilizar filas alternadas en tablas largas.
8. No utilizar más de cuatro colores de estado.
9. Mantener columnas de notas y comentarios al final.
10. Usar validación de datos para Status, Priority y Health.

## Hojas recomendadas
- Executive Dashboard
- Project Portfolio
- Task Tracker
- Milestones
- Risk Register
- Decisions & Actions

## Fórmulas útiles
- Avance promedio: `=AVERAGE(I2:I100)`
- Tareas vencidas: `=COUNTIFS(H2:H100,"<"&TODAY(),F2:F100,"<>Completed")`
- Tareas bloqueadas: `=COUNTIF(F2:F100,"Blocked")`
- Riesgos altos: `=COUNTIF(F2:F100,"High")`
