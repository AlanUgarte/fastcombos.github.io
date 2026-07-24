# FastCotillón

Página única de catálogo de cotillón (`index.html`), con todos los artículos de la
categoría "Cotillon" del listado de precios del proveedor, precio +30% sobre el
bruto por unidad o display. Carrito, buscador, filtro por línea, combos armados y
pedido por WhatsApp (`remito.html` genera el comprobante). Los datos de productos
viven en el array `PRODUCTS.cotillon` dentro de `index.html`, ordenados primero
los que tienen imagen y luego los que no; para actualizarlos, volvé a exportar el
listado de precios del proveedor y regenerá ese array.
