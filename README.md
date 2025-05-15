# Laboratório Azure - Instância de Banco de Dados SQL

## 🧠 Objetivo
Documentar o processo de criação e configuração de uma instância gerenciada de SQL no Microsoft Azure, conforme proposto no laboratório da DIO.

## ⚙️ Passo a Passo

### 1. Acesso ao Portal do Azure
- Link: [https://portal.azure.com](https://portal.azure.com)

### 2. Criação da Instância SQL
- Tipo: SQL Managed Instance
- Nome da instância: `sql-dio-lab`
- Região: Brasil Sul
- Versão: SQL Server 2022
- Usuário administrador: `adminsql`
- Segurança: Senha definida na criação
- Firewall: Configurado para acesso público (para testes)

### 3. Conexão à Instância
- Ferramenta sugerida: Azure Data Studio ou SQL Server Management Studio (SSMS)
- String de conexão gerada automaticamente pelo portal
- Exemplo de conexão testada com SSMS

### 4. Dicas e Observações
- **Importante**: Sempre verifique a política de firewall para permitir acesso ao seu IP
- Use ferramentas como SSMS ou Azure Data Studio para gerenciar seu banco
- Lembre-se de **pausar ou excluir a instância** se não for mais utilizar, para evitar cobranças

## 📚 Referências
- [Tutorial Oficial Microsoft - SQL Managed Instance](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal)
- [Portal Azure](https://portal.azure.com)
