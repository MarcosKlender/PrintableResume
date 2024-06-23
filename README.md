<div align="center">
<img src="logo.png" height="90px" width="auto" /> 
<h2>
    <em>Résumé</em> minimalista maquetado para web y pdf
</h2>
<p>
Esquema del JSON de CV de <a href="https://jsonresume.org/schema/">jsonresume.org</a>
</p>

<p>
Basado en el diseño de <a href="https://github.com/BartoszJarocki/cv">Bartosz Jarocki</a>
</p>

</div>

<img src="portada.png"></img>

## 🛠️ Stack

- [**Astro**](https://astro.build/) - El framework web de la nueva época.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript con sintaxis de tipado.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Menu desplegable con atajos de teclado hecho en puro Javascript.

## 🚀 Empezar

### 1. Usa este [repo](https://github.com/midudev/minimalist-portfolio-json) como _template_ de un proyecto de Astro

- Yo uso [pnpm](https://pnpm.io/installation) como gestor de dependencias y empaquetador.

```bash
# Activa pnpm en MacOS, WSL & Linux:
corepack enable
corepack prepare pnpm@latest --activate

# Inicializa el proyecto
pnpm create astro@latest -- --template midudev/minimalist-portfolio-json
```

### 2. Añade tu contenido:

Edita el archivo `cv.json` para crear tu propio Portafolio/CV imprimible.

### 3. Lanza el servidor de desarrollo:

```bash
# Disfruta del resultado
pnpm dev
```

1. Abre [**http://localhost:4321**](http://localhost:4321/) en tu navegador para ver el resultado 🚀

## 🧞 Comandos

|     | Comando         | Acción                                                                       |
| :-- | :-------------- | :--------------------------------------------------------------------------- |
| ⚙️  | `dev` o `start` | Lanza un servidor de desarrollo local en `localhost:4321`.                   |
| ⚙️  | `build`         | Comprueba posibles errores y hace un empaquetado de producción en `./dist/`. |
| ⚙️  | `preview`       | Vista previa en local `localhost:4321`                                       |

## 🔑 Licencia

[MIT](LICENSE.txt) - Creado por [**midudev**](https://midu.dev).

## TODO

- [x] Añadir i18n
- [x] Añadir imagenes optimizadas
- [x] Arreglar hreflang
- [x] quitar trailing slash urls
- [x] Embeber estilos criticos
- [x] Añadir sitemap
- [x] Añadir astro-rename si se cambia a tailwind
- [ ] Selector de idioma
- [ ] Autodetectar idioma
- [ ] Añadir más skills
- [ ] Añadir soporte para modo oscuro
- [ ] Selector de temas
- [ ] Autodeteccion modo oscuro
- [ ] Actualizar README
- [ ] Comprobar rendimiento
- [ ] Estudiar embeber imagen
- [ ] Accesibilidad
- [ ] 404
- [ ] Añadir esLint, Prettier, Husky, Lint-staged, Commitlint
- [ ] Añadir enlace para descargar en pdf y enlace para acceder al json
- [ ] Añadir og image
- [ ] Actualizar scripts para parecerse a next.js
- [ ] Arreglar pagespeed problems
- [ ] Arreglar w3c problems
