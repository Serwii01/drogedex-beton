# DROGEDEX / BETON

Tercera versión de Drogedex, la más minimalista: estética de club de hormigón (*Beton* en alemán), monocroma y brutalista. TFG de Psicología.

- **Sin color:** solo negro, grises de hormigón y blanco. Las familias se distinguen por tonos de gris y los niveles de riesgo por gris y símbolo (`○ · − △ ▲ ✕`). Cuanto más claro, más peligroso.
- **Tipografía:** Inter Tight fina, en mayúsculas y muy espaciada; IBM Plex Mono para el texto.
- **Política de fotos:** en la pista no hay color. Las fotos reales se ven en blanco y negro y recuperan el color al pasar el cursor.
- **Funciones:** las mismas que la versión NAVE (comprobador de mezclas, comparador, psicología con DSM-5, mapa, cronología, emergencias, glosario, galería, citar en APA, impresión en PDF).

Las otras versiones están en `../drogedex` (techno berlinés) y `../drogedex-nave` (nave rave / ruin bar).

## Desarrollo
```bash
npm install
npm run dev
npm run build
```

El sistema visual está en `src/styles/beton.css` y conserva los nombres de variable de la versión NAVE para reutilizar componentes. `--hazard` es el único acento: el blanco.

## Vercel
Se importa el repositorio en vercel.com/new. Astro se detecta solo.
