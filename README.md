<div align="justify">
  <b>Ambiental Enter</b> desarrollaron <b>C0NVERSA1</b>, una aplicación web para convertir el formato complicado en <i>.pdf</i> generado por el <b><i>"Asistente para la Identificación de las Normas Oficiales Mexicanas de Seguridad y Salud en el Trabajo"</i></b> en un formato manejable de extensión <i>.csv</i>.
</div>

<br><br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/14faf60c-e321-4154-b835-9826f03a3c5a" alt="C0NVERSA1 Portada" style="max-width: 100%; height: auto;">
</p>

<p align="center">
  La figura de arriba muestra la portada de la aplicación <b>C0NVERSA1 v0.1</b>.
</p>

<br><br>

<h3><b>¿Cómo usar la aplicación (Windows)?</b></h3>
<ul>
  <li>Descargar el archivo <b>"C0N1-v0.1.zip"</b> y descomprimir la carpeta.</li>
  <li>Abrir el cuadro de diálogo Ejecutar (Windows + R) y ejecutar PowerShell.</li>
  <li>Verificar si tienes Python instalado (si no, instálalo desde <a href="https://www.python.org/" target="_blank">python.org</a>):</li>
  <pre>python --version</pre>
  <li>Configura la dirección de la terminal para ir a la carpeta descomprimida <b>"C0N1-v0.1"</b> (puedes usar los comandos <code>dir</code> para listar los directorios y <code>cd</code> para cambiar el directorio).</li>
  <li>Crea un entorno virtual para instalar solo los módulos necesarios para ejecutar la aplicación (una vez):</li>
  <pre>python -m venv env_Autogestion</pre>
  <li>Instala los módulos necesarios:</li>
  <pre>pip install -r requerimientos.txt</pre>
  <li>Ejecuta la aplicación:</li>
  <pre>python app_0.1_.py</pre>
  <li>Copia y pega la siguiente dirección local en tu navegador para utilizar la aplicación web:</li>
  <pre>http://localhost:8000</pre>
</ul>

<br><br>

<p align="center">
  <i><b>Nota:</b> Si tienes problemas con la ejecución en PowerShell, asegúrate de permitir la ejecución de scripts. Para más detalles, puedes consultar <a href="https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/unblock-file" target="_blank">Unblock-File cmdlet</a>.</i>
</p>
