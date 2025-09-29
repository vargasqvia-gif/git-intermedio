**1.-¿Qué es una rama (branch) en Git y para qué se utiliza?**

Una rama es como una copia del proyecto donde puedes trabajar sin afectar el código principal.

Sirve para probar cosas nuevas, agregar funciones o arreglar errores sin arruinar lo que ya funciona.

La rama principal normalmente se llama main.

**2.-Explica con tus palabras qué significa hacer un merge**.

Hacer un merge es juntar los cambios de una rama con otra.

Por ejemplo, si trabajaste en una rama llamada nueva-funcion y terminaste, haces un merge para combinar ese trabajo con la rama principal.

**3.-¿Qué es un conflicto de fusión (merge conflict) y cómo se puede resolver?**

Un conflicto pasa cuando dos personas cambian la misma parte de un archivo y Git no sabe qué versión debe dejar.

Cómo se soluciona:

Abrir el archivo con conflicto.

Elegir qué cambios conservar o mezclarlos.

Guardar el archivo y hacer commit para confirmar la solución.

**4.-Diferencia entre fork y clone en GitHub.**

Fork: guardas tu propia versión de un proyecto en GitHub.

Clone: descargas ese proyecto para editarlo en tu computadora.

**5.-¿Qué es un pull request y para qué se usa en proyectos colaborativos?**

Un pull request es pedir que tus cambios se unan al proyecto principal.

Sirve para que los demás revisen tu trabajo antes de agregarlo y asegurar que todo esté bien hecho.

**6.-Investiga y explica 3 buenas prácticas para colaborar en equipo usando GitHub**.

Crear una rama por cada tarea:

Así el trabajo está ordenado y no se mezcla con otras cosas.

Ejemplo: feature/login para la pantalla de inicio de sesión.

Hacer commits claros y frecuentes:

Guardar cambios seguido y con mensajes que expliquen bien qué hiciste.

Ejemplo:

"Agregado botón de registro en la página principal"

Actualizar tu rama antes de fusionar:

Descargar los últimos cambios para evitar conflictos.

Comando:

git pull origin main

