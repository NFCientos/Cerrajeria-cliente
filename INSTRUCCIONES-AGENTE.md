INSTRUCCIONES DEL AGENTE — CREACIÓN DE PÁGINAS WEB

OBJETIVO

Tu función es ayudar a crear y personalizar páginas web para clientes utilizando la información proporcionada en "Formulario-cliente.md" y una plantilla independiente destinada a nuevos clientes.

El objetivo es transformar las respuestas de un cliente en una página web funcional, profesional, clara y adaptable a teléfonos móviles.

---

1. PROTECCIÓN DE SITIOS EXISTENTES

Los sitios web de clientes existentes son independientes del sistema de automatización.

Nunca modificar, reemplazar, eliminar, renombrar ni sobrescribir archivos pertenecientes a un cliente existente durante la creación de un nuevo sitio.

En este repositorio:

- "Index.html" pertenece al sitio de Cerrajería.
- "logo-cerrajeria.png" pertenece al sitio de Cerrajería.
- "plantilla tarjeta profesional" es un recurso de referencia.

Estos archivos están protegidos.

No utilizar "Index.html" como plantilla de trabajo para un nuevo cliente.

No reemplazar el contenido de "Index.html" por los datos de otro cliente.

No reemplazar "logo-cerrajeria.png" por el logotipo de otro cliente.

No modificar "plantilla tarjeta profesional" salvo autorización explícita.

Si existe cualquier duda sobre qué archivo debe modificarse, detenerse y solicitar confirmación al usuario.

---

2. ARCHIVOS DEL PROYECTO

Antes de realizar una modificación relacionada con un nuevo cliente:

1. Revisar "Formulario-cliente.md".
2. Revisar "AGENTS.md".
3. Revisar este archivo.
4. Revisar la plantilla independiente destinada a nuevos clientes.
5. Revisar los recursos específicos del cliente.
6. No modificar archivos protegidos.

No utilizar sitios existentes como plantillas de trabajo.

---

3. INFORMACIÓN DEL CLIENTE

Utilizar exclusivamente la información proporcionada por el cliente.

No inventar:

- teléfonos
- direcciones
- precios
- horarios
- servicios
- redes sociales
- opiniones
- certificaciones
- promociones
- información comercial

Si un dato no fue proporcionado, no inventarlo.

Cuando una pregunta del formulario indique "No aplica", no mostrar esa información en la página.

---

4. ESTRUCTURA DE LA PÁGINA

La página debe adaptarse al tipo de negocio.

Como estructura general, considerar:

1. Encabezado
2. Logotipo
3. Nombre del negocio
4. Descripción breve
5. Botón de contacto principal
6. Servicios o productos
7. Información relevante del negocio
8. Ubicación, si corresponde
9. Horarios, si corresponde
10. Redes sociales, si corresponde
11. Galería de imágenes, si corresponde
12. Información adicional
13. Pie de página

No es obligatorio utilizar todas las secciones.

Solo mostrar las secciones para las cuales exista información relevante.

---

5. CREACIÓN DE UN NUEVO CLIENTE

Cuando se reciba el formulario de un nuevo cliente:

1. Analizar toda la información proporcionada en "Formulario-cliente.md".
2. Revisar "AGENTS.md" y "INSTRUCCIONES-AGENTE.md".
3. Utilizar exclusivamente "PLANTILLA/index.html" como plantilla maestra para nuevos clientes.
4. Considerar "PLANTILLA/index.html" como archivo protegido y de solo lectura durante la creación del cliente.
5. Comprobar que exista la carpeta "CLIENTES/".
6. Crear una carpeta nueva y exclusiva dentro de "CLIENTES/" para el nuevo cliente.
7. Comprobar que esa carpeta no exista previamente.
8. Crear dentro de esa carpeta una copia independiente de "PLANTILLA/index.html".
9. Personalizar únicamente la copia ubicada dentro de la carpeta del nuevo cliente.
10. Incorporar exclusivamente los datos proporcionados por ese cliente.
11. Incorporar únicamente los recursos correspondientes a ese cliente.
12. Mantener los recursos específicos del cliente dentro de su propia carpeta cuando corresponda.
13. Revisar todos los enlaces, botones, imágenes y funciones.
14. Comprobar que no existan datos pertenecientes a otros clientes.
15. Comprobar que ningún archivo protegido haya sido modificado.
16. Mantener intactos todos los sitios existentes.

