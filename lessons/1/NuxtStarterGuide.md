# Nuxt.js starter guide

## Files

### nuxt-config.js
    
    - Nuxt.js configuration.

## Directories

### pages

    - Where the pages are stored. 
    - Automatically routed by Nuxt.js (see routing).

### components

    - Where the components used in pages are stored.
    - Unlike Vue we don't need to import them on the script.

### assets
    
    - Static and non-compiled files that will be served.
    - Example: CSS, images and fonts.

### static
    
    - Assigned to the root of the server (where the site is deployed).
    - Contains files whose names won't change
    - EXAMPLE: robots.txt or favicon.

## Deployment

### Server

1. Run the command:

```
npm run build
```
**This will create the directory .output/server**

2. Deploy the folder in the server.

### Server (preview)

**Allows to see a preview of this application without having to deploy it.**

```
npm run preview
```

### Static

1. Run the command:

```
npm run generate
```
**This will create the directory .output/publoc**

2. Deploy the folder in the server.

## Netlify deployment

### Static

1. Go to ***nuxt.config.js***.
2. Add the following property to the configuration.
```js
target:'static'
```
3. **Set git branch** to ***main***.
4. Run the command
```
npm run generate
```
5. **Copy** generated directory ***.output/public*** **to server**

### Client

1. Go to ***nuxt.config.js***.
2. Add the following properties to the configuration.
```js
target:'static'
ssr:'false'
```
3. **Set git branch** to ***main***.
4. Run the command
```
npm run generate
```
5. **Copy** generated directory ***.output/public*** **to server**

