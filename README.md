## Proyecto Back-end Noticias-Web

Una vez descargado el proyecto, descomprímelo y posteriormente a eso tienes que instalar "NodeJS" desde su página oficial https://nodejs.org/es/download/ la opción que dice LTS.

Si tienes Windows lo único que tienes que hacer es descargarlo y darle siguiente siguiente, caso contrario hay muchos recursos en YouTube de como instalar NodeJS en diferentes sistemas operativos (Windows ,Mac, Linux, etc).

Una vez instalado NodeJS ve hacia la carpeta que descargaste en el primer paso, da click derecho y posteriormente "click en abrir terminal".

En caso no te aparezca la opción sugiero lo siguiente:

- Abre la carpeta con el proyecto
- Copia la ruta que aparece en la parte superior, en mi caso esta es la ruta C:\Users\cueva\Downloads\trabajo
- En los programas busca CMD o Powershell y da click en abrir.
- Escribe el siguiente comando sin comillas: "cd $ruta"
- En mi caso sería algo así: "cd C:\Users\Downloads\trabajo"
- Dale enter y listo.

Una vez en la terminal ejecuta estos dos comandos:

- npm i
- npm run start

Te debe salir un mensaje que diga lo siguiente: "¡Todo correcto, ya puedes usar el servicio!", en caso el mensaje no te salga comunicate conmigo.

¡Excelente! el servicio se esta ejecutando,no cierres la terminal en la que estas.

Ahora para poder usar el servicio sigue las instrucciones de la parte de abajo del documento, como vez esta todo lo que se solicitó como requerimiento.

Saludos.

---

## ENDPOINTS

1. **BASE_URL:** _http://localhost:3000/_
2. **Register:** _http://localhost:3000/auth/local/register_
3. **Login:** _http://localhost:3000/auth/local/login_
4. **Create list of favorites:** _http://localhost:3000/api/favs_
5. **Get list of favorites:** _http://localhost:3000/api/favs_
6. **Get one list of favorites:** _http://localhost:3000/api/favs/:id_
7. **Delete one list of favorites:** _http://localhost:3000/api/favs/:id_

### Register

- POST
- url:3000/auth/local/register
  {
  email:""
  password:""
  }
- password > 8 caracteres

### Login

- POST
- url:3000/auth/local/login
  {
  email:""
  password:""
  }
- Devuelve el token
