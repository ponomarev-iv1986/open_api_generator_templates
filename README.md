# open_api_generator_templates
OpenAPI generator templates for python

Пример команды для генерации клиентов с помощью Open API Generator:
```commandline
java -jar openapi-generator-cli-7.17.0.jar generate -i http://path_to_swagger.json -g python -o ./output_dir --library asyncio --package-name package_name --skip-validate-spec -t /path_to_open_api_generator_templates/python
```
