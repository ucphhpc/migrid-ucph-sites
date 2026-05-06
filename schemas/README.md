# JSON Validator Schemas
Our JSON Validator action using
https://github.com/GrantBirki/json-yaml-validate
not only checks that json files are fundamentally valid, but also that they
follow a known format (schema):
https://github.com/GrantBirki/json-yaml-validate/#schema-validation
The schema(s) used are specified in files here and must follow the standard
https://ajv.js.org/json-schema.html#json-schema

A working one can be generated with the `genson` python package in line with
https://docs.unstructured.io/api-reference/legacy-api/partition/generate-schema
