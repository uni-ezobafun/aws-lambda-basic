# aws-lambda/typescript-deploy

### setup

```
$ npm install
$ npm run build-dev
$ sam local start-api -p 3001 -t ./sam/dev/template.yaml
$ curl -X GET http://127.0.0.1:3001/ping
```
