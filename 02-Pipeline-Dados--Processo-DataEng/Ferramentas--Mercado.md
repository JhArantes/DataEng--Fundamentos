
# Ferramentas no Mercado 

Podemos dividir em 2 Tipos de Empresa

## 1. Empresas Tradicionais: Por que Ferramentas Antigas/Consolidadas?
1. Estabilidade e Confiabilidade
"Se não está quebrado, não conserte": Empresas tradicionais (bancos, seguradoras, varejo consolidado) priorizam sistemas estáveis e comprovados em produção há anos.

Exemplo: Oracle e SQL Server são usados há décadas, com suporte enterprise garantido.

2. Conformidade e Governança Rígida
Regulamentações (LGPD, GDPR, Basel III) exigem auditoria e rastreabilidade, presentes em ferramentas como IBM InfoSphere ou Informatica.

Legado regulatório: Sistemas antigos já estão adaptados a compliance, evitando riscos de migração.

3. Infraestrutura On-Premise e Investimento Anterior
Custo afundado (sunk cost): Empresas já investiram milhões em licenças de Oracle, Teradata ou SAP. Migrar para cloud é caro e complexo.

Integração com sistemas legados: Ferramentas como IBM DataStage funcionam bem em mainframes, enquanto soluções modernas exigem reengenharia.

4. Cultura de Avversão a Riscos
Processos lentos de TI: Grandes corporações têm ciclos longos para aprovação de novas tecnologias.

Medo de downtime: Startups podem experimentar falhas; empresas tradicionais não podem correr esse risco.

## 2. Startups: Por que Ferramentas Modernas/Cloud-Native?
1. Agilidade e Escalabilidade sob Demanda
Cloud = Flexibilidade: Startups usam BigQuery, Snowflake e AWS para escalar rapidamente sem investir em hardware.

Serverless e SaaS: Ferramentas como Fivetran e dbt eliminam a necessidade de gerenciar infraestrutura.

2. Custo Acessível e Pay-as-you-go
Sem licenças caras: PostgreSQL e Airflow são open-source; BigQuery cobra por consulta, não por servidor.

Economia em early-stage: Startups não podem pagar Oracle ou Cloudera, então optam por alternativas cloud.

3. Cultura de Experimentação e Inovação
Adoção rápida de tendências: Startups testam ferramentas como Apache Kafka (streaming) e Databricks (Lakehouse) antes de virar mainstream.

Time enxuto e multstack: Equipes pequenas preferem ferramentas que integram bem (ex: dbt + Snowflake + Airflow).

4. Necessidade de Dados em Tempo Real
Tradicionais usam batch (ETL) → Startups precisam de streaming (Kafka, Flink) para decisões ágeis.

Exemplo: Uma FinTech processa transações fraudelentas em milissegundos, não em lotes diários.


## Conclusão: Há Convergência?

Tradicionais estão migrando para o cloud (ex: bancos usando Snowflake), mas com cautela.

Startups, ao amadurecerem, podem adotar ferramentas enterprise (ex: Datadog para monitoramento).

O futuro é híbrido: Ferramentas modernas estão sendo absorvidas por corporações, enquanto startups buscam maturidade em governança.

Resumo:

Tradicionais = Estabilidade + Compliance + Legado → Ferramentas consolidadas.

Startups = Agilidade + Custo + Inovação → Soluções cloud-native.


---


# 3 Áreas de Data Eng e ferramentas que suprem tais necessidades

## 1. Ferramentas para Transformação de Dados

### Apache Spark
Framework de processamento distribuído para big data, com suporte a SQL, streaming, machine learning e processamento de grafos. Dominante no mercado por sua velocidade e versatilidade.

### dbt (data build tool)
Ferramenta de transformação de dados que permite aos analistas transformar dados em seus warehouses usando SQL. Tornou-se essencial para workflows modernos de ELT.

### Apache Airflow
Plataforma para orquestração de workflows programaticamente, muito popular para agendamento e monitoramento de pipelines de dados.

### AWS Glue
Serviço ETL totalmente gerenciado da AWS que facilita a preparação e carga de dados para análise.

### Apache Kafka
Sistema de mensagens distribuído para pipelines de dados em tempo real e aplicações de streaming.

### Apache Beam
Framework unificado para definir pipelines de dados batch e streaming, com execução em vários backends.

### Kebola
Plataforma ETL/ELT de baixo código para integração e transformação de dados.

### Airbyte
Plataforma open-source de integração de dados (ELT) que está ganhando popularidade como alternativa ao Fivetran.

### Fivetran
Solução gerenciada de ETL que automatiza a extração e carga de dados de diversas fontes para warehouses.

### DataForm
Ferramenta para desenvolvimento colaborativo de SQL em warehouses de dados.

### AWS Athena
Serviço de consulta interativa que permite analisar dados no S3 usando SQL padrão.

### Stitch
Serviço simples de ETL na nuvem, adquirido pelo Talend, focado em cargas incrementais.

### Dremio
Plataforma de lakehouse que acelera consultas em data lakes sem necessidade de ETL.

