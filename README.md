# waziup-api

Waziup Api Server

## Install It
```
npm install
```

## Run It
#### Run in *development* mode:

```
npm run dev
```

#### Run in *production* mode:

```
npm compile
npm start
```

#### Deploy to the Cloud
e.g. CloudFoundry

```
cf push waziup-api
```

### Try It
* Point you're browser to [http://localhost:3000](http://localhost:3000)
* Invoke the example REST endpoint `curl http://localhost:3000/api/v1/examples`
* Interactive API doc at [http://localhost:3000/api-explorer](http://localhost:3000/api-explorer)

THis api connect to a local keycloak server on localhost:8080. THis is hardcoded for now.

   
