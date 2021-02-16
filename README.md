# Terraform Module AWS VPC

Creates a simpe AWS VPC

# Example

```workflow
module "vpc" {
  source = "git@github.com:hmanzur/terraform-module-vpc.git"

  name = "VPC Cool Name"
  
  cidr_block = "10.0.0.0.16"
}
```

## Variables

| Variable   | Default     | Required | Description    |
|------------|-------------|----------|----------------|
| name       | 10.0.0.0/16 | No       | VPC name       |
| cidr_block |             | Yes      | VPC CIDR Block |

## Outputs

- The VPC `Id`
- The VPC `cidr_block`
