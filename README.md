# api_nodejs
<h1>Instalación local de paquetes</h1>
<p>Solo se recomienda instalar paquetes localmente para cada proyecto individual.</p>

<p>Para instalar un paquete localmente, navega hasta el directorio de la aplicación de tu sitio (no el directorio /public). 
El comando para instalar un paquete es:</p>
_______________________________________________
<p>npm install</p>
_______________________________________________

<h1>Actualizar paquetes</h1>
<p>Primero, verifica qué paquetes deben actualizarse:</p>
_______________________________________________
npm outdated
_______________________________________________
<p>Puedes actualizar un solo paquete con:</p>
_______________________________________________
npm update -S <package_name>
_______________________________________________
<p>Puedes actualizar todos los paquetes locales con:</p>
_______________________________________________
npm update -S
_______________________________________________

<h2>Actualizar paquetes globales</h2>
<p>Primero, verifica qué paquetes deben actualizarse:</p>
_______________________________________________
npm outdated -g --depth=0
_______________________________________________
<p>Puedes actualizar un solo paquete con:</p>
_______________________________________________
npm outdated -g <package_name>
_______________________________________________
<p>Puedes actualizar todos los paquetes globales con:</p>
_______________________________________________
npm update -g
_______________________________________________

<h2>Base de datos "library"</h2>


