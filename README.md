<h1>Tarea Entorno de Desarrollo Odoo-Python</h1>

En este ejercicio hemos creado un entorno de desarrollo en Python para trabajar en Docker con la imagen de Odoo.
Para empezar, hemos creado un proyecto en Pycharm en el que hemos creado un documentos  ```docker-compose.yml``` el cual pasaré a explicar a continuación.

<h3>Documento Docker-Compose</h3>
Para crear este documento.

Hemos utilizado la imagen -> ```odoo: 14.0```

Hemos utilizado como base de datos, la imagen -> ``` postgres: 13.0```

Hemos mapeado los puertos de la base de datos -> ``` 5432:5432```

Hemos mapeado los puertos del odoo -> ``` 8069:8069```

Una vez creado el documento, pasaremos a ejecutarlo con el comando ```docker-compose up```. Una vez realizado dicho comando, tendremos nuestro odoo y nuestra base de datos postgres, listos y operativos para trabajar con ellos.

<h3>Configuración</h3>
Una vez creado el ```docker-compose.yml``` y con el odoo y la base de datos operativos, nos hemos conectado en el navegador como ``localhost``  al puerto ```8069``` y hemos configurado de inicio el Odoo, añadiendo y creando una nueva base de datos postgres, configurando usuario y contraseña. Además de la master password.

Despues de haber hecho la configuración y tener nuestro Odoo funcionando, hemos enlazado la base de datos postgres dentro de nuestro proyecto en Pycharm, donde tendremos acceso a todas las tablas, esquemas, usuarios y demás contenido de nuestro Odoo.