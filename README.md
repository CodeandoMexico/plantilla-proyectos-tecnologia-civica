![Logo Codeando México](/recursos/imagenes/logo-cmx.svg#gh-light-mode-only)
![Logo Codeando México](/recursos/imagenes/logo-cmx-blanco.svg#gh-dark-mode-only)

[![website](https://img.shields.io/badge/website-CodeandoMexico-00D88E.svg)](http://www.codeandomexico.org/)
[![slack](https://img.shields.io/badge/slack-CodeandoMexico-EC0E4F.svg)](http://slack.codeandomexico.org/)


# Guía y plantilla para proyectos de Codeando México

A lo largo de los años, el número de proyectos y la variedad de personas que han colaborado ha ido aumentando, y como resultado la manera en la que están estructurados los proyectos en Codeando México es muy variada también. 

Este repositorio es una plantilla con la **estructura mínima** que debería tener cada proyecto de la comunidad y de la organización Codeando México, y debe servir de guía para los nuevos proyectos que se vayan a integrar al repositorio de la organización.


## Índice

- [Guía y plantilla para proyectos de Codeando México](#guía-y-plantilla-para-proyectos-de-codeando-méxico)
  - [Índice](#índice)
  - [Nombre del proyecto](#nombre-del-proyecto)
  - [[Archivo] Read Me](#archivo-read-me)
    - [[Sección] Referencias](#sección-referencias)
    - [[Sección] Créditos](#sección-créditos)
  - [[Archivo] Código de conducta](#archivo-código-de-conducta)
  - [[Archivo] Licencia de uso](#archivo-licencia-de-uso)
  - [[Archivo] Cómo contribuir al proyecto](#archivo-cómo-contribuir-al-proyecto)
  - [[Archivo] Hacklog](#archivo-hacklog)
  - [[Carpeta] Documentación](#carpeta-documentación)
  - [[Carpeta] Recursos](#carpeta-recursos)

## Nombre del proyecto

La recomendación es que el nombre del repositorio del proyecto esté en español, dado que la principal audiencia de nuestros proyectos es población de la república mexicana y América Latina. Si el nombre del proyecto tiene más de una plabra, estas deben estar en minúsculas y separadas por guiones.

* ✅  `estandar-datos-legislativos`, `aprende-con-datos`, `guia-participacion-digital`.
* ❌  `BlockchainForTheWin`, `OTRA_APP_DE_RAILS`

## [Archivo] Read Me

```
‼️ Este archivo es OBLIGATORIO
ℹ️ Este archivo debe llamarse README.md o LEEME.md y residir en la carpeta raíz del proyecto
```

El archivo Read Me contiene la información básica del proyecto:

  * En qué consiste
  * Por qué es útil
  * Cómo se puede usar
  * Dónde se puede obtener ayuda
  * [Referencias](#sección-referencias)
  * [Créditos](#sección-créditos): Quien mantiene y contribuye al proyecto


El ficherto que estás leyendo ahora mismo es el Read Me de este repositorio, y lo puedes tomar como referencia, para el uso de los logos y ver ejemplos de secciones que se suelen incluir en este tipo de  archivo.

### [Sección] Referencias

```
❗️ Esta sección es OPCIONAL
```

En nuestros proyectos solemos aplicar metodologías de trabajo desarrolladas por otras organizaciones o gobiernos, y en esta sección incluimos los enlaces a los documentos de referencia. 

### [Sección] Créditos

```
‼️ Esta sección es OBLIGATORIA
```

Uno de los pilares de nuestro trabajo es la colaboración multidisciplinar. En Codeando México colaboramos con gobiernos de todos los niveles (federal, estatal, municipal), organizaciones internacionales y de la sociedad civil y con un gran número de colaboradores individales.

En esta sección intentamos dar el crédito a todos los colaboradores, ya que sin ellos no sería posible nuestro trabajo.

Antes de incluir el nombre y contacto de un colaborador, es necesario contar con su visto bueno.

## [Archivo] Código de conducta

```
‼️ Este archivo es OBLIOGATORIO
ℹ️ Este archivo debe llamarse CODE_OF_CONDUCT.md o CODIGO_DE_CONDUCTA.md y residir en la carpeta raíz del proyecto
```

El código de conducta regula cómo se deben comportar las personas que participan en los proyectos de Codeando México.

La última versión de nuestro código de conducta se encuentra en el [repositorio de Comunidad](https://github.com/CodeandoMexico/comunidad/blob/master/CODIGO-DE-CONDUCTA.md).

Todos los repositorios deben enlazar directamente al código de conducta del repositorio de comunidad.

## [Archivo] Licencia de uso

```
‼️ Este archivo es OBLIOGATORIO
ℹ️ Este archivo debe llamarse LICENSE o LICENCIA y residir en la carpeta raíz del proyecto
```

A diferencia del software propietario, como por ejemplo Microsoft Word, todos los proyectos de la comunidad y de la organización Codeando México son proyectos de [software libre](https://www.gnu.org/philosophy/free-sw.es.html).

Uno de los requisitos del software libre es que este sea publicado bajo licencias que permitan su copia, uso, modificación y redistribución sin limitaciones a las libertades de los usuarios, y el cídigo fuente del proyecto debe de tener un archivo que especifique la licencia bajo la cual se está publicando el proyecto.

En algunos casos, un proyecto puede estar badado en proyectos o librerías de terceros, por lo cual antes de elegir la licencia es necesario revisar las licencias de estos proyectos o librerías para no incurrir en una violación de los derechos establecidos en esas licencias.

Por ejemplo, el proyecto Decidim Monterrey está basado en el proyecto Decidim, y este se publica bajo la licencia GNU Affero General Public License v3.0, la cual especifica que si usas Decidim, tu proyecto debe ser liberado bajo la misma licencia.

Codeando México no tiene una recomendación sobre qué licencia usar en específico, pero como referencia estos son algunos ejemplos de licencias que hemos usado en nuestros proyectos:
* [MIT](https://opensource.org/licenses/MIT)
* [GNU Affero General Public License v3.0](https://choosealicense.com/licenses/agpl-3.0/)
* [Creative Commons Attribution Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)


[Esta herramienta](https://choosealicense.com/appendix/) puede ser de utilidad a la hora de seleccionar una licencia para el proyecto.

## [Archivo] Cómo contribuir al proyecto

```
❗️ Este archivo es OPCIONAL
ℹ️ Este archivo debe llamarse CONTRIBUTING.md o CONTRIBUYE.md y residir en la carpeta raíz del proyecto
```

En la medida de los posible, en Codeando México intentamos trabajar en abierto, tanto en nuestras comunicaciones de proyecto, como los avances de los mismos, aunque eso no significa que un proyecto esté abierto siempre a colaboraciones.

En los casos en los que sí esté abierto, es necesario especificar de qué manera cualquier persona podrá colaborar. Esto se especifica en el documento `CONTRIBUTING.md`. 

Algunos ejemplos de referencia:

* [Estándar de datos legislativos](https://github.com/CodeandoMexico/estandar-datos-legislativos/blob/master/CONTRIBUTING.md)
* [Decidim Monterrey](https://github.com/CodeandoMexico/decidim-monterrey/blob/main/CONTRIBUTING.md)


## [Archivo] Hacklog

```
❗️ Este archivo es OPCIONAL
ℹ️ Este archivo debe llamarse HACKLOG.md o BITACORA.md y residir en la carpeta raíz del proyecto
```

Como parte de nuestro objetivo de trabajar en abierto, es buena práctica ir documentando algunos de los milestones en el archivo hacklog.

A su vez, es buena práctica documentar las tareas o issues que se estén trabajando haciendo uso de la herramienta de issues de GitHub.

## [Carpeta] Documentación

```
‼️ Esta carpeta es OBLIGATORIA
ℹ️ Esta carpeta debe llamarse `documentos`
```

La documentación del proyecto debe vivir en el mismo repositorio que el código que documenta. Cualquier documento, ya sean archivos markdown, word, pdf o txt, deben estar bajo la carpeta `documentos`.

Es buena idea poner en esta carpeta:

* Documentación sobre cómo instalar el proyecto
* Guía de uso
* Legislación de referencia en caso de que sea relevante
* Etc


## [Carpeta] Recursos

```
‼️ Esta carpeta es OBLIGATORIA
ℹ️ Esta carpeta debe llamarse `recursos`
```

Todos los recursos gráficos (logos, banners, etc) o fotografías deben de ir en la carpeta de recursos.

--

Creado con ❤️ por la comunidad de [Codeando México](http://www.codeandomexico.org).
