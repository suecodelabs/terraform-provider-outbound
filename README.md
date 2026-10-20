# Terraform provider for Multistax Outbound

The `suecodelabs/outbound` provider onboards AWS accounts and replaces NAT gateways with Multistax Outbound
gateways, for Terraform and OpenTofu.

```terraform
terraform {
  required_providers {
    outbound = {
      source = "suecodelabs/outbound"
    }
  }
}
```

Documentation: [Terraform Registry](https://registry.terraform.io/providers/suecodelabs/outbound/latest/docs).

This repository holds only the documentation and the signed release archives the registries publish from. It is
updated automatically on each release and does not accept pull requests.

Licensed under the [Mozilla Public License 2.0](LICENSE).
