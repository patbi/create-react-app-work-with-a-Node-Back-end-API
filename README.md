# create-react-app-work-with-a-Node-Back-end-API

> Example on using create Front React app with Node Express Backend

## Usage

Install [nodemon](https://github.com/remy/nodemon) globally

```
npm i nodemon -g
```

Install server and client dependencies

```
cd project_name && npm i
```

To start the server and client at the same time (from the root of the project)

```
cd project_name && npm run dev
```

## How this works

The key to use an Express backend with a project created with `create-react-app` is on using a **proxy**. We have a _proxy_ entry in `client/package.json`

```
"proxy": "http://localhost:5000/"
```


-Patrick BIYAGA
