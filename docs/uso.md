# Uso de MkDocs

MkDocs convierte archivos Markdown en un sitio web estático de documentación.

## Ejecutar servidor local

Para probar el sitio en la computadora se usa:

```bash
mkdocs serve
```

Luego se abre en el navegador:

```text
http://127.0.0.1:8000
```

## Generar el sitio estático

Para generar la versión final del sitio:

```bash
mkdocs build
```

Esto crea una carpeta llamada `site/`.

## Bloque de código con pestañas

=== "Python"

    ```python
    print("Hola desde Python")
    ```

=== "JavaScript"

    ```javascript
    console.log("Hola desde JavaScript")
    ```

## Bloque desplegable

??? info "Más información"
    Este contenido se puede expandir o contraer haciendo clic.