# Turnos

Aplicación web sencilla para gestionar turnos de atención y cuatro mesas.

## Funciones

- Vista para tomar turnos anónimos y ver la lista de espera.
- Panel de administración para agregar turnos, mesas y asignar personas a mesas.
- Al finalizar una atención, la mesa se libera y puede asignarse automáticamente al siguiente turno.
- Anuncio por voz del número de turno y la mesa asignada, con control para activar o silenciar el audio.
- Turnos y estado guardados en el almacenamiento local del navegador.

## Uso

Abre `index.html` en un navegador moderno. Para los anuncios de voz, el navegador debe admitir la Web Speech API y tener el audio habilitado.

Los datos permanecen en el mismo navegador y dispositivo. Esta versión no usa un servidor compartido; para operar con varios dispositivos hace falta alojar una API y una base de datos.
