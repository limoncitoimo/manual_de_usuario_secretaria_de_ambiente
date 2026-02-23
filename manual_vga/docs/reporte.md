---
site_name: Manual de usuario
site_url: https://visorgeo.ambientebogota.gov.co/docs/manual/
site_description: Manual de usuario del Visor Geográfico Ambiental
site_author: Secretaría Distrital de Ambiente de Bogotá
copyright: Creative Commons 4

nav:
    - Presentación: index.md
    - Interfaz gráfica: interfaz.md
    - Navegación: navegacion.md
    - Búsqueda: ubicacion.md
    - Reportes: reporte.md
    - Autenticación: autenticacion.md
    - Posconsumo: posconsumo.md
    - Datos abiertos: datos_abiertos.md
    - Términos de uso y política de privacidad: terminos.md
    - Registro de cambios: changelog.md

extra_css:
  - css/extra.css

theme:
  font:
    text: Museo Sans
  palette:
    primary: css/extra.css
  features:
    - navigation.sections
    - navigation.instant
    - navigation.expand
    - navigation.tabs
    - toc.integrate
    - toc.follow
  name: material
  logo: 'images/logo.png'
  language: es

plugins:
  - search

extra:
  social:
    - icon: fontawesome/solid/paper-plane
      link: mailto:<visorsda@ambientebogota.gov.co>
      name: Correo
    - icon: fontawesome/solid/link
      link: https://visorgeo.ambientebogota.gov.co
      name: Sitio Web

copyright: Derechos reservados &copy; 2024 Secretaría Distrital de Ambiente

markdown_extensions:
  - abbr
  - admonition
  - attr_list
  - def_list
  - footnotes
  - meta
  - md_in_html
  - toc:
      permalink: true
  - tables
  - pymdownx.caret
  - pymdownx.mark
  - pymdownx.tilde
  - pymdownx.details
  - pymdownx.keys
  - pymdownx.critic
  - pymdownx.tasklist:
      custom_checkbox: true
---

Panel lateral de Reportes Ambientales

Antes de realizar cualquier reporte es necesario que realice la ubicación predial, ver en [Menú de ubicación](ubicacion.md), de otra forma no permite continuar con la generación del reporte.

Con la localización correcta predial, es posible la generación de dos reportes:

- **Inclusión predial en determinantes ambientales:** Este reporte generado a nivel predial, permite conocer las inclusiones de áreas protegidas a nivel Distrital de acuerdo al [Decreto 555 de 2021](https://www.alcaldiabogota.gov.co/sisjur/normas/Norma1.jsp?i=119582) y demás determinantes ambientales.
- **Jurisdicción predial:** este reporte generado a nivel predial, permite conocer la jurisdicción de entidades o instituciones para trámites de carácter ambiental.
- **Respuesta a emergencia ambientales:** Reporte correspondiente al módulo de Respuesta a Emergencias Ambientales.
- **Descarga de datos abiertos:** Reporte que corresponde a las estadísticas de descargas de [datos abiertos](datos_abiertos.md) por lo usuarios.


<figure markdown>
![Reportes Ambientales](images/Reporte/01-panel.png)
<figcaption>Reportes Ambientales</figcaption>
</figure>

Una vez identifique el reporte, haga clic en el botón Generar reporte para crear el documento reporte. El resultado del reporte muestra un enlace para la descarga del documento

<figure markdown>
![Resultado de la generación de reporte](images/Reporte/02-formato.png)
<figcaption>Resultado de la generación de reporte.</figcaption>
</figure>

!!! info "NOTA"

    Para usuarios visitantes deben ingresar el *captcha*, para usuarios autenticados y funcionarios de la SDA, pueden seleccionar a otros formatos adicionales. 

Al hacer clic en el enlace de descargar reporte, se descarga un documento en formato **PDF** con la información asociada del predio.

<figure markdown>
![Resultado de la generación de reporte a nivel predial](images/Reporte/03-reporte.png)
<figcaption>Resultado de la generación de reporte a nivel predial.</figcaption>
</figure>
