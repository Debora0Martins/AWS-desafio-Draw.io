# AWS-desafio-Draw.io

 # Desafio DIO – Gerenciamento de Instâncias EC2 na AWS

Este repositório contém anotações, insights e práticas realizadas no desafio da DIO sobre **instâncias EC2 na AWS**.  
O objetivo é consolidar os conhecimentos adquiridos, documentar o processo e ter um material de apoio para futuras implementações.

Desafio AWS EC2 – Documentação e Aprendizados

(Sobre o Desafio)

Este desafio teve como objetivo consolidar meus conhecimentos em gerenciamento de instâncias EC2 na AWS, incluindo criação de instâncias, configuração de volumes EBS, snapshots, permissões IAM e execução de comandos via PowerShell e CloudShell.

O repositório contém:
	•	Prints do passo a passo (17 fotos)
	•	Diagrama da arquitetura em Draw.io
	•	Insights e aprendizados adquiridos durante a prática

(Conceitos e Ferramentas Aprendidos)
 
	•	AWS EC2: criação, execução e gerenciamento de instâncias.
	•	AMIs e Snapshots EBS: aprendizado sobre imagens e backups de instâncias.
	•	IAM (Identity and Access Management): configuração de permissões para executar scripts e acessar instâncias via SSH.
	•	Autenticação segura: uso do Google Authenticator para acessar a AWS de forma protegida.
	•	PowerShell: execução de comandos administrativos no Windows Server.
	•	CloudShell: execução de scripts diretamente no ambiente da AWS.
	•	Draw.io: criação de diagramas de arquitetura e compressão básica de arquivos.
	•	Noção básica de arquitetura: adquirida através do uso do Draw.io para organizar visualmente os processos e fluxos da AWS.
	•	GitHub: versionamento de arquivos, organização de repositório e documentação técnica.

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
