# Códigos para Práctico — Prof. Ivanna Escala (LAPIS 2026)

Repositorio de materiales y códigos para el práctico de la Profesora Ivanna Escala (*Decoding Galaxy Assembly with the Andromeda System*) en la escuela de astrofísica **XII LAPIS 2026**.

## Proyecto y Datos

- **Proyecto**: Combinación de historias de formación estelar basadas en HST (PHAT) y mediciones de abundancias químicas de estrellas individuales basadas en JWST en el disco de M31 para analizar cómo el *starburst* global de M31 impacta su evolución química.
- **Datos y catálogos**: Serán provistos por la profesora.

## Software y Estructura

- `VICE/` — Submódulo con el fork de [giganano/VICE](https://github.com/giganano/VICE) en [`LAPIS-2026/VICE`](https://github.com/LAPIS-2026/VICE) ([documentación](https://vice-astro.readthedocs.io/en/latest/)).
- `emcee/` — Submódulo con el fork de [dfm/emcee](https://github.com/dfm/emcee) en [`LAPIS-2026/emcee`](https://github.com/LAPIS-2026/emcee) ([documentación](https://emcee.readthedocs.io/en/stable/)).
- `dynesty/` — Submódulo con el fork de [joshspeagle/dynesty](https://github.com/joshspeagle/dynesty) en [`LAPIS-2026/dynesty`](https://github.com/LAPIS-2026/dynesty) ([documentación](https://dynesty.readthedocs.io/en/v3.1.0/)).

## Lecturas Previas Sugeridas

- [Williams et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJ...806...48W/abstract)
- [Nidever et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024IAUS..377..115N/abstract)
- [Escala et al. (2026, Sección 4.1)](https://ui.adsabs.harvard.edu/abs/2026arXiv260325909E/abstract)
- [Escala et al. (2021, Secciones 1 y 4.2)](https://ui.adsabs.harvard.edu/abs/2021AJ....162...45E/abstract)

## Cómo clonar este repositorio (incluyendo submódulos)

```bash
git clone --recurse-submodules https://github.com/LAPIS-2026/ivaescala.git
```

Si ya clonaste el repositorio sin `--recurse-submodules`, inicializa y descarga todos los submódulos con:

```bash
git submodule update --init --recursive
```
