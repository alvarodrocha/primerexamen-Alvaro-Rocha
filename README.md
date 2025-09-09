# primerexamen-Alvaro-Rocha
Ing.Alvaro Daniel Rocha Rocha, Estudiante del Curso Complementario de la carrera de Ing.Sistemas
en la Universidad UAB
Proyecto de Desarrollo Web responsive para la empresa MANACO

# Accesibilidad (a11y)
1.uso del Skip Link
Permite a los usuarios de teclado y lectores de pantalla saltar la navegación e ir directo al contenido principal:

2.Foco visible
Todos los enlaces y botones muestran un contorno plomo visible
cuando son seleccionados con el teclado (`Tab`):

3.Texto alternativo (`alt`) en imágenes

Cada producto tiene un `alt` descriptivo, en lugar de un texto genérico:

4.Navegación accesible

`nav` incluye `aria-label="Navegación principal"` para dar contexto  a los usuarios de lector de pantalla.
La navegación es completamente usable con teclado (`Tab`, `Enter`).

5.Buenas prácticas

Se evitó el uso excesivo de `<div>` → se usaron etiquetas semánticas.
`id="contenido"` asegura que el skip link funcione correctamente.
Uso prudente de atributos `aria-*` (solo donde aporta valor).