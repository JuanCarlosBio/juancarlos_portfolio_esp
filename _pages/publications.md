---
layout: archive
title: "🚀 <u>Proyectos Personales</u>"
permalink: /proyectos/
author_profile: true
---

{% include base_path %}

Debido a mi gran interés por la informática, he desarrollado proyectos personales enfocados en el análisis de datos, con un especial interés en datos de origen biológico. Este enfoque me ha permitido adquirir habilidades prácticas en la gestión y procesamiento de información compleja.

Comparto mis proyectos, tanto los más destacados como aquellos en los que aún estoy aprendiendo, en mi repositorio de GitHub, lo que me permite documentar y reflejar mi evolución técnica y aprendizaje continuo.

--- 

Proyectos 2024
===

## <u>Estancia en el Cabildo de Gran Canaria (Medio Ambiente)</u> 🥾 

<div style="float: right; margin-left: 20px;">
  <img src="../images/GC_mapa.png" width="250px">
</div>

### Web de Especies de la isla de Gran Canaria observadas 🐜 🌱

<strong>Descripción</strong>: Esta web fue creada para la observación de especies localizadas <i>in situ</i> mediante la toma de muestras georreferenciadas a través de fotografías con el móvil 📱📷🌍. La plataforma consta de varias páginas donde se pueden observar las especies en visores, tablas interactivas y estadísticas.

Actualmente, estoy enfocándome en la búsqueda de <u>animales invertebrados y plantas</u>, aunque no descarto incluir otros organismos en el futuro.

[Repositorio de GitHub BiodiversidadGJC](https://github.com/JuanCarlosBio/BiodiversidadGJC) | [🌐 Sitio WEB](https://juancarlosbio.github.io/BiodiversidadGJC/)

### Web de senderos obtenidos por la aplicación IGN 🗺️

**Descripción**: En esta web comparto senderos obtenidos en formato KML a partir de archivos GPX generados con la aplicación del IGN.

He desarrollado el flujo de trabajo, pero estoy buscando mejorar el sitio web para optimizar la experiencia del usuario.

[Repositorio Salidas_de_Campo_CabildoGC](https://github.com/JuanCarlosBio/Salidas_de_Campo_CabildoGC/) | [🌐 Sitio WEB](https://juancarlosbio.github.io/Salidas_de_Campo_CabildoGC/)

### Cuadrículas 100 x 100 Para búsqueda de especies Python 🌷🐜🔍

<div style="float: right; margin-left: 20px;">
  <img src="https://github.com/JuanCarlosBio/Cuadriculas_Especies/blob/main/images/exampe_portfolio/Captura%20de%20pantalla%202024-10-03%20165837.png?raw=true" width="200px">
</div>

**Descripción:** Flujo de Trabajo para crear cuadrículas 100 x 100 (m<sup>2</sup>) en los Espacios Naturales Protegidos, mediante el uso de Python. La idea es tener cuadrículas para cargar en IGN y guiarse mejor en estos espacios y anotar especies.

Con estas capas luego se pueden análisis espaciales de especies identificadas (u otras observaciones) como la web que he desarrollado para la localización de especies nativas en la caldera de Bandama.

[Repositorio Cuadriculas_Especies](https://github.com/JuanCarlosBio/Cuadriculas_Especies) | [🌐 Sitio WEB](https://juancarlosbio.github.io/Cuadriculas_Especies/)
 

## <u>Otros proyectos personales este año</u> 

### Estudio de sequía en Canarias (estaciones NOAA) ☀️ ☁️ ☔

**Descripción**: Este proyecto se inspira en un tutorial de YouTube llamado [Riffomonas Project](https://www.youtube.com/@Riffomonas/featured) , creado por [Pathick Schloss](https://medschool.umich.edu/profile/2341/patrick-d-schloss), profesor en la University of Michigan Medical School. 

Este fue mi <u>primer proyecto de desarrollo web</u>.

<u>El objetivo final es crear un GIF que muestre la evolución de la sequía del año 2024 en comparación con los últimos 30 años de datos de las estaciones NOAA</u>.

Desgraciadamente ocurre una catástrofe en Asheville el día 28 de septiembre de 2024 debido al Huracán Helene, que asola la ciudad. Por ello los servidores de NOAA NCEI han caído: [noticia](https://www.noaa.gov/news/noaa-ncei-websites-systems-down-due-to-helene-devastation-in-asheville-nc).  

<p align="center">
<img src="https://github.com/JuanCarlosBio/tiempo_canarias_noaa/blob/main/figures/precipitaciones_canarias.png?raw=true" width="700px">
</p>

[Repositorio de GitHub tiempo_canarias_noaa](https://github.com/JuanCarlosBio/tiempo_canarias_noaa/) | [🌐 sitio WEB](https://juancarlosbio.github.io/tiempo_canarias_noaa/)

### Análisis de Base de Datos de Tortugas Marinas usando Julia. 

<div style="float: right; margin-left: 20px;">
  <img src="https://www.freecodecamp.org/news/content/images/size/w2000/2023/01/Ifihan-article-cover.png" width="200px">
</div>

**Descripción**: En mi último año de carrera, realicé mi Trabajo de Fin de Grado en Biología, que consistió en el análisis de una base de datos de <u>tortugas marinas varadas en Tenerife</u>, proporcionada por el Centro de Recuperación de Fauna Silvestre La Tahonilla, utilizando el <u>lenguaje de programación R</u>. Este proyecto tiene como objetivo replicar y expandir ese análisis estadístico, pero empleando el [lenguaje de programación Julia](https://julialang.org/).

Además, me introduje en el uso de frameworks para desarrollo WEB mediante el paquete [Franklin.jl](https://franklinjl.org/).

<u>Actualmente, este proyecto se encuentra en desarrollo</u>.

[Repositorio de GitHub para el análisis con Julia de Tortugas marinas](https://github.com/JuanCarlosBio/turtles_julia_analysis) | [🌐 Sitio WEB](https://juancarlosbio.github.io/turtles_julia_analysis/)


--- 

Proyectos 2023
===

## <u>Trabajo de Fin de Máster en Bioinformática (VIU)</u>🧬 👨‍💻 📈

<div style="float: right; margin-left: 20px;">
  <img src="https://snakemake.readthedocs.io/en/stable/_static/logo-snake.svg" width="150px">
</div>

**Descripción**: Este proyecto consistió en desarrollar un flujo de trabajo para el análisis <u>bioinformático de Next Generation Sequencing</u> utilizando el software [SNAKEMAKE](https://snakemake.github.io/), un gestor de flujos de trabajo basado en GNUmake. Snakemake es ideal para automatizar y hacer reproducibles los procesos bioinformáticos, destacando por su sintaxis en Python, lo que facilita su aprendizaje y comprensión.  

* **Repositorio de GitHub**: [Desarrollo de un pipeline automatizado y reproducible para análisis WES mediante el uso de SNAKEMAKE](https://github.com/JuanCarlosBio/TFM) 

## <u>Otras asignaturas del máster (2023)</u> 🧬 👨‍💻 📈

### Actividades de Secuenciación Genómica (VIU)

<div style="float: right; margin-left: 20px;">
  <img src="https://www.pssi.com/wp-content/uploads/2022/01/GenomeSequencing-Pic1.png
" width="170px">
</div>

**Descripción**: Código empleado para resolver los problemas de la asignatura Secuenciación Genómica.

* [Repositorio de las actividades de Secuenciación Genómica](https://github.com/JuanCarlosBio/Secuenciacion_Genomica_VIU)

### Actividades de Trasncriptómica (VIU)

<div style="float: right; margin-left: 20px;">
  <img src="https://microbenotes.com/wp-content/uploads/2022/07/RNA-Sequencing.jpg" width="170px">
</div>

**Descripción**: Código empleado para resolver los problemas de la asignatura Trascriptómica (RNA-SEQ).

* [Repositorio de las actividades de Transcriptómica](https://github.com/JuanCarlosBio/RNA-Seq_VIU)

### Actividades de Datos Ómicos para Poblaciones (VIU)

<div style="float: right; margin-left: 20px;">
  <img src="https://innovativegenomics.org/wp-content/uploads/2021/10/Metagenomics-101-1-1024x615.png" width="170px">
</div>

**Descripción**: Código empleado para resolver los problemas de la asignatura Datos Ómicos para Poblaciones, en concreto las ómicas que estudiamos fueron la Metagenómica y Metataxonómica. 

* [Repositorio de las actividades de Datos Ómicos para Poblaciones](https://github.com/JuanCarlosBio/Analisis_Datos_Omicos_Poblaciones)

--- 

Proyectos 2022
===

## <u>Otras asignaturas del máster (2022)</u> 🧬 👨‍💻 📈

### Actividades de Programación en Python y R (VIU)

<div style="float: right; margin-left: 20px;">
  <img src="https://media.licdn.com/dms/image/v2/D4D12AQEz33xZKsngrw/article-cover_image-shrink_423_752/article-cover_image-shrink_423_752/0/1685213382501?e=1732752000&v=beta&t=oM6a_TEeZpZq4-IHTMnL3N0zZ2uCXgwsLqWHrVRtjjY" width="150px">
</div>

**Descripción**: Código empleado para resolver los problemas de la asignatura Programación en los Lenguaje de Programación [Python](https://www.python.org/) y [R](https://www.r-project.org/).

* [Repositorio de las actividades de Programación en Python y R](https://github.com/JuanCarlosBio/Programacion_Python_R)

### Actividades de Programación en Shell Scripting / BASH (VIU)

<div style="float: right; margin-left: 20px;">
  <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*f7uGDZbiOloyZSM8C5bNMQ.png" width="150px">
</div>

**Descripción**: Código empleado para resolver los problemas de la asignatura Programación en Shell Scripting, en concreto aprendimos a usar el interprete <u>BASH SHELL</u>.

Cabe destacar que me especialicé además en el *Sistema Operativo <u>Linux</u>*, lo que me ha ayudado a mejorar en proyectos de análisis de datos.

* [Repositorio de las actividades de Programación en Shell Scripting](https://github.com/JuanCarlosBio/Programacion_Shell_Scripting_VIU)

## <u>Trabajo de Fin de Grado en Biología</u> 

<div style="float: right; margin-left: 20px;">
  <img src="../images/tahonilla_tortugas.jpg" width="250px">
    <figcaption style="font-size: 12px;" align="center">Visita para ver las tortugas en La Tahonilla.</figcaption>
</div>

**Descripción**: Tras aprender programación en R de forma autodidacta, puse a prueba mis habilidades analizando una base de datos de tortugas marinas varadas, proporcionada por el Centro de Recuperación de Fauna Silvestre La Tahonilla del Cabildo de Tenerife.

Este proyecto me permitió demostrar competencias en programación, análisis estadístico, visualización de datos y más.

Además, aprendí de forma autodidacta a utilizar <u>Git y GitHub</u> para el control de versiones, almacenando mi código y compartiéndolo con mi tutor y el tribunal.

<p align="center">
<img src="../images/tahonilla.jpg" width="400px">
</p>

* **Repositorio de GitHub**: [Análsis estadístico de tortugas marinas varadas en Tenerife, Islas Canarias](https://github.com/JuanCarlosBio/Tortugas_La_Tahonilla) 

--- 

Proyectos de 2021
===

### Asignaturas de Cuarto de Carrera🥼 🔬 🧫 🧪 🐁 🥾 🐜 🌺 🌱 🍄

Aprendí programación de forma autodidacta para analizar los datos de mis últimas asignaturas de cuarto de carrera. <u>Comencé con el lenguaje de programación R</u>, y conservo el código utilizado para los análisis. Además, lo he empleado para experimentar y aplicar nuevos conocimientos, realizando modificaciones y explorando diferentes enfoques.

* <u>Asignaturas optativas para la especialidad:</u> 
  * 🐁 Fisiología Animal Aplicada
  * 🌱 Aplicaciones de la Fisiología Vegetal
  * 🧫 Microbiología Aplicada
  * 🧪 Avances en Bioquímica y Biología Molecular 
  * 🧬 Genética Evolutiva.

* **Repositorio de GitHub**: [Análisis de datos de las asignaturas de Cuarto de Carrera de Biología](https://github.com/JuanCarlosBio/cuarto_carrera)
