# Códigos para Práctico — Prof. Ivana Escala (LAPIS 2026)

Repositorio de materiales y códigos para el práctico de la Profesora Ivana Escala en la escuela de astrofísica **LAPIS 2026**.

## Estructura

- `VICE/` — Submódulo con el fork de [giganano/VICE](https://github.com/giganano/VICE) en [`LAPIS-2026/VICE`](https://github.com/LAPIS-2026/VICE).
- `emcee/` — Submódulo con el fork de [dfm/emcee](https://github.com/dfm/emcee) en [`LAPIS-2026/emcee`](https://github.com/LAPIS-2026/emcee) ([documentación](https://emcee.readthedocs.io/en/stable/)).
- `dynesty/` — Submódulo con el fork de [joshspeagle/dynesty](https://github.com/joshspeagle/dynesty) en [`LAPIS-2026/dynesty`](https://github.com/LAPIS-2026/dynesty) ([documentación](https://dynesty.readthedocs.io/en/v3.1.0/)).

## Cómo clonar este repositorio (incluyendo submódulos)

```bash
git clone --recurse-submodules https://github.com/LAPIS-2026/ivaescala.git
```

Si ya clonaste el repositorio sin `--recurse-submodules`, inicializa y descarga todos los submódulos con:

```bash
git submodule update --init --recursive
```

