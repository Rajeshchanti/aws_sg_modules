# security_group module

This module will create the security group

## Inputs
* project_name (Required) - your project name
* environment (Required) - which environment you are working in
* sg_name (Required) - Give your security group name
* sg_description (Optionsl) - Enter description
* common_tags (Optional) - Default value is empty, better to Provide tags
* sg_tags (Optional) - Default value is empty
* vpc_id (Required) - Give your VPC_ID
* sg_ingress_rules (Required) - Give allowing ports. Type is list

## Output
* sg_id - sg_id created