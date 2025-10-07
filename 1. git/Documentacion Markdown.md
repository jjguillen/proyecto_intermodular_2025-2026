# Documentación Markdown

- [Documentación de Código](#documentación-de-código)
  - [Markdown](#markdown)
    - [Sintaxis Básica de Markdown](#sintaxis-básica-de-markdown)
    - [Ejemplo de Documento Markdown Completo](#ejemplo-de-documento-markdown-completo)

# Documentación de Código

La **documentación del código** es una parte fundamental y a menudo subestimada del desarrollo de software. Es esencial para el mantenimiento futuro de cualquier proyecto, ya que permite a otros desarrolladores (e incluso a tu yo futuro) entender, utilizar y modificar el código sin necesidad de una inmersión profunda en su implementación interna. Una buena documentación reduce la curva de aprendizaje, facilita la colaboración y mejora la calidad general del software.

## Markdown

**Markdown** es un **lenguaje de marcado ligero** diseñado por John Gruber y Aaron Swartz en 2004. Su principal objetivo es lograr la máxima legibilidad y facilidad de escritura tanto en su forma de entrada como de salida. Permite dar formato a texto plano utilizando una sintaxis sencilla e intuitiva. Es el formato por defecto en plataformas como GitHub para archivos `README.md`, wikis y comentarios, y es ampliamente utilizado en documentación técnica, notas, blogs y contenido web debido a su simplicidad y portabilidad.

**Ventajas de usar Markdown:**

- **Facilidad de Lectura y Escritura**: Su sintaxis es muy natural y se asemeja a cómo formatearías texto en un correo electrónico.
- **Versatilidad**: Se puede usar para crear una amplia variedad de documentos, desde notas personales hasta libros y documentación de API.
- **Portabilidad**: Los archivos Markdown son texto plano, lo que significa que pueden ser abiertos y editados con cualquier editor de texto y no dependen de plataformas específicas.
- **Estabilidad a Largo Plazo**: Su formato sencillo asegura que los documentos creados con Markdown serán legibles en el futuro, independientemente de la evolución del software.
- **Popularidad y Soporte**: Es un estándar bien establecido en la comunidad tecnológica y cuenta con soporte en numerosos gestores de contenido, foros y aplicaciones sociales.

### Sintaxis Básica de Markdown

La sintaxis de Markdown es intuitiva. Aquí se muestran los elementos más comunes:

- **Encabezados**: Se utilizan de una a seis almohadillas (`#`) al principio de una línea. Un `#` es un título principal, `##` es un subtítulo, y así sucesivamente.

  ```markdown
  # Título Principal (H1)

  ## Sección Importante (H2)

  ### Subsección (H3)

  #### Punto Clave (H4)

  ##### Detalle (H5)

  ###### Sub-detalle (H6)
  ```

- **Texto Básico (Negrita, Cursiva, Combinado)**:

  - Para **negrita**, encierra el texto entre dos asteriscos o guiones bajos: `**texto en negrita**` o `__texto en negrita__`.
  - Para _cursiva_, encierra el texto entre un solo asterisco o guion bajo: `*texto en cursiva*` o `_texto en cursiva_`.
  - Para **_negrita y cursiva_**, usa tres asteriscos: `***texto en negrita y cursiva***`.

- **Listas Numeradas**: Empieza cada elemento con un número seguido de un punto y un espacio. Markdown se encarga de la numeración correcta.

  ```markdown
  1. Primer elemento de la lista
  2. Segundo elemento
     1. Sub-elemento A
     2. Sub-elemento B
  3. Tercer elemento
  ```

- **Listas con Viñetas**: Empieza cada elemento con un guion (`-`), un asterisco (`*`) o un signo más (`+`) seguido de un espacio.

  ```markdown
  - Elemento con viñeta

  * Otro elemento con viñeta
    - Sub-elemento con viñeta
  ```

- **Enlaces**: La sintaxis para un enlace en línea consta del texto del enlace entre corchetes `[ ]` seguido de la URL entre paréntesis `( )`. Puedes añadir un título opcional entre comillas después de la URL.

  ```markdown
  [Visita Google](https://www.google.com "Buscador líder")
  ```

- **Imágenes**: Similar a los enlaces, pero precedido por un signo de exclamación `!`. El texto alternativo (que se muestra si la imagen no carga) va entre corchetes, y la URL de la imagen entre paréntesis.

  ```markdown
  ![Logo de Ejemplo](/assets/logo.png "Logo del Proyecto")
  ```

- **Bloques de Código**:

  - Para `código en línea`, encierra el texto entre comillas invertidas (backticks): `` `código en línea` ``.
  - Para `bloques de código` multilínea (delimitados), usa tres comillas invertidas (```) antes y después del bloque. Puedes especificar el lenguaje para el resaltado de sintaxis después de las primeras tres comillas.

    ````markdown
    ```java
    public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hola, Mundo!");
    }
    }
    ```
    ````

    ```

    ```

- **Tablas**: Las tablas no forman parte de la especificación original de Markdown, pero GitHub Flavored Markdown (GFM) y otras variantes las soportan ampliamente. Se construyen usando barras verticales (`|`) para las columnas y guiones (`-`) para el encabezado.

  ```markdown
  | Encabezado 1 | Encabezado 2 | Encabezado 3 |
  | ------------ | :----------: | -----------: |
  | Fila 1 Col 1 | Fila 1 Col 2 | Fila 1 Col 3 |
  | Fila 2 Col 1 | Fila 2 Col 2 | Fila 2 Col 3 |
  | Fila 3 Col 1 | Fila 3 Col 2 | Fila 3 Col 3 |
  ```

  _Alineación_: Los dos puntos en la línea de guiones controlan la alineación del texto:

  - `:---` o `---` = Izquierda
  - `:---:` = Centro
  - `---:` = Derecha

### Iconos

[Link](https://gist.github.com/rxaviers/7360908)

#### Ejemplo de Documento Markdown Completo

A continuación, un ejemplo de cómo se vería un documento `README.md` estructurado utilizando Markdown:

````markdown
# Mi Proyecto Fabuloso

¡Bienvenido a Mi Proyecto Fabuloso! Este es un proyecto de ejemplo que demuestra cómo usar Markdown para la documentación.

## 🚀 Inicio Rápido

Sigue estos pasos para poner en marcha el proyecto en tu entorno local.

### Prerequisitos

Asegúrate de tener instalado lo siguiente:

- Node.js (versión 14 o superior)
- npm (normalmente viene con Node.js)
- Git

### Instalación

1.  **Clona el repositorio:**

    ```bash
    git clone https://github.com/tu-usuario/mi-proyecto-fabuloso.git
    cd mi-proyecto-fabuloso
    ```

2.  **Instala las dependencias:**

    ```bash
    npm install
    ```

3.  **Ejecuta el proyecto:**
    ```bash
    npm start
    ```
    El proyecto debería estar ahora ejecutándose en `http://localhost:3000`.

## 📚 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- `src/`: Contiene el código fuente principal.
  - `components/`: Componentes UI reutilizables.
  - `pages/`: Vistas de la aplicación.
  - `App.js`: Componente principal de la aplicación.
  - `index.js`: Punto de entrada de la aplicación.
- `public/`: Archivos estáticos como `index.html` y `favicon.ico`.
- `README.md`: Este mismo archivo de documentación.

## 🛠️ Comandos Útiles

Aquí hay una tabla de comandos que te pueden ser útiles durante el desarrollo:

| Comando            | Descripción                                      |
| ------------------ | :----------------------------------------------- |
| `npm start`        | Inicia el servidor de desarrollo local.          |
| `npm test`         | Ejecuta los tests unitarios.                     |
| `npm run build`    | Compila la aplicación para producción.           |
| `npm run deploy`   | Despliega la aplicación a un entorno de staging. |
| `git status`       | Muestra el estado del repositorio.               |
| `git commit -m ""` | Guarda los cambios en el historial.              |

## 🤝 Contribución

¡Las contribuciones son bienvenidas! Si deseas contribuir, sigue estos pasos:

1.  Haz un `fork` de este repositorio.
2.  Crea una nueva rama para tu característica:
    ```bash
    git checkout -b feature/nombre-de-la-caracteristica
    ```
3.  Realiza tus cambios y `commitea` con un mensaje descriptivo.
4.  Sube tu rama:
    ```bash
    git push origin feature/nombre-de-la-caracteristica
    ```
5.  Abre un `Pull Request` explicando tus cambios.

### Pautas para Commits

Por favor, sigue estas pautas para los mensajes de commit:

- Comienza con un verbo imperativo (ej., "Añadir", "Corregir", "Actualizar").
- Mantén la primera línea corta (menos de 50 caracteres).
- Proporciona un cuerpo más detallado si es necesario, explicando el "por qué" y "cómo".

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## 📞 Contacto

Para cualquier pregunta o comentario, puedes contactar a [Tu Nombre](mailto:tu.email@ejemplo.com).
````
