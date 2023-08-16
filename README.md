# <img src="dist/header.svg" alt="TIRAYA" height="100"> META

Shared files for the Tiraya Music project. Currently these are mostly design files

- Color palette
- Icons
- Header images (for READMEs)

## Use the icons/header

The files in the `dist` folder are the converted/optimized graphics to be used by the
project.

Add the TIRAYA header to a readme:

```md
# <img src="https://raw.githubusercontent.com/TirayaMusic/meta/main/dist/header.svg" alt="TIRAYA" height="100"> PROJECT
```

## Development

The icons were created using [Inkscape](https://inkscape.org). Use the script
`npm run convert` to optimize the SVG files. It requires svgo (npm dependency) and
inkscape to be installed.
