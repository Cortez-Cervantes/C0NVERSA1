<div align="justify">
  <b>Ambiente-Enter</b> desarrollaron <b>C0NVERSA1</b>, una aplicación web para convertir la plantilla complicada del <b><i>"Asistente para la Identificación de las Normas Oficiales Mexicanas de Seguridad y Salud en el Trabajo"</i></b> en formato <i>.pdf</i> en un formato manejable de extensión <i>.csv</i>.
</div>

<br><br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/14faf60c-e321-4154-b835-9826f03a3c5a" alt="C0NVERSA1 Portada" style="max-width: 100%; height: auto;">
</p>

<p align="center">
  La figura de arriba muestra la portada de la aplicación <b>C0NVERSA1 v0.1</b>.
</p>

<br><br>

<h3><b> ¿Cómo usar la aplicación en Windows?</b></h3>

<ul>
  <li>Descargar el archivo <b>"C0N1-v0.1.zip"</b> y descomprimir la carpeta.</li>

  <li>Abrir el cuadro de diálogo Ejecutar (<kbd>Windows</kbd> + <kbd>R</kbd>), escribir:</li>
  <pre>powershell</pre>

  <li>Verificar si Python está instalado (si no, descárgalo desde 
    <a href="https://www.python.org/" target="_blank">python.org</a>):</li>
  <pre>python --version</pre>

  <li>Navegar hasta la carpeta descomprimida <b>"C0N1-v0.1"</b> usando la terminal (puedes usar 
    <code>dir</code> para listar carpetas y <code>cd</code> para cambiar de directorio).</li>

  <li>Crear un entorno virtual para instalar los módulos necesarios (solo se hace una vez):</li>
  <pre>python -m venv env_Autogestion</pre>

  <li>Activar el entorno virtual:</li>
  <pre>.\env_Autogestion\Scripts\activate</pre>
  <p><b>⚠ Nota:</b> Si aparece un error de permisos, ejecuta lo siguiente y repite el paso anterior:</p>
  <pre>Set-ExecutionPolicy Unrestricted -Scope Process</pre>

  <li>Instalar las dependencias necesarias (espera unos segundos/minutos):</li>
  <pre>pip install -r requerimientos.txt</pre>

  <li>Ejecutar la aplicación (se quedará en ejecución en la terminal):</li>
  <pre>python app_0.1_.py</pre>

  <li>Abrir el navegador y acceder a la aplicación con la siguiente URL:</li>
  <pre>http://localhost:8000</pre>
</ul>

<br><br>

<p align="center">
  <i><b>📌 Nota:</b> Si tienes problemas ejecutando scripts en PowerShell, revisa la política de ejecución. 
  Puedes consultar más detalles en la documentación de <a href="https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/unblock-file" target="_blank">PowerShell</a>.</i>
</p>
