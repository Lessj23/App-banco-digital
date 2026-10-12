# DreamBank

Prototipo web responsive de banca digital con datos ficticios y operaciones simuladas. No está conectado a bancos, pagos ni cotizaciones financieras.

## Abrir

Abre `index.html` en un navegador o ejecuta un servidor estático desde esta carpeta:

```sh
python3 -m http.server 4173
```

Después visita `http://localhost:4173`.

## Explorar

- En la portada, elige **Iniciar sesión** y luego **Entrar al demo con Mariana**.
- También puedes crear un perfil ficticio.
- Los cambios se guardan en el almacenamiento local del navegador. En **Cerrar sesión y restablecer demo** puedes volver a los datos iniciales.
- Las tasas de monedas son valores fijos de ejemplo. Transferencias, depósitos, tarjetas y saldos no representan operaciones reales.

## Archivos

- `index.html`: estructura y metadatos.
- `styles.css`: sistema visual y adaptación responsive.
- `app.js`: navegación, contenido, estado local y flujos simulados.
