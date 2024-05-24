### SalaryHero

SalaryHero es una aplicación web desarrollada en Python utilizando el framework Flask. La aplicación permite a los usuarios calcular el salario mensual de empleados y gerentes en base a los datos ingresados en un formulario web.

#### Características:

- **Cálculo del Salario Mensual:** La aplicación calcula el salario mensual de un empleado o gerente en base a los datos ingresados en el formulario.

#### Requisitos:

Para ejecutar esta aplicación, necesitas:

1. **Python 3:** Asegúrate de tener instalado Python 3 en tu sistema.
2. **Flask:** Si no tienes Flask instalado, puedes hacerlo utilizando pip:
   ```
   pip install Flask
   ```
3. **Archivos del Proyecto:** Debes tener los siguientes archivos en el mismo directorio:
   - `app.py`: Contiene el código principal de la aplicación.
   - `clases.py`: Define las clases `Empleado` y `Gerente` requeridas para el cálculo del salario.
   - `formulario.html`: Plantilla HTML para el formulario de entrada de datos.
   - `resultado.html`: Plantilla HTML para mostrar el resultado del cálculo.

#### Instrucciones de Uso:

1. **Clonar el Repositorio:** Descarga los archivos del proyecto o clona el repositorio en tu sistema.
2. **Ejecutar la Aplicación:** Abre una terminal en el directorio del proyecto y ejecuta el siguiente comando:
   ```
   python3 app.py
   ```
   Esto iniciará el servidor Flask.
3. **Acceder a la Aplicación:** Abre un navegador web y visita la dirección proporcionada por Flask, típicamente `http://localhost:5000`.
4. **Completar el Formulario:** Completa el formulario con los datos requeridos, como nombre, edad y salario base. Selecciona el tipo de empleado (regular o gerente) y, si corresponde, ingresa el bono para los gerentes.
5. **Calcular el Salario:** Haz clic en el botón "Calcular" para obtener el salario mensual.
6. **Capturar el Resultado:** Toma una captura de pantalla del resultado obtenido y guárdala como referencia.

Además, ten en cuenta que este proyecto se ejecutó desde una instancia EC2 con el puerto 5000 abierto, conectada a un entorno AWS Cloud9.

¡Disfruta usando SalaryHero para calcular de manera rápida y sencilla los salarios mensuales de tus empleados y gerentes!