Ejemplo de estructura:

"PLANTILLA/index.html"
↓
"CLIENTES/nombre-del-cliente/index.html"

Cada cliente debe tener su propia carpeta, su propia página y sus propios recursos.

Nunca utilizar:

"Index.html"
"logo-cerrajeria.png"
"plantilla tarjeta profesional"
la carpeta de otro cliente
la página de otro cliente

como punto de partida para crear un nuevo cliente.

Si la carpeta del nuevo cliente ya existe:

DETENER EL PROCESO.

No sobrescribir ni modificar archivos existentes sin confirmación explícita del usuario.

Si existe cualquier duda sobre qué carpeta o archivo corresponde al nuevo cliente:

DETENER EL PROCESO Y SOLICITAR CONFIRMACIÓN AL USUARIO.

No asumir.
No sobrescribir.
No eliminar.
No modificar otros clientes.
No modificar "PLANTILLA/index.html".

Una vez creada y personalizada la copia independiente, continuar con las revisiones de CONTACTO, GOOGLE MAPS, REDES SOCIALES, DISEÑO, IMÁGENES y REVISIÓN FINAL.

---

6. CONTACTO

Cuando el cliente proporcione un número de WhatsApp:

Crear un botón funcional de WhatsApp utilizando el número proporcionado.

Cuando existan dos contactos:

Mostrar claramente:

- Contacto 1
- Contacto 2

Cada botón debe dirigir al número correspondiente.

No mostrar números telefónicos innecesariamente si el cliente solicita que permanezcan ocultos visualmente.

Si existe un teléfono para llamadas, crear un botón de llamada mediante:

"tel:"

---

7. GOOGLE MAPS

Si el cliente proporciona un enlace de Google Maps:

Crear un botón visible que permita abrir la ubicación.

Utilizar exactamente el enlace proporcionado.

No modificar ni inventar el enlace.

Si falta el enlace, no crear un enlace ficticio.

---

8. REDES SOCIALES

Si el cliente proporciona Instagram, Facebook o TikTok:

Crear botones funcionales hacia las cuentas correspondientes.

Si una red social no fue proporcionada, no crear un enlace ficticio.

---

9. DISEÑO

El diseño debe:

- ser profesional
- ser responsive
- funcionar correctamente en teléfonos Android y iPhone
- utilizar botones grandes y fáciles de tocar
- mantener una jerarquía visual clara
- respetar los colores proporcionados por el cliente
- utilizar correctamente el logotipo
- evitar elementos innecesarios

La página debe verse correctamente tanto en pantallas pequeñas como grandes.

---

10. WHATSAPP

Los enlaces de WhatsApp deben utilizar el formato correcto.

Cuando sea apropiado, utilizar un mensaje inicial relacionado con el servicio.

Ejemplo:

"Hola, quisiera consultar por sus servicios."

No inventar datos del negocio dentro del mensaje.

---

11. IMÁGENES

Utilizar únicamente las imágenes proporcionadas por el cliente cuando estén disponibles.

Los recursos visuales de cada cliente son independientes.

Cuando el cliente proporcione un logotipo:

1. Guardar el logotipo dentro de la carpeta exclusiva de ese cliente.
2. Utilizar ese archivo para reemplazar la variable "{{LOGO}}".
3. Utilizar una ruta relativa que apunte al recurso ubicado dentro de la propia carpeta del cliente.

Ejemplo:

"CLIENTES/nombre-del-cliente/logo.png"

y:

"CLIENTES/nombre-del-cliente/index.html"

deben pertenecer al mismo cliente.

No utilizar como recurso de un nuevo cliente:

- "logo-cerrajeria.png"
- logotipos de otros clientes
- fotografías de otros clientes
- imágenes de otros clientes
- recursos ubicados en carpetas de otros clientes

Nunca utilizar rutas como:

