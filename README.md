# dotnet-templates

.NET templates.

## About

Custom .NET templates for creating boilerplate with `dotnet new`. The `samples/` are minimal examples for reference. The `meta/` templates are templates for creating other templates.

To test a template, install it.
```sh
dotnet new install --force <path to template>
```

Make sure it's listed as a template.
```sh
dotnet new list
```

Then verify the output.
```sh
dotnet new <template shortname> --output bin/
```