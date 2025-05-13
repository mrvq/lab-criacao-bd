# 🗄️ Laboratório Azure - Configuração de Instância de Banco de Dados

## 🎯 Descrição do Desafio

Este repositório foi criado como parte do laboratório prático do curso de Azure. O objetivo é praticar a **configuração de uma instância de Banco de Dados** utilizando os serviços disponíveis na **plataforma Microsoft Azure**.

Como entregável, este repositório contém **resumos, anotações e dicas práticas** sobre o uso de bancos de dados na nuvem Azure. O conteúdo serve como **material de apoio para estudos e futuras implementações** profissionais.

---

## 📘 Conteúdo Estudado

### 🔹 Conceitos Fundamentais

- **Banco de Dados como Serviço (DBaaS)**: Modelo em que a gestão da infraestrutura do banco (atualizações, backups, disponibilidade) é feita pela plataforma Azure.
- **Azure SQL Database**: Serviço PaaS (Platform as a Service) que permite a criação de instâncias SQL com alta disponibilidade, segurança e escalabilidade.
- **Azure Database for MySQL/PostgreSQL**: Alternativas gerenciadas para bancos relacionais além do SQL Server.
- **Escalabilidade**: Capacidade de aumentar recursos de forma elástica (ex: CPU, memória, armazenamento).
- **Alta Disponibilidade**: Recursos nativos do Azure para garantir continuidade dos serviços, como replicação geográfica e failover automático.

---

## ⚙️ Etapas Práticas Realizadas

1. **Criação do Resource Group**  
   - Organização dos recursos em um grupo lógico.
2. **Criação da Instância de Banco de Dados**  
   - Escolha entre SQL Server, MySQL ou PostgreSQL.
   - Definição de região, tamanho, versão e configurações de backup.
3. **Configuração de Segurança e Acesso**  
   - Definição de firewall e regras de rede.
   - Configuração de login administrativo e senha.
4. **Criação do Banco de Dados**  
   - Criação de schemas e tabelas usando o Query Editor do portal ou ferramentas como SSMS ou Azure Data Studio.
5. **Testes de Conectividade**  
   - Conexão a partir de uma aplicação ou máquina local.
   - Teste de inserções, queries e autenticação.

---

## 💡 Dicas Importantes

- Use **camadas de serviço** conforme o perfil de uso (Basic, Standard, Premium).
- Habilite **autenticação do Azure AD** para segurança centralizada.
- Utilize **tags** para rastrear o custo e identificar o propósito de cada banco.
- Habilite **auditoria** e **diagnóstico** para monitoramento e compliance.
- Sempre configure **backup automático** e políticas de retenção adequadas.

---

## ✅ Conclusão

Durante este laboratório, pude compreender o processo de provisionamento e configuração de uma instância de banco de dados no Microsoft Azure. Essa prática reforçou conceitos fundamentais de banco de dados na nuvem, além de boas práticas de segurança, escalabilidade e gerenciamento de custos.

Este repositório serve como um material de referência para futuras implementações em projetos reais na nuvem.

---

📌 **Autor:** Marcio  
📅 **Data:** Maio de 2025
