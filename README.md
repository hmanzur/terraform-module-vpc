# Terraform Module AWS VPC

How to use

```workflow
module "vpc" {
  source = "git@github.com:hmanzur/terraform-module-vpc.git"

  name = "VPC Cool Name"
}
```

## Variables

| Variable   | Default     | Required | Description                                                        |
|------------|-------------|----------|--------------------------------------------------------------------|
| name       | 10.0.0.0/16 | No       | VPC name                                                           |
| cidr_block |             | Yes      | VPC CIDR Block                                                     |

## Outputs

- The VPC `Id`
- The VPC `cidr_block`
