# Rifa - Grilla 00 al 99

App web de una sola página para gestionar una rifa con números del 00 al 99.

## Uso

Abrí `index.html` en el navegador (o publicalo con GitHub Pages). Por cada venta:

1. Tocá el número vendido en la grilla.
2. Cargá el nombre del comprador y una referencia (celular o Instagram).
3. Guardá. El número queda marcado en verde.

Los datos se guardan automáticamente en el navegador (localStorage). Para no perder
la información, usá el botón **Exportar backup** cada tanto y guardá el archivo
`.json` generado; con **Importar backup** podés restaurarlo en cualquier dispositivo.

### Otras funciones

- **Buscador**: filtra la grilla por número, nombre o referencia.
- **Precio por número**: si lo completás, la app calcula el total recaudado.
- **Reiniciar todo**: borra todas las ventas cargadas (pide confirmación).

## Publicar con GitHub Pages

1. En GitHub, andá a *Settings > Pages*.
2. Como fuente elegí la rama `main` (o la que uses) y la carpeta raíz.
3. Guardá; GitHub te da una URL pública para usar la app desde el celular.