"../../logo-cerrajeria.png"

ni ninguna otra ruta que haga que un nuevo cliente dependa del logotipo de Cerrajería o de otro cliente.

Si el cliente no proporciona un logotipo:

- No inventar uno.
- No reutilizar el logotipo de otro cliente.
- No copiar un logotipo existente de otro sitio.
- No utilizar "logo-cerrajeria.png".
- Mantener preparada la estructura para incorporar posteriormente el logotipo del cliente.

Utilizar textos "alt" descriptivos para las imágenes.

Si una imagen necesaria no está disponible, dejar preparada la estructura para incorporarla posteriormente en lugar de inventar o reutilizar una imagen perteneciente a otro cliente.

---

12. SEGURIDAD Y CALIDAD

No incluir código malicioso.

No incluir scripts innecesarios.

No recopilar información personal del visitante sin autorización.

Evitar formularios que envíen información a servicios externos si no existe una configuración explícita para ello.

Mantener el código organizado y fácil de modificar.

---

13. COMPATIBILIDAD

La página debe funcionar en:

- Google Chrome
- Safari
- navegadores móviles Android
- navegadores móviles iPhone

Evitar depender de funciones experimentales.

---

14. INDEPENDENCIA ENTRE CLIENTES

Cada cliente debe tener:

- sus propios datos
- sus propios textos
- sus propios enlaces
- sus propios logotipos
- sus propias fotografías
- su propia página
- su propia copia de la plantilla

Nunca reutilizar accidentalmente información de otro cliente.

Antes de finalizar una página, comprobar que no contiene:

- nombre de otro negocio
- teléfonos de otro negocio
- WhatsApp de otro negocio
- dirección de otro negocio
- Google Maps de otro negocio
- redes sociales de otro negocio
- servicios de otro negocio
- promociones de otro negocio
- logotipos de otro negocio
- fotografías de otro negocio

---

15. DATOS FALTANTES

Si faltan datos esenciales para construir una función:

No inventarlos.

Indicar qué información falta.

Ejemplo:

"Falta el enlace de Google Maps para configurar el botón de ubicación."

Si la información faltante no impide crear la página, continuar utilizando únicamente los datos disponibles.

---

16. REVISIÓN FINAL

Antes de considerar terminada una página:

Comprobar:

- nombre del negocio
- logotipo
- descripción
- servicios
- teléfonos
- WhatsApp
- Google Maps
- redes sociales
- horarios
- colores
- imágenes
- botones
- enlaces
- versión móvil
- ausencia de información de otros clientes
- independencia de los archivos de otros clientes

Todos los enlaces deben apuntar al destino correcto.

No afirmar que una función fue probada si realmente no pudo comprobarse.

---

17. FORMA DE TRABAJO

Cuando recibas las respuestas de un nuevo cliente:

1. Analizar toda la información.
2. Identificar qué secciones necesita la página.
3. Seleccionar la plantilla independiente.
4. Crear una copia para el cliente.
5. Determinar qué elementos deben modificarse.
6. Implementar la información del cliente.
7. Incorporar sus recursos.
8. Revisar enlaces y botones.
9. Revisar la versión móvil cuando sea posible.
10. Comprobar que ningún archivo protegido fue modificado.
11. Informar claramente qué se modificó y qué información falta.

No realizar cambios destructivos.

---

18. REGLA DE SEGURIDAD ANTE DUDAS

Si el agente no puede determinar con certeza:

- qué archivo pertenece al nuevo cliente
- cuál es la plantilla independiente
- qué archivo debe modificar
- si una acción puede afectar a un cliente existente

debe detenerse y solicitar confirmación al usuario.

No asumir.

No sobrescribir.

No eliminar.

---

PRINCIPIO FUNDAMENTAL

FORMULARIO = datos reales del cliente.

PLANTILLA = estructura y diseño reutilizable.

CLIENTE = copia independiente de la plantilla.

SITIOS EXISTENTES = protegidos.

AGENTS.MD = reglas generales del agente.

El agente debe combinar el formulario del cliente con una plantilla independiente para producir una página web personalizada sin modificar los sitios de otros clientes.