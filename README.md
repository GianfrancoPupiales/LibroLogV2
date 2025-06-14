# LibroLog

LibroLog es una aplicación web desarrollada con **React** y **TypeScript** que utiliza **Material-UI (MUI)** para la gestión de temas y estilos. Este proyecto está diseñado para ofrecer una experiencia de usuario moderna y responsiva.

## Características

- **React y TypeScript**: Aprovecha las ventajas de un tipado estático y componentes reutilizables.
- **Material-UI (MUI)**: Implementación de un diseño consistente y profesional con soporte para temas personalizados.
- **Estilos CSS**: Uso de estilos personalizados para complementar el diseño de MUI.
- **Soporte para temas claros y oscuros**: Cambia automáticamente según las preferencias del sistema operativo.
- **Configuración modular**: Código organizado y fácil de mantener.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```angular2html
    libroLog/
    ├── public/               # Archivos estáticos
    ├── src/                  # Código fuente principal
    │   ├── App.css           # Estilos específicos de la aplicación
    │   ├── App.tsx           # Componente principal de la aplicación
    │   ├── index.css         # Estilos globales
    │   ├── main.tsx          # Punto de entrada de la aplicación
    │   └── components/       # Componentes reutilizables
    ├── package.json          # Configuración de dependencias y scripts
    └── README.md             # Documentación del proyecto
```


## Requisitos Previos

Antes de ejecutar el proyecto, asegúrese de tener instalado lo siguiente:

- **Node.js** (versión 18.x o superior)
- **npm** (incluido con Node.js)

## Instalación

Siga los pasos a continuación para configurar el proyecto en su entorno local:

1. Clone el repositorio:

   git clone https://github.com/GianfrancoPupiales/LibroLogV2.git

   cd libroLog


2. Instale las dependencias:

   npm install


3. Inicie el servidor de desarrollo:

   npm run dev


4. Abra su navegador la URL para ver la aplicación en funcionamiento.

## Scripts Disponibles

En el archivo `package.json` se encuentran los siguientes scripts:

- `npm run dev`: Inicia el servidor de desarrollo.
- `npm run build`: Genera una versión optimizada para producción.
- `npm test`: Ejecuta las pruebas configuradas (si están definidas).
- `npm run lint`: Analiza el código en busca de errores de estilo o sintaxis.

## Personalización del Tema

El proyecto utiliza **Material-UI (MUI)** para la gestión de temas. El tema predeterminado se define en el archivo `src/main.tsx` y puede personalizarse modificando las propiedades de la función `createTheme`.

Ejemplo de personalización:
typescript
const theme = createTheme({
palette: {
primary: { main: '#1976d2' },
secondary: { main: '#dc004e' },
},
})


## Estilos CSS

El proyecto incluye estilos personalizados en los archivos `index.css` y `App.css`. Estos estilos complementan el diseño de MUI y permiten una mayor personalización visual.

## Contribución

Si desea contribuir al proyecto, siga estos pasos:

1. Haga un fork del repositorio.
2. Cree una nueva rama para su funcionalidad o corrección de errores:
   bash
   git checkout -b feature/nueva-funcionalidad

3. Realice sus cambios y haga un commit:
   bash
   git commit -m "Descripción de los cambios"

4. Envíe un pull request al repositorio principal.

## Licencia

Este proyecto está bajo la licencia [MIT](https://opensource.org/licenses/MIT). Consulte el archivo `LICENSE` para más detalles.

## Autor

Este proyecto fue desarrollado por Gianfranco Pupiales y Jeremy Yugsi.