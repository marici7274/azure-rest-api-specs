# Azure.Developer.Signing

> see https://aka.ms/autorest

This is the AutoRest configuration file for Azure.Developer.Signing.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the Azure.Developer.Signing.

```yaml
openapi-type: data-plane
tag: 2023-06-15-preview
```

### Tag: 2023-06-15-preview

These settings apply only when `--tag=2023-06-15-preview` is specified on the command line.

```yaml $(tag) == '2023-06-15-preview'
input-file:
  - Azure.Developer.Signing/preview/2023-06-15-preview/azure.developer.signing.json
```

## Suppression


``` yaml
directive:
  - suppress: AvoidAnonymousTypes
    reason: The spec is autogenerated, I have no control over how models are defined.
```

---
