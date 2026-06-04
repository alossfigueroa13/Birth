# Landing Birth - GitHub Pages

Este paquete esta listo para publicarse en GitHub Pages.

## Archivos importantes

- `index.html`: archivo principal de la landing. GitHub Pages lo abre automaticamente.
- `_next/`: estilos, scripts y fuentes de la landing. Debe subirse completa.
- `birth-logo-black.png`: logo usado por la landing.
- `.nojekyll`: archivo necesario para que GitHub Pages respete la carpeta `_next`.
- `ABRE-ESTE-ARCHIVO.html`: copia para abrir localmente si alguien quiere probarla en su computadora.

## Como publicarlo en GitHub Pages

1. Entra a https://github.com e inicia sesion.
2. Crea un repositorio nuevo, por ejemplo `birth-landing`.
3. Descomprime este ZIP.
4. Sube estos archivos y carpetas a la raiz del repositorio:
   - `index.html`
   - `_next`
   - `birth-logo-black.png`
   - `.nojekyll`
   - `README.md`
   - `ABRE-ESTE-ARCHIVO.html` opcional
5. Da clic en `Commit changes`.
6. En el repositorio, entra a `Settings`.
7. En el menu lateral, entra a `Pages`.
8. En `Build and deployment`, elige:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - carpeta: `/root`
9. Guarda con `Save`.
10. Espera de 1 a 3 minutos. GitHub mostrara la URL publica de la landing.

La URL normalmente queda asi:

```text
https://TU-USUARIO.github.io/birth-landing/
```

## Importante

No subas el ZIP cerrado como unico archivo del repositorio. Primero descomprimelo y sube el contenido. La carpeta `_next` y el archivo `.nojekyll` son necesarios para que la landing se vea bien publicada.
