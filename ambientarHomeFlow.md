=========|| REQUISITOS PARA PODER AMBIENTAR HOMEFLOW ||=============

 
==|| BACKEND ||==
- Algún IDE, como Spring Tools Eclipse
- JDK 17
- Para validar instalación de JDK: java --version 
- BD debe estar prendida o conectada
- Postgres 18

==|| FRONTEND ||==
- Descarga e instala la versión LTS de Node.js.
- Validar instalación node: node --version
- npm: desde la consola del proyecto, ir a frontend/homeflow-frontend y ejecutar npm install
- Validar la instalación de npm: npm --version 
- Levantar front: en la consola colocarse en la carpeta del front y ejecutar npm run dev

==|| CONFIGURACIÓN VScode ||==
- abrir poweshell como admin
- colocarse en la carpeta donde exista el archivo vscode_extensions.txt
- ejecutar: Get-Content vscode_extensions.txt | ForEach-Object { code --install-extension $_ }