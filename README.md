# 🚀 This is a sample repo with Strapi Backend

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### ` develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

## ✅ Specify the import file

To import data into a Strapi instance use the strapi import command in the project root directory. Specify the file to be imported using the -f or --file option. The filename, extension, and path are required. If the file is encrypted, you are prompted for the encryption key before the import starts.

Example: Minimum command to import data from a file in the Strapi project root

```
npm npm run strapi import -- -f export_20221213105643.tar.gz.enc
```
