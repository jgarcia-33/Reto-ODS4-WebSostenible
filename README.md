# Reto-ODS4-WebSostenible

# Proyecto Web: [Nombre de vuestra App Web] - ODS 4

Este proyecto es una propuesta tecnológica para mejorar la calidad educativa (ODS 4) desde la
perspectiva del Desarrollo de Aplicaciones Web (DAW).

## 1. Análisis del Problema y Sostenibilidad (Responsable: Alumno A)

### El "Bug" Educativo

> [Explica aquí el problema real usando este bloque de cita. Ejemplo: falta de plataformas
> > accesibles, consumo excesivo de papel...]

### Nuestro "Parche" Sostenible

- [ ] Medida 1: [Ej: Imágenes optimizadas]
- [ ] Medida 2: [Ej: Accesibilidad para lectores de pantalla]

## 2. Arquitectura de la Solución Web (Responsable: Javier Castro López)

### Funcionalidades Principales

1. **Buscador de Comandos:** [Es un buscador simple al que tu le describes el comando y el te devuelve comandos que cumplan con la descripción enviada]
2. **Clasificación por Módulos:** [Cada comando tiene sus etiquetas relacionadas con su lenguaje y su función, permitiéndole a los usuarios filtrar por etiquetas]
3. **Botón de Copiado Rápido:** [Cada comando tiene a su derecha un icono el cual, al hacerle click, te copia el comando en el portapapeles]

### Entidades de Datos Básicas

| Entidad  | Descripción                               | Ejemplo de datos                |
| :------- | :---------------------------------------- | :------------------------------ |
| Usuarios | Almacena profesores y alumnos             | Email, contraseña, rol          |
| Comandos | Almacena los comandos que registra la web | git add, docker ps, npm run dev |

### Prototipo de Interfaz (Frontend)

A continuación se muestra el wireframe de nuestra aplicación:
![Prototipo de la Interfaz Web](Filtros.png)
**Breve explicación:** En la captura podemos ver 2 barras, una de busqueda por texto, y otra por filtros. A su vez, vemos los comandos mas utilizados. Al pinchar en ellos, nos saldrá su descripcion, y al clickear el icono de su derecha, se nos copiara el comando en el portapapeles