## 2. Ferramentas para Armazenamento e Cloud Computing
### Snowflake
Warehouse de dados em nuvem que separa computação e armazenamento, líder de mercado por sua escalabilidade e simplicidade.

### Databricks
Plataforma unificada baseada em Apache Spark que oferece processamento de dados, machine learning e colaboração em notebooks.

### Google BigQuery
Data warehouse totalmente gerenciado do Google Cloud com análise SQL petabyte-scale sem infraestrutura.

### AWS Redshift
Warehouse de dados em nuvem da AWS, popular para análise em grande escala.

### Delta Lake
Camada de armazenamento open-source que traz ACID transactions para data lakes.

### AWS S3
Serviço de armazenamento de objetos altamente escalável, base de muitos data lakes modernos.

### Azure Data Factory / Data Lake Storage
Serviço de integração de dados da Microsoft e solução de armazenamento para big data analytics.

### Apache Hadoop
Framework para processamento distribuído de grandes conjuntos de dados em clusters.

### Apache Hive
Sistema de warehouse para dados em Hadoop que permite consultas tipo SQL.

### Segment
Plataforma de CDP (Customer Data Platform) para coleta e roteamento de dados de clientes.

## 3. Ferramentas para Real-Time Analytics e BI
### Power BI
Solução de BI da Microsoft com forte integração com produtos Azure e atualizações automáticas.

### Tableau
Líder em visualização de dados e business intelligence, adquirido pela Salesforce.

### Looker Studio (Google Data Studio)
Ferramenta de BI e visualização de dados do Google, integrada ao BigQuery.

### Apache Flink
Framework para processamento de streams distribuído e de alta performance.

### Metabase
Ferramenta open-source de BI e visualização com foco em simplicidade.

### Superset
Plataforma de visualização de dados e business intelligence open-source da Apache.

### Azure Synapse Analytics
Serviço analítico ilimitado que une data warehouse e big data analytics.

### Presto
Motor de consulta SQL distribuído para consultas interativas em grandes conjuntos de dados.

### MicroStrategy
Plataforma de business intelligence empresarial com forte capacidade analítica.

### Redash
Ferramenta de visualização e dashboarding focada em equipes de dados.

### Apache Druid
Banco de dados colunar distribuído para datasets em tempo real.

### Dataedo
Ferramenta de catalogação e documentação de metadados.



## 4. Ferramentas Auxiliares e Subtools

### Containerização e Orquestração

#### **Docker**
- Padrão para empacotar aplicações em containers isolados
- Essencial para ambientes reprodutíveis de pipelines

#### **Kubernetes (K8s)**
- Sistema de orquestração de containers dominante
- Escala workloads (Spark, Flink, etc.)

#### **AWS ECS/Fargate**
- Serviços gerenciados AWS para containers
- Execução sem gerenciamento de infraestrutura


### Monitoramento e Observabilidade

#### **Prometheus + Grafana**
- Combinação clássica para monitoramento
- Alertas e métricas de pipelines

#### **Datadog**
- Plataforma unificada para monitoramento
- Cobre infra, aplicações e pipelines

#### **Elastic Stack (ELK)**
- Análise de logs em sistemas distribuídos
- Integração com Airflow, Spark, etc.


### CI/CD e Automação

#### **Jenkins**
- Servidor de automação open-source líder
- Principais casos de uso:
  1. Orquestração de jobs ETL/ELT
  2. Testes de dados automatizados
  3. Deploy de pipelines
- Integrações chave:
  - Airflow, Spark, Terraform
  - Plugins para Snowflake, BigQuery

#### **GitHub Actions/GitLab CI**
- Alternativas modernas com Git nativo
- CI/CD integrado ao versionamento

#### **Argo Workflows**
- Pipelines nativas para Kubernetes
- Ideal para ambientes cloud-native


### Ferramentas Específicas

#### **Great Expectations**
- Validação de qualidade de dados como código

#### **Dagster**
- Alternativa moderna ao Airflow
- Foco em desenvolvimento local

#### **MLflow**
- Gerenciamento de ciclo de vida de ML

#### **Pulumi**
- IaC multi-cloud alternativa



### CLIs e Utilitários

| Ferramenta       | Função Principal                          |
|------------------|------------------------------------------|
| `jq`/`yq`       | Processamento de JSON/YAML no terminal   |
| AWS CLI/GCloud   | Interação com serviços cloud             |
| Terraform CLI    | Gerenciamento de infraestrutura como código |

---

**Nota sobre Relevância**:  
✔️ Ferramentas cloud (Snowflake, Databricks) em ascensão  
✔️ Open-source (Spark, Airflow) mantém forte adoção  
✔️ Jenkins ainda dominante em enterprises  
✔️ Kubernetes tornou-se padrão para orquestração  


Nota sobre relevância: A ordenação considera adoção no mercado, demanda por profissionais, capacidade de inovação e crescimento recente. Ferramentas em nuvem (Snowflake, Databricks, BigQuery) têm ganhado relevância sobre soluções on-premise tradicionais. O ecossistema open-source (Spark, Airflow, dbt) continua extremamente relevante, especialmente em empresas com equipes técnicas maiores.