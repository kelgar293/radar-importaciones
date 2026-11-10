# Radar de importaciones

Panel HTML autónomo con indicadores de compra, volumen, valor CIF, precio ponderado y concentración por origen. Incluye filtros y exportación CSV.

Abra `index.html` en un navegador actualizado e ingrese la contraseña compartida por separado. El reporte está cifrado con AES-GCM de 256 bits y una clave derivada mediante PBKDF2-SHA256 (600.000 iteraciones). No requiere servidor ni dependencias externas.

La información representa la base suministrada, sin garantía de cobertura completa del mercado. La metodología se consulta dentro del panel.

El repositorio contiene únicamente el panel cifrado. No incluye el Excel, datos sin cifrar ni la contraseña. Recargar el archivo vuelve a solicitar el acceso.
