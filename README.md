# Explora Ciudades - RSS & Atom Feeds

Este proyecto contiene la implementación de feeds de sindicación **RSS 2.0** y **Atom 1.0** para el blog de viajes urbanos "Explora Ciudades". El objetivo es permitir que los usuarios se suscriban y reciban actualizaciones automáticas sobre guías y tips de viaje.

##  Descripción del Proyecto

El blog se enfoca en experiencias prácticas en grandes ciudades. Los archivos incluidos en este repositorio son:

* viajes.rss: Feed en formato RSS 2.0.
* viajes.atom: Feed en formato Atom 1.0 (estándar ISO 8601).

### Entradas Incluidas
1. **Barcelona**: Ruta gastronómica.
2. **París**: Mejores miradores.
3. **Nueva York**: Guía de transporte en 3 días.
4. **Tokio**: Museos culturales e históricos.



## Validaciones (W3C Feed Validator)

Ambos archivos han sido procesados a través del validador oficial del W3C para garantizar que cumplen con los estándares web.

### Validación RSS 2.0
![Validación RSS]()
> *Estado: Validado con éxito.*

### Validación Atom 1.0
![Validación Atom]()
> *Estado: Validado con éxito.*

---

## Cómo usar estos archivos
1. Sube los archivos **viajes.rss** y **viajes.atom** a la raíz de tu servidor web.
2. Añade los siguientes enlaces en el **<head>** de tu página principal:
   ```html
   <link rel="alternate" type="application/rss+xml" title="RSS Feed" href="/viajes.rss" />
   <link rel="alternate" type="application/atom+xml" title="Atom Feed" href="/viajes.atom" />