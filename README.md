# maildev - helm chart

    2020 Ondrej Sika <ondrej@ondrejsika.com>
    https://github.com/ondrejsika/maildev-helm

## Usage

Add repo

```
helm repo add ondrejsika https://helm.oxs.cz
```

Install

```
helm upgrade --install \
  <name> ondrejsika/maildev \
  --set host=<domain>
```

## Parameters

- `host` (default `maildev.local`) - Ingress hostname
