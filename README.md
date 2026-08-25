# Conociéndonos 2.0 — Prototipo navegable (Iteración 1)
Prototipo navegable de **Conociéndonos 2.0 — Familia · Escuela · Puente**, la evolución de la
bitácora doméstica "Conociéndonos" hacia una herramienta de acompañamiento situado entre
familia y escuela.

> ⚠️ **Esto es un prototipo, no la aplicación final.** Todos los datos que se ven al navegar
> (personas, procesos, conexiones, autorizaciones) son **ficticios** y existen solo en la
> memoria del navegador mientras la pestaña está abierta. No hay servidor, no hay base de
> datos y no se guarda ninguna información real de niñas, niños o familias.

## ¿Qué muestra este prototipo?

A diferencia de la primera versión de Conociéndonos (que registraba rasgos de temperamento),
esta iteración se enfoca en las **reglas de acceso y gobernanza de la información**:

- **Espacios separados** — Familia y Escuela ven contenido independiente; nunca se combina
  automáticamente.
- **Procesos** — el objeto central ya no es "cómo es este niño o niña", sino una situación
  concreta con observaciones, estrategias y resultados asociados.
- **Puente Familia-Escuela** — conexiones explícitas entre una familia y una cuenta
  institucional, donde solo se comparten elementos puntuales, no todo el historial.
- **Autorizaciones con vigencia** — permisos con fecha de expiración y opción de revocación.
- **Panel de trazabilidad** — un registro simulado de las acciones realizadas durante la
  sesión, con fines de demostración.

## Cómo probarlo

1. Entra a la URL publicada con GitHub Pages (o abre `index.html` sirviéndolo por `https://`
   o `localhost`; abierto directo como archivo local el Service Worker no se activa, pero el
   prototipo funciona igual).
2. Inicia sesión con los datos de ejemplo ya precargados en el formulario.
3. Elige un espacio (Familia o Escuela) y navega libremente — nada de lo que hagas se
   guarda de forma permanente.

## Instalación como app (PWA)

El prototipo puede instalarse en un teléfono o computadora como aplicación independiente
(ícono en la pantalla de inicio, funciona sin conexión salvo por la primera carga), gracias
al `manifest.json` y al Service Worker (`sw.js`) incluidos.

## Estado del proyecto

Este repositorio contiene la **Iteración 1** del prototipo de la Fase 7. Forma parte del plan
maestro de Conociéndonos 2.0, desarrollado con un equipo de trabajo mixto (dirección del
proyecto, especificación, auditoría técnica y contraste de investigación) antes de pasar a
una siguiente fase de desarrollo.

## Licencia

Este proyecto se publica bajo licencia MIT — ver [`LICENSE`](./LICENSE).
