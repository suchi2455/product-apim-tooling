## apimcli init

initialize a new project in given path

### Synopsis


initialize a new project in given path. If a openAPI definition provided API will be populated with details from it

```
apimcli init [project path] [flags]
```

### Examples

```
apimcli init myapi --openapi petstore.yaml
```

### Options

```
  -d, --definition string   Provide a YAML definition of API
  -f, --force               Force create project
  -h, --help                help for init
      --oas string          Provide an OpenAPI specification file for the API
```

### Options inherited from parent commands

```
  -k, --insecure   Allow connections to SSL endpoints without certs
      --verbose    Enable verbose mode
```

### SEE ALSO
* [apimcli](apimcli.md)	 - CLI for Importing and Exporting APIs and Applications
