## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_time"></a> [time](#provider\_time) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [time_static.example](https://registry.terraform.io/providers/hashicorp/time/latest/docs/resources/static) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_additional_tags"></a> [additional\_tags](#input\_additional\_tags) | n/a | `map(any)` | `{}` | no |
| <a name="input_cost_center"></a> [cost\_center](#input\_cost\_center) | Cost Center for chargeback. | `string` | `"000000-00"` | no |
| <a name="input_environment"></a> [environment](#input\_environment) | Environment for provisioning (dev\|qa\|stage\|prod). | `string` | n/a | yes |
| <a name="input_name"></a> [name](#input\_name) | Common name to be used for all provisioned AWS resources except additional resources. For naming additional resources of same type, specify `name_override` in individual modules | `string` | n/a | yes |
| <a name="input_owner"></a> [owner](#input\_owner) | Team DL for the product team. | `string` | n/a | yes |
| <a name="input_platform_version"></a> [platform\_version](#input\_platform\_version) | Version of Platform used to provision infrastructure | `string` | n/a | yes |
| <a name="input_product"></a> [product](#input\_product) | Platform product name. | `string` | n/a | yes |
| <a name="input_service_name"></a> [service\_name](#input\_service\_name) | Application service name | `string` | n/a | yes |
| <a name="input_service_version"></a> [service\_version](#input\_service\_version) | Version of the application service | `string` | `"0.0.1"` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_common_prefix"></a> [common\_prefix](#output\_common\_prefix) | Common prefix to be applied for resource. |
| <a name="output_common_tags"></a> [common\_tags](#output\_common\_tags) | Map of common tags to be applied to all product resources. |
| <a name="output_current_time"></a> [current\_time](#output\_current\_time) | n/a |
