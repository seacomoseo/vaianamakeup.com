# vaianamakeup.com

[![vaianamakeup.com](/assets/media/logo.png)](https://vaianamakeup.com/)
- [![Netlify Status](https://api.netlify.com/api/v1/badges/77289ad4-5acb-47ee-9c00-e6c007091792/deploy-status)](https://app.netlify.com/sites/vaianamakeup/deploys)


## STEPS

### Local

- Design
  - GENERAL
    - `config.yml`
  - IMG
    - `assets/media/` folder ⏩ [Compress image tool](https://compressor.io/)
      - `fondo.jpg`
  - FONTS
    - Fonts that not be in Google Fonts:
      - .otf/.ttf files in `assets/fonts` + rename
      - You need the `vaianamakeup_tools` proyect in `../_tools` folder
      - Run `make fonts` comand
      - `Family` + `Style` + `Weight` must match in `config.yml ⏩ params.fonts` + `_fonts.scss` (and disable `params.fonts.google_fonts` if appropriate)
  - IMG
    - `assets/media/*`
  - REDIRECTS
    - `assets/redirects.md`
  - ROBOTS
    - `assets/robots.md`
  - Try in Safari and Firefox
  - If Multilanguaje and Multihosting, add `cp ./public/[es|en]/404.html ./public/` in `netlify.toml ⏩ build.command`

### After client validate web

##### Services Layout

1. [Servicios vaianamakeup.com](https://docs.google.com/spreadsheets/d/1U9d7QvDSPa84rzpZQdduRAuWJ4vCG1zJdf1_2DLJsKA/) ⏩ `File ⏩ Make a copy` ⏩ Select client directory.
1. Change the info.
1. `Share` ⏩ Add emails of collaborators with `Editor` permission.


##### Instructions

Send to all collaborators next links:
1. `Services Layout`
1. [Entrega](https://seacomoseo.com/entrega/).