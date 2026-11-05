# Comercializadora Ángel

App para manejar el inventario de la bodega desde el celular.

Entrar con:
- usuario: admin
- clave: admin123

Qué trae:
- Inventario con buscador y aviso de stock bajo.
- Productos, categorías y proveedores.
- Usuarios y roles (esto solo lo ve el admin).
- Entradas y salidas con su historial.
- Informes PDF de entradas, salidas, stock normal, stock bajo e inventario completo.

Para correrlo: abrir la carpeta en Android Studio y darle Run. Necesita Android 11 o superior.

Los PDF se guardan en Descargas/InformesAlmacen.

La base es SQLite local (BD_EJEMPLO.db) y se crea sola la primera vez con algunos productos de ejemplo.