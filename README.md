# AWS-desafio-Draw.io

 # Desafio DIO – Gerenciamento de Instâncias EC2 na AWS

Este repositório contém anotações, insights e práticas realizadas no desafio da DIO sobre **instâncias EC2 na AWS**.  
O objetivo é consolidar os conhecimentos adquiridos, documentar o processo e ter um material de apoio para futuras implementações.

---

## O Desafio
- Criar e gerenciar instâncias EC2 na AWS.  
- Trabalhar com **imagens AMI**.  
- Criar e restaurar **snapshots EBS**.  
- Documentar os processos técnicos de forma clara e organizada.  
- Utilizar o **GitHub** como ferramenta de registro e compartilhamento.  

---

## Passo a Passo Realizado
1. Criação de uma instância EC2 (tipo `t2.micro`) no console da AWS.  
2. Configuração de **Security Group** para permitir acesso SSH.  
3. Conexão via terminal:  
   ```bash
   ssh -i minha-chave.pem ec2-user@<ip-da-instancia>
