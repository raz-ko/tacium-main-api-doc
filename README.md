# tacium-main-api
Tacium Main API

## Code generation
The code generation can be done by any open-api code generator.
Here we use swagger-codegen (https://github.com/swagger-api/swagger-codegen)
### swagger-codegen
```shell
swagger-codegen generate -i doc/tacium_main_api.yml -l html -o dist
```