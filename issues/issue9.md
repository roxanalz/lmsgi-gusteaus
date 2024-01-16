# Ejercicio 9 Reelaborado: Creación del "Menú Estrella" con Enfoque en Alérgenos usando HTML5 y CSS

## Descripción 

El objetivo es Desarrollar una página web para el "Menú Estrella" del restaurante Gusteau's, haciendo énfasis en la presentación de información sobre alérgenos utilizando atributos `data-` en HTML5 y estilos CSS.

## Esqueleto de página del menú HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú Estrella de Gusteau's</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
    <header>
        <h1>Menú Estrella del Restaurante Gusteau's</h1>
    </header>

    <nav>
        <!-- Menú de navegación aquí, si es necesario -->
    </nav>

    <main>
        <section class="menu-estrella">
            <h2>Platos Principales</h2>
            <ul>
                <li data-alergenos="nueces mariscos">Ensalada Mediterránea con Nueces y Gambas</li>
                <li data-alergenos="nueces">Tarta de Chocolate y Nueces</li>
                <li data-alergenos="mariscos">Paella de Mariscos</li>
                <li>Sopa de Verduras</li>
                <!-- Más platos aquí -->
            </ul>

            <h2>Entrantes</h2>
            <ul>
                <!-- Ítems de entrantes aquí -->
            </ul>

            <h2>Postres</h2>
            <ul>
                <!-- Ítems de postres aquí -->
            </ul>
        </section>
    </main>

    <footer>
        <!-- Información del pie de página aquí -->
    </footer>
</body>
</html>
```

## Uso del atributo `data-` en HTML5

- El atributo `data-` en HTML5 se utiliza para almacenar información adicional sobre un elemento, que no está directamente relacionada con la representación o el comportamiento estándar del elemento.
- Es importante porque permite a los desarrolladores web agregar datos personalizados a sus elementos HTML de una manera que es accesible a través de CSS y JavaScript, sin alterar la semántica del documento.
- En este ejercicio, usamos `data-alergenos` para identificar los alérgenos presentes en cada plato, lo que permite una gran flexibilidad para estilizar y manipular estos elementos según sea necesario.

## Tareas

### Estilización del menú

- [ ] Aplicar estilos CSS para crear un diseño visualmente atractivo y coherente con el tema del restaurante.
- [ ] Incluir estilos para encabezados, listas de platos y elementos individuales del menú.

### Manejo de Alérgenos

- [ ] Utilizar los atributos data-alergenos para identificar platos con alérgenos específicos y aplicar estilos distintivos a estos elementos.
- [ ] Para platos con múltiples alérgenos, asegurarse de que el estilo aplicado sea claro y diferenciable.

### Interactividad y detalles de Alergenos

- [ ] Implementar efectos :hover para resaltar los platos al pasar el mouse
- [ ] Usar selectores avanzados en CSS para aplicar estilos basados en los valores de `data-alergenos`.


