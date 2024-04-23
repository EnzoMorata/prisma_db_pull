# prisma_db_pull
Script necesario para obtener el modelo de la Base de Datos indicada en la variable de entorno.

## Requisitos

- Es necesario tener [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/) instalado.
- Para ejecutar el script es necesario copiar el archivo *.env.example* y renombrarlo como *.env*. Además, se deben rellenar las variables de entorno con los datos de la Base de Datos. Ya que indicarán la URL de conexión hacia la Base de Datos, siguen el siguiente [detalle de conexión](https://classic.yarnpkg.com/lang/en/docs/install/).

## Ejecución

Desde la terminal en el directorio raíz del repositorio, ejecutar el siguiente comando:

```bash
yarn db_pull
```

Dentro del archivo [schema.prisma](./prisma/schema.prisma) se habrá generado el modelo de la base de datos indicada en el archivo *.env*.