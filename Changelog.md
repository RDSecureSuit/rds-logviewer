
# Changelog

## 03.09.2021 (Beta 1.0)
- Se agregó el diseño del formulario donde introducirán puerto, usuario, contraseña, el host y el nombre de la base de datos.
- Se incorporó el código de la creación del archivo ini la ruta esta por definirse para ver donde se guardará el archivo.
- En el evento dek Botón 1 del formulario Configini, lo que hace es leer lo que contenga el archivo ini, si no contiene ninguna información no mostrara nada en los campos y el button 2 lo que hace es guardar los datos que se escriben en el formulario y lo guarda en el archivo ini que se creó anteriormente guarda todas las variables que vienen en el ejemplo del github
- Se utilizo la api de Windows para poder leer y guardar el archivo ini (que API)
- La ruta del archivo ini en este caso se guarda en el disco local “D”, **la duda que tengo es como integrarlo bien al proyecto**
# Correccion de Bugs.
## 21-09-2021 (Beta 3)
- Al momento de crear el archivo ini ya no lo crea basio, si no ya contiene algunos valores predefinidos.
- Cuando se guardan los datos de la base de datos en el formulario ya no es necesario volverlos a escribir cuando se vuelva a ejecutar por que ya se quedan guardados.
- Se simplifico el condigo del formulario en diferentes secciones para que sea mas entendible al momento de leerlo.

