<div align="center">
<h2>
    CV minimalista maquetado para web y pdf
</h2>
<p>
Esquema del JSON de CV de <a href="https://jsonresume.org/schema/">jsonresume.org</a>
</p>

<p>
Basado en el diseño de <a href="https://github.com/BartoszJarocki/cv">Bartosz Jarocki</a> y del repositorio de <a href="https://github.com/midudev/minimalist-portfolio-json">MiduDev</a>
<p>La diferencia con el repo de Midu es que se utilizó Tailwind CSS como framework para los estilos</p>
</p>
</div>

## 🛠️ Stack

- [**Astro**](https://astro.build/) - Marco web para sitios web basados ​​en contenido.
- [**Typescript**](https://www.typescriptlang.org/) - Lenguaje de programación fuertemente tipado que se basa en JavaScript.
- [**TailwindCss**](https://tailwindcss.com/) - Framework de css.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Menu desplegable con atajos de teclado hecho en puro Javascript.

## Como usar esta plantilla

### 1. Cloná e instalá las dependencias

```bash
# Inicializa el proyecto
git clone https://github.com/alexsh882/portfolio-with-astro-tailwind.git

# Ingresá a la carpeta del proyecto
cd portfolio-with-astro-tailwind

#Luego para instalar las dependencias ejecuta
pnpm i

# o si usas npm
npm i
```

### 2. Añade tu contenido:
- Edita el archivo `cv-es.json` para generar tu propio Portafolio/CV imprimible.
- Subí tu imagen de perfil a la carpeta `/public` y renombralo a `me.png`

### 3. Lanza el servidor de desarrollo:

```bash
# Disfruta del resultado
pnpm run dev

# o si usas npm
npm run dev
```


1. Abre [**http://localhost:4321**](http://localhost:4321/) en tu navegador para ver el resultado 🚀

## 🧞 Comandos

|     | Comando          | Acción                                        |
| :-- | :--------------- | :-------------------------------------------- |
| ⚙️  | `dev` o `start` | Lanza un servidor de desarrollo local en  `localhost:4321`.  |
| ⚙️  | `build`          | Comprueba posibles errores y hace un empaquetado de producción en `./dist/`.      |
| ⚙️  | `preview`        | Vista previa en local `localhost:4321` |