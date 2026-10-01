# Carpinchos BCH Argentina — Parte 2

Arte y metadata de **2.500 piezas**, números **2501–5000**, de una colección de **5.000 NFT únicos**.

Proyecto de [BCH Argentina](https://www.bcharg.com/). Cuenta oficial: [bchargentina](https://github.com/bchargentina).

## Estado

El arte está terminado. **Los tokens todavía no fueron emitidos y la venta no está abierta.** El Category ID oficial, el BCMR autenticado y el enlace de compra se publicarán después de las pruebas de emisión.

Precio previsto: **0,075 BCH por NFT**, en tres rondas de **2.000, 1.500 y 1.500**. El intervalo orientativo es de 6–8 semanas, sujeto a ventas y demanda; aún no hay fecha de lanzamiento.

## Archivos

- `images/`: WebP finales a 1254×1254, calidad 95.
- `metadata/`: nombre, descripción, atributos y URL de imagen fijada al commit del arte.
- `SHA256SUMS`: hashes SHA-256 de las imágenes.
- `manifest.json`: numeración, combinaciones, pesos y hashes.
- `collection.json`: configuración y estado de la colección.
- [BENEFICIOS.md](BENEFICIOS.md): crédito para la membresía del Club, airdrops de ARG Tokens y apoyo a la adopción de BCH.
- [LICENSE.md](LICENSE.md): estado de los derechos de uso.

Los JSON individuales no sustituyen el BCMR de CashTokens. La división en dos repos es únicamente de almacenamiento y no representa dos colecciones ni las rondas de venta.

## Integridad

Commit del arte: `b5ba20ba843bd0798dbed7e66647b1793e4d9643`. Los 5.000 archivos finales fueron comprobados: cero combinaciones o imágenes duplicadas, incluso al comparar los píxeles decodificados.

Para verificar esta parte en Linux:

```sh
sha256sum -c SHA256SUMS
```

En macOS: `shasum -a 256 -c SHA256SUMS`.

Otra parte: [carpinchos-nft-01](https://github.com/bchargentina/carpinchos-nft-01).
