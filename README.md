# newmanStressTests


Solo correr con "npm start" o "yarn start" despues de haber bajado las dependencias.

En el archivo index.js esta el contenido de la collection:

    Usa este formato para collections fisicas:
    collection: path.join(__dirname, 'postman/postman_collection.json'), 

    O este para URLS:
    collection: 'https://www.getpostman.com/collections/f731a92bd2449e359ffc',


Aca indicas cantidad de "threats" que corren en paralelo
const PARALLEL_RUN_COUNT = 10
