## GraphQL boilerplate

Boilerplate to use GraphQL and GraphiQL


### Usage
#### Install
```
$ yarn
```

#### Build GraphiQL interface
```
$ yarn run build
```

#### Run server (width `nodemon`)
```
$ yarn run serve
```

### Configuration
#### Schema & Types
The graphQL schema must be define on the file `./server/schema.gql`.

All the graphQL types must be define in `./server/types/` directory and must have the `gql` extension.

#### Resolvers
All the resolver files must be setted in `./server/resolvers`