# m5-ep1

# 1 Usa los Hooks useEffect y useState
- Se utilizan los hooks useEffect y useState para obtener las especialidades de los médicos y mostrarlas en la página de servicios.

# 2 Uso de Fetch API o Axios para el Consumo de la API
- Considerando que en el punto anterior se utilizó fetch, se instala axios mediante el comando npm install axios y se consume una API externa para obtener los datos de usuarios que simularán doctores, estos serán cargados vía useState y mostrados en consola. Se genera una petición con URL inexistente para visualizar el manejo de errores de axios. Se espera recibir un error de tipo 404 y se mostrará en la consola.

# 3 Peticiones Basadas en Eventos del Usuario
- Se utiliza el evento onclick de un boton como trigger del useEffect para camboiar la información de lols servicios. Se utiliza la función toggleModal para cambiar el estado de isOpen y se utiliza la función setSpecialty para actualizar la información de los servicios.

# 4 Manejo de Errores en Peticiones Asíncronas
- En envían los errores vía props y se muiestra mensaje por pantalla.

# 5 Optimización del Rendimiento al Omitir Efectos en useEffect
- Se utilza el segundo argumento de useEffect para evitar que se vuelva a ejecutar el componente si no es necesario.
