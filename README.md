# Terraform CI/CD Pipeline with AWS

Este projeto demonstra uma pipeline DevOps completa utilizando Terraform e GitHub Actions para validar infraestrutura automaticamente.

## Arquitetura

GitHub → GitHub Actions → Terraform → AWS

## O que o pipeline faz

1. Checkout do código
2. Instala Terraform
3. Configura credenciais AWS
4. Executa Terraform Init
5. Executa Terraform Validate
6. Executa Terraform Plan automaticamente

## Tecnologias utilizadas

- Terraform
- AWS
- GitHub Actions
- Infrastructure as Code (IaC)
- CI/CD

## Estrutura do projeto

.
├── main.tf
├── variables.tf
├── outputs.tf
└── .github/workflows/terraform.yml

## Objetivo

Automatizar validação de infraestrutura utilizando CI/CD.

## Autor

Rayane Santana  
DevOps & Cloud Enthusiast
