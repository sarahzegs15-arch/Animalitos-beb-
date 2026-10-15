# 🍼 Animalitos a comer

Juego para bebés (2–3 años) para iPad con iOS 12.5.x. Funciona **sin internet** una vez instalado. Mismo diseño de los animalitos, ahora para darles de comer y dormirlos.

## Instalarlo (igual que la versión anterior)
1. Sube **todo el contenido de esta carpeta** a un repositorio de GitHub y activa **Settings → Pages** (rama `main`, carpeta `/ (root)`).
2. En el iPad, con wifi, abre la dirección en **Safari**, espera a que carguen los animalitos.
3. **Compartir → Añadir a pantalla de inicio**. Después funciona en modo avión.

## Para el bebé
- **Menú de la izquierda**: desliza con el dedo hacia arriba/abajo y toca el alimento: biberón, papilla, uvas, pan, agua, plátano y waffles.
- **Biberón / vaso**: arrástralo a la boquita y *mantén el dedo presionado*. Se acaba en ~4 s y se vuelve a llenar solo.
- **Papilla**: mete la cuchara en el plato y llévala a la boquita.
- **Uvas, pan, plátano, waffles**: arrastra una pieza a la boquita (o suéltala ahí).
- **Biberón seleccionado**: aparecen la **cama** (tócala para dormirlo, ronca) y arriba la **lámpara** (apaga/enciende la luz).
- Toca al animalito para despertarlo o para que haga su sonidito.

## Botones para mamá y papá (arriba a la derecha, mantener ~1 s)
🔈 silenciar · 🔄 volver a empezar.

## Ajustes rápidos
Al inicio de `app.js`: `DRAIN_S` (cuánto dura el biberón/vaso, 4 s), `REFILL_S` (cuánto tarda en rellenarse, 3 s) y `BITE_S` (tiempo de cada bocado).
Si cambias algo, sube la versión en `sw.js` (`animalitos-comida-v2`…).
