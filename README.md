Creamos el fichero package.json. Este fichero es utilizado por npm para, entre otras cosas, almacenar la información referente a nuestro proyecto, como pueden ser las dependencias.
>> npm init

Iinstalaremos la librería de mocha.js a través de npm. Le añadimos el parámetro –save al comando para que guarde dicha librería en el fichero package.json
>> npm install mocha --save

Iinstalar la dependencia de chai.js de la misma forma que instalamos en pasos anteriores mocha.js:
>>  npm install chai --save

Editamos el fichero package.json y le daremos valor al parámetro “test” que por defecto lo encontraremos vacío.
>> "test": "./node_modules/.bin/mocha --reporter spec

Ejecutamos nuestra prueba con: 
>> npm test o  mocha  nombre archivo.js
