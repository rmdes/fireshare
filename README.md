# fireshare

Self host your media and share with unique links

# Server

```
pip install -r app/server/requirements.txt
```

then source the dev env vars.

```
source .env.dev
```

run the flask app

```
flask run
```

# Client

navigate to the client root and install dependencies

```
cd app/client && npm i
```

start the react dev server

```
npm start
```

Navigate to `http://localhost:3000`

In production, flask will serve the react app and it will be access at `http://localhost:5000` from within
the docker container.
