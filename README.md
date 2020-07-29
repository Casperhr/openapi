# openapi
OpenAPI feature tests

OpenAPI 3 split into modules

Main Api file is [api.yaml](./petstore/api.yaml)

## Components (Global)
- [Responses](./petstore/components/responses.yaml)
- [Schemas](./petstore/components/schemas.yaml)
- [Security Schemas](./petstore/components/securitySchemas.yaml) 


## Modules

### Pet
The main module file is [./petstore/modules/pet/api.yaml](./petstore/modules/pet/api.yaml)

**Models**

- [Category - ./petstore/modules/pet/models/category.yaml](./petstore/modules/pet/models/category.yaml)
- [Pet - ./petstore/modules/pet/models/pet.yaml](./petstore/modules/pet/models/pet.yaml)
- [Tag - ./petstore/modules/pet/models/tag.yaml](./petstore/modules/pet/models/tag.yaml) 


### Store
The main module file is [./petstore/modules/store/api.yaml](./petstore/modules/store/api.yaml)

**Models**

- [Order - ./petstore/modules/pet/models/category.yaml](./petstore/modules/pet/models/category.yaml)


### User
The main module file is [./petstore/modules/user/api.yaml](./petstore/modules/user/api.yaml)

**Models**

- [User - ./petstore/modules/user/models/user.yaml](./petstore/modules/user/models/user.yaml)
