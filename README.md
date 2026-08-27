# Hoja de Vida Profesional en HTML5 Nativo

## Información del Estudiante

- **Nombre Completo:** Joaquin Francisco Villalpando Apaza
- **Carrera:** Ingeniería de Sistemas
- **Semestre:** Cuarto Semestre
- **Asignatura:** Tecnologías Web I (SIS-214)
- **Institución:** Universidad Católica Boliviana "San Pablo"

## Descripción del Proyecto

Este proyecto consiste en el diseño y desarrollo de una Hoja de Vida técnica y profesional estructurada bajo estándares rigurosos de HTML5 nativo, aplicando la filosofía de desarrollo sin dependencias ("Zero Frameworks").

El diseño se enfoca en la semántica estructural, la accesibilidad de cara al usuario (A11y) y la optimización de la entrega de recursos nativos desde el navegador.

## Estructura del Directorio

El proyecto se organiza bajo la siguiente arquitectura de archivos:

```
hoja-vida/
├── index.html
├── assets/
│   ├── images/
│   │   ├── perfil-fallback.jpg
│   │   ├── perfil-small.webp
│   │   ├── perfil-large.webp
│   │   └── video-poster.jpg
│   └── documents/
│       ├── presentacion.mp3
│       ├── presentacion.ogg
│       ├── proyecto-demo.mp4
│       ├── proyecto-demo.webm
│       ├── subtitulos_es.vtt
│       ├── hoja-de-vida-completa.pdf
│       └── portafolio-comprimido.zip
└── README.md
```

## Requisitos Técnicos Implementados

- **Semántica Estructural de Bloque:** Organización jerárquica libre de capas genéricas `div`, utilizando de manera exclusiva contenedores semánticos (`header`, `nav`, `main`, `section`, `article`, `aside` y `footer`).
- **Semántica Inline de Precisión:** Uso sistemático de etiquetas semánticas de texto (`abbr`, `time`, `mark`, `dfn`, `em` y listas de definiciones `dl`, `dt`, `dd`).
- **Componentes Interactivos Nativos (Zero JS):** Implementación de acordeones plegables mediante `details` y `summary`, junto con cuadros de diálogo nativos con `dialog`.
- **Visualización de Datos y Tablas:** Uso de tablas accesibles con marcado completo (`caption`, `thead`, `tbody`, `th`, `td`) y barras de visualización cuantitativa nativas (`progress` y `meter`).
- **Multimedia Adaptativa:** Incorporación de elementos multimedia adaptativos (`picture` con múltiples fuentes `source` y carga diferida) y reproductores de audio y video accesibles mediante el uso de pistas de subtítulos (`track`).
- **Formularios con Validación de Hardware:** Estructura con agrupaciones lógicas (`fieldset` y `legend`) y controles avanzados HTML5 (`type="tel"`, `type="email"`, `type="date"`, `type="range"`, `datalist`) validados nativamente en el navegador mediante restricciones de caracteres, obligatoriedad y expresiones regulares (`pattern`).

## Instrucciones de Despliegue

Para visualizar el proyecto localmente:

1. Asegúrese de mantener la estructura de directorios descrita anteriormente.
2. Inicie un servidor local (por ejemplo, utilizando la extensión Live Server en Visual Studio Code) o abra directamente el archivo `index.html` en cualquier navegador web moderno que soporte el estándar HTML5.