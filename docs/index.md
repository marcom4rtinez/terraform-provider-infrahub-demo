---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "infrahub Provider"
subcategory: ""
description: |-
  
---

# infrahub Provider



## Example Usage

```terraform
terraform {
  required_providers {
    infrahub = {
      source  = "marcomartinez.ch/marcom4rtinez/infrahub"
      version = "1.0"
    }
  }
}

provider "infrahub" {
  api_key         = "XXX"
  infrahub_server = "http://10.0.0.1:8000"
  branch          = "main"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `api_key` (String, Sensitive) API Key to access Infrahub
- `branch` (String) Infrahub Branch
- `infrahub_server` (String) Infrahub Server running API
