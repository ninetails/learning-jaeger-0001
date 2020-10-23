# learning-jaeger-0001

> https://medium.com/@danwild.io/observability-for-front-end-web-clients-with-opentelemetry-and-jaeger-in-5-minutes-343f719fbf5a

## TODO

- [ ] Tests using [@opentelemetry/plugin-fetch](https://github.com/open-telemetry/opentelemetry-js/tree/master/packages/opentelemetry-plugin-fetch)

## Usage

after cloning...

### Running Jaeger & CORS anywhere (with Docker Compose)

At root

```sh
$ docker-compose up -d
```

### Testing example application

go to `opentelemetry-js/examples/tracer-web-jaeger`, run:

```sh
$ npm install
$ npm start
```

And open http://localhost:8090.
