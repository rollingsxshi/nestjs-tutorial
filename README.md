## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Notes
### adding modules
- run `nest g module [moduleName]`

### adding controllers to a module
- run `nest g controller [moduleName]`

### adding provider to a module
- run `nest g service [moduleName]`

### adding resource (shortcut to above steps)
- creates module, controller, service all at once
- for fast development of a Rest API
- run `nest g resource [resourceName]`

## Prisma
- `npm i prisma -D`
- `npx prisma init`
- `npx prisma migrate dev --name init`

## Rate limiting
- `npm i @nestjs/throttler`

## Logging
- can use nestjs-prsma package 
