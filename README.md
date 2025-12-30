# Navbar--footer-y-responsive-basico
Aprendiendo Navbar, footer y responsive básico
# Proyecto: Mundo Animal - Estructura y Responsive

## Objetivo
Desarrollar una página web sobre animales utilizando HTML semántico y CSS moderno para practicar el uso de Navbar, Footer y elementos superpuestos.

## Características Técnicas
**Flexbox:** Utilizado en el Navbar para alinear el logo y botones, y en el Footer para las columnas.
**Z-Index:** Aplicado en el banner de cookies para asegurar su visibilidad fija sobre el contenido.
**Responsive Design:** Implementación de Media Queries para adaptar la navegación y el pie de página de móvil a escritorio.
**Iconos:** Integración de Font Awesome para una interfaz visualmente atractiva.

## Estructura
1. Header con navegación adaptable.
2. Sección Hero informativa.
3. Banner de privacidad fijo.
4. Footer con múltiples columnas de información.


## Actualización: Implementación de Diseño Responsivo
En esta fase del proyecto, el sitio se transformó para ser totalmente adaptable a cualquier dispositivo, siguiendo los estándares modernos de desarrollo web:

Enfoque Mobile First: La hoja de estilos se reestructuró para priorizar dispositivos móviles, utilizando min-width en las media queries para añadir complejidad conforme aumenta el tamaño de la pantalla.

Unidades Relativas: Se migraron medidas absolutas a relativas para garantizar escalabilidad:

rem: Utilizado en tipografías y espaciados para respetar la configuración del navegador del usuario.

vh (Viewport Height): Aplicado en la sección Hero para que el contenido principal ocupe una proporción específica del alto de la pantalla visible.

vw (Viewport Width): Usado en títulos para que su tamaño se ajuste dinámicamente al ancho del dispositivo.

Breakpoints Definidos: Se estableció un punto de quiebre principal en 768px para gestionar la transición de un diseño vertical (móvil) a uno horizontal (escritorio) en el navbar y el footer.

Diseño Responsivo vs Adaptativo: El sitio utiliza un diseño responsivo fluido que se ajusta gradualmente, en lugar de saltos fijos de diseño adaptativo.