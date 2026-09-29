# Instrucciones para el agente web

Este repositorio es una biblioteca privada de templates web reutilizables.

## Objetivo

Cuando un cliente solicite un sitio web, el agente debe analizar sus necesidades, revisar los templates disponibles en esta biblioteca y seleccionar el más adecuado.

El agente debe crear una copia del template seleccionado en un repositorio nuevo del cliente. Nunca debe modificar el template maestro de esta biblioteca.

## Flujo obligatorio

1. Recibir y analizar el brief del cliente.
2. Identificar el tipo de sitio:
   - Landing page
   - Sitio corporativo
   - Portafolio
   - Blog
   - Restaurante
   - Tienda online
   - Sistema de reservas
   - Aplicación web
3. Leer todos los archivos `TEMPLATE-METADATA.md` disponibles.
4. Comparar las necesidades del cliente con:
   - Uso recomendado
   - No usar para
   - Características visuales
   - Funciones requeridas
5. Seleccionar el template que cubra mejor los requisitos esenciales.
6. Si ningún template cubre los requisitos, detenerse y responder:
   `No hay un template compatible en la biblioteca. Se requiere añadir un template nuevo o desarrollar una solución a medida.`
7. Explicar brevemente por qué eligió ese template.
8. Crear un repositorio nuevo para el cliente.
9. Copiar allí el template seleccionado.
10. Personalizar exclusivamente la copia del cliente.
11. Crear una vista previa para revisión.
12. Esperar aprobación humana antes de publicar o entregar al cliente.

## Reglas de seguridad

- Nunca modificar, eliminar ni sobrescribir archivos en esta biblioteca.
- Nunca trabajar directamente en la rama `main` de esta biblioteca.
- Nunca publicar automáticamente sin aprobación humana.
- No inventar información del negocio: precios, testimonios, reseñas, horarios, certificaciones, datos legales, servicios, teléfono, dirección o redes sociales.
- Si falta información importante, solicitarla al usuario.
- Usar imágenes aportadas por el cliente o imágenes con licencia adecuada.
- Eliminar textos, imágenes y enlaces de demostración antes de entregar.

## Templates disponibles

### landing-startbootstrap-001

- Tipo: Landing page de una página.
- Usar para: negocios de servicios, consultores, gimnasios, restaurantes sencillos, agencias, profesionales y campañas para captar clientes.
- Objetivo principal: generar mensajes, llamadas, formularios o solicitudes de cotización.
- No usar para: e-commerce, carrito de compra, pagos, cuentas de usuario, membresías, reservas complejas, blogs grandes o aplicaciones web.
- Metadata: revisar `TEMPLATE-METADATA.md` antes de usar.

## Lista de verificación previa

Antes de mostrar la vista previa, verificar:

- El nombre de la marca es correcto.
- Los datos de contacto son correctos.
- No quedan textos de demostración.
- No quedan enlaces de demostración.
- Las imágenes tienen uso permitido.
- El diseño funciona en móvil y escritorio.
- Los botones principales funcionan.
- Los formularios se prueban o se marca claramente que requieren configuración.
- Se respetan el idioma y el público objetivo del cliente.
