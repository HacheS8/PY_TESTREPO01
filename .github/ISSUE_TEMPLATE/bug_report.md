---
name: Reporte de bug
about: Reporta un error para ayudarnos a mejorar
title: "[BUG] <módulo>: <descripción breve>"
labels: bug, triage
assignees: ''
---

## 1. Resumen
<!-- Una o dos frases: qué falla y dónde. -->

## 2. Severidad e impacto
- **Severidad:** <!-- Crítica (sistema caído / pérdida de datos) | Alta (función clave rota) | Media (hay workaround) | Baja (cosmético) -->
- **Usuarios / clientes afectados:** <!-- Cantidad estimada o segmento -->
- **¿Bloquea un flujo crítico?** <!-- Sí / No. Cuál -->
- **¿Existe workaround?** <!-- Sí / No. Describirlo -->
- **¿Es una regresión?** <!-- Sí / No. Última versión donde funcionaba -->

## 3. Comportamiento esperado
<!-- Qué debería ocurrir. -->

## 4. Comportamiento actual
<!-- Qué ocurre realmente. -->

## 5. Pasos para reproducir
1. Ir a '...'
2. Hacer clic en '...'
3. Ingresar '...'
4. Ver el error

**Frecuencia:** <!-- Siempre | Intermitente (~X de cada 10) | Una sola vez -->
**¿Reproducible en otros entornos/usuarios?** <!-- Sí / No / No probado -->

## 6. Datos de prueba
<!-- Payload, ID de registro, usuario de prueba, archivo de ejemplo.
     NO incluir credenciales, tokens ni datos personales reales. -->

## 7. Evidencia
<!-- Capturas, video/GIF, logs, stack trace. -->

<details>
<summary>Logs / Stack trace</summary>

```
Pegar aquí
```

</details>

**Request / Response (si aplica):**
- Endpoint: 
- Método: 
- Código HTTP: 
- Request ID / Trace ID: 

## 8. Entorno
| Campo | Valor |
|---|---|
| Entorno | <!-- Producción / Staging / Desarrollo / Local --> |
| Versión / commit / release | |
| Fecha y hora del incidente (con zona horaria) | |
| Navegador y versión | |
| Sistema operativo | |
| Dispositivo | |
| Versión de runtime (Node, Python, Java, etc.) | |
| Versión de app móvil | |
| Rol / permisos del usuario | |

## 9. Contexto adicional
<!-- Feature flags activos, integraciones involucradas, cambios recientes,
     issues o PRs relacionados (#123). -->

## 10. Causa probable (opcional)
<!-- Hipótesis o archivo/línea sospechosa, si la conoces. -->

## 11. Checklist antes de enviar
- [ ] Busqué en issues abiertos y cerrados y no es un duplicado
- [ ] Probé en la última versión disponible
- [ ] Incluí pasos de reproducción claros
- [ ] Adjunté evidencia (logs, capturas o video)
- [ ] Eliminé datos sensibles (credenciales, tokens, datos personales)