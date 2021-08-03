## Challenge backend/nodejs/mongodb

Este challenge tiene como objetivo usar herramientas básicas como js y git para conecterse, leer, procesar y guardar información (en MongoDB/NoSQL) de transacciones que interactuan con contratos escritos en solidity.


Para esto se pide que el candidato realice las siguientes tareas:

1. Cree un repositorio público de Bitbucket/Github en su cuenta para el challenge, usando una rama para desarrollo: 'development'
2. Inicialice el repositorio para nodejs, ignorando node_modules, logs, etc.
3. Instalar las librerias necesarias (web3) para poder interactuar con blockchains EVM y procesar información de contratos.
4. Instanciar web3 con un RPC público (en este caso se pide Polygon | Ver referencias)
5. Teniendo como punto de partida esta transaccion [0x2b1cb0ee5c14b33d1871a671c235dce2972861a1ad1410659251f0b9d7fac39f](https://polygonscan.com/tx/0x2b1cb0ee5c14b33d1871a671c235dce2972861a1ad1410659251f0b9d7fac39f) y usando el RPC instanciado previamente, se pide:

  a) Usar los métodos correspondientes de web3 para obtener información programática en JSON de la transacción, junto con los logs de eventos.

  b) En base a las propiedades y objetos devueltos por la api de web3 cuando se consulta la transacción, se pide crear un Schema de Mongoose, mediante el cual se   defina las propiedades y tipos de datos para guardar la información de la transacción procesada en el item a)
  c) Crear los métodos necesarios para guardar dicha información
  

6. Crear un archivo index.js que al ejecutarlo muestre por consola el resultado de consultar la información guardada en MongoDB
 
7. Adicionalmente, se pide un error handling básico e instrucciones escritas de cómo correr la solución.

8. Al terminar enviar url del repositorio.


#### Referencias:

Polygon Public RPC: [https://matic-mainnet.chainstacklabs.com](https://matic-mainnet.chainstacklabs.com)

[Event logs](https://medium.com/mycrypto/understanding-event-logs-on-the-ethereum-blockchain-f4ae7ba50378)

[Web3 doc](https://web3js.readthedocs.io/en/1.0/web3-eth.html)

[topics & getPastLogs](https://ethereum.stackexchange.com/questions/61585/how-to-setup-topics-for-function-getpastlogs)
