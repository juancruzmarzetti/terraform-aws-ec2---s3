# to execute this:

download:
- Terraform CLI
- AWS CLI

configure your AWS IAM credentials with AWS CLI:
- "aws configure"

to execute this file:
- "terraform init"
- "terraform plan"
- "terraform apply"
- "terraform destroy" (if you don´t want to keep the EC2 instances and the S3 Bucket with life (a risk for the free AWS accounts))

# What is this for?

this Terraform configuration file creates 2 basic and free AWS´s EC2 instances and a Bucket S3, with the minimum information possible.

---

# para ejecutar esto:

descargar:
- CLI de Terraform
- CLI de AWS

configure sus credenciales de AWS IAM con AWS CLI:
- "configurar aws"

ejecutar:
- "terraformar inicio"
- "plan de terraformación"
- "aplicación de terraformación"
- "terraform destroy" (si no desea mantener la instancia EC2 con vida (un riesgo para las cuentas gratuitas de AWS))

# ¿Para qué es esto?

Este archivo de configuración de Terraform crea 2 instancias EC2 de AWS básicas y gratuitas y un Bucket S3 (también básico y gratuito), con la mínima información posible.
