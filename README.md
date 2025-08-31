# desafio-instancia-de-banco-de-dados-
Configurando uma instância de Banco de Dados na Azure

# 🚀 Projeto: Instância de Banco de Dados no Azure

## 📖 Descrição
Este projeto documenta a criação e configuração de uma instância de banco de dados SQL gerenciado na Microsoft Azure, realizada como parte do desafio da [Digital Innovation One](https://dio.me). O objetivo foi aplicar conceitos de bancos de dados em nuvem, incluindo provisionamento, configuração, segurança, monitoramento de recursos, backup e gestão de custos.

## 🎯 Objetivos
- Criar e configurar uma instância de banco de dados SQL no Azure;
- Aplicar conceitos de rede, segurança, monitoramento e backup;
- Gerenciar recursos de forma econômica;
- Documentar o processo de forma clara e estruturada;
- Demonstrar conhecimento técnico em um repositório GitHub.

## 🛠️ Execução

### 1. Criação da Instância de Banco de Dados
A instância SQL foi criada com as seguintes configurações:
- Nome da instância: `sql-dio-anderson`
- Região: **Brasil Sudeste** (proximidade geográfica e menor latência)
- Tipo de banco: SQL gerenciado
- Usuário administrador: `admin_ander`
- Configuração de desempenho: camada básica (`Basic`) para testes e validação

### 2. Configuração de Rede e Segurança
- A instância foi configurada para permitir conexões seguras apenas de endereços IP autorizados.
- Foi habilitado o firewall do servidor SQL para proteger a instância contra acessos não autorizados.
- Configurações de autenticação e credenciais foram definidas seguindo boas práticas de segurança.

### 3. Backup
- Foi configurado backup automático da instância, garantindo a recuperação de dados em caso de falha.
- A retenção do backup foi definida conforme boas práticas, permitindo restaurar a instância para pontos específicos no tempo.
- Testes de restauração foram simulados para confirmar a integridade do processo de backup.

### 4. Custos
- A camada básica (`Basic`) foi escolhida estrategicamente para minimizar custos durante testes e validações.
- O painel **Custos + Faturamento** do Azure foi monitorado para acompanhar consumo e despesas.
- A VM e a instância SQL foram desligadas ou escalonadas quando não estavam em uso, evitando gastos desnecessários.

### 5. Validação
- A instância foi acessada remotamente utilizando o usuário `admin_ander`.
- Foi criado um banco de teste chamado `db_dio_test` para validar a conectividade e operações básicas (criação de tabelas, inserção e consulta de dados).
- Todas as operações ocorreram conforme esperado, confirmando a correta configuração da instância, rede, backup e otimização de custos.

### 6. Monitoramento e Encerramento
- O consumo de recursos foi acompanhado através do painel de monitoramento do Azure SQL.
- Boas práticas de desligamento e escalonamento automático foram aplicadas para otimização de custos e manutenção da segurança.

## 🧑‍💻 Tecnologias Utilizadas
- **Microsoft Azure**
- **SQL Database Gerenciado**
- **GitHub + Markdown**

## 📚 Referências
- [Documentação Oficial Azure SQL](https://learn.microsoft.com/azure/azure-sql/)
- [Guia de Markdown GitHub](https://docs.github.com/pt/get-started/writing-on-github)

## 💡 Observações Técnicas
  O processo de criação e configuração da instância reforçou a importância do planejamento, segurança, backup e gestão de custos em ambientes de nuvem. Definir rede, firewall, usuário administrador, camada de desempenho e políticas de backup são passos críticos para garantir que o banco de dados seja funcional, seguro e econômico. A experiência também evidenciou como documentação clara é essencial para replicar e manter ambientes de TI.
