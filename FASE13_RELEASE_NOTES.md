# SOLIS PWA 1.13.0 — Fase 13

## Ingeniería de instrumentación

- Índice de instrumentos vinculado con I/O, requisitos y causa-efecto.
- Rangos, unidades, señal, alimentación, falla, área clasificada y certificación.
- Referencias controladas a hoja de datos, P&ID y hook-up.
- Lazos desde campo hasta PLC/DCS, con caja, cable, terminal y plano.
- Historial de calibraciones con certificado en R2 y huella SHA-256.
- Bloqueos para señales analógicas sin instrumento, lazos incompletos y calibraciones vencidas.
- Contrato de revisión actualizado a `solis.engineering-revision/1.3`.
- Exportación documental con índice de instrumentos y lazos.

## Persistencia y validación

La migración D1 `0011_great_gorgon.sql` crea las tres tablas del dominio con índices,
unicidad de TAG/I/O y control de versión. Build, lint y 40 pruebas automatizadas aprobados.
