# Checkpoint 2 — Orquestación Multi-Agente Distribuida

Proyecto desarrollado en n8n para la gestión de expedientes jurídicos mediante una arquitectura Manager–Worker.

## Componentes

- Manager: clasifica solicitudes y deriva su ejecución.
- Worker 1: consulta expedientes en Google Sheets.
- Worker 2: valida y registra nuevos expedientes.

La comunicación utiliza Execute Sub-workflow
y contratos JSON estructurados.

Los datos utilizados son ficticios.
