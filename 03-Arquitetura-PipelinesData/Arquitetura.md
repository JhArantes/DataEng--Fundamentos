# Arquitetura de Pipelines de Dados
Para iniciar um projeto de pipeline de dados, o primeiro passo é entender claramente os requisitos de negócio. Isso envolve compreender quais problemas a empresa deseja resolver com dados e quais objetivos estratégicos ela quer alcançar — como, por exemplo, aumentar o lucro e reduzir custos.

## 1. Requisitos de Negócio
Antes de pensar em ferramentas ou tecnologias, é fundamental garantir que o pipeline será construído com um propósito claro:

Apoiar a empresa na tomada de decisões baseadas em dados;

Otimizar processos internos por meio de automações e análises;

Gerar insights acionáveis para diferentes áreas do negócio;

Reduzir custos operacionais e aumentar a eficiência.

Com isso em mente, o pipeline não é apenas uma estrutura técnica, mas uma ferramenta estratégica.

## 2. Hierarquia da Arquitetura de Dados
A construção de pipelines deve seguir uma hierarquia dentro da arquitetura geral de dados da empresa, respeitando diretrizes de escalabilidade, segurança e flexibilidade:

#### 2.1. Plataforma de Dados
É o ambiente onde os dados são centralizados e armazenados. Pode incluir serviços em nuvem, data warehouses, data lakes, entre outros.

#### 2.2. Arquitetura de Dados Corporativa
Define como os componentes irão interagir dentro da plataforma: ingestão, armazenamento, processamento e visualização. Deve garantir governança, integração e disponibilidade.

#### 2.3. Pipelines
São os fluxos responsáveis por:

Mover dados de uma origem (como bancos de dados, APIs, arquivos);

Transformar os dados para deixá-los limpos, estruturados e úteis;

Carregar os dados em um destino final, como um data warehouse ou uma ferramenta de visualização.

Cada pipeline deve ter um propósito específico e estar alinhado à estratégia de dados da empresa.

## 3. Características de um Bom Pipeline
Um pipeline eficiente deve:

Estar conectado aos requisitos de negócio;

Ter baixo custo operacional;

Ser seguro e seguir boas práticas de proteção de dados;

Ser flexível e adaptável às mudanças que surgirem ao longo do tempo;

Garantir qualidade e consistência dos dados.

## 4. PoC (Prova de Conceito)
Antes de implementar um pipeline em produção, é recomendável construir uma Prova de Conceito (PoC).

A PoC serve como um laboratório controlado, com o objetivo de:

Testar ferramentas e tecnologias;

Simular cenários reais e validar hipóteses;

Confirmar a viabilidade técnica e econômica do projeto;

Evitar investimentos desnecessários em soluções que não atendem aos requisitos.

---

# Perguntas para começar a Arquitetura de um Pipeline de Dados

1. Quais são os requisitos de negócio??

2. Quais resultados finais são nescessários??

3. Os dados estão disponíveis?? Quais são as fontes?

4. Quais tipos de formato(s) de dados estão disponíveis??

5. Qual o crescimento esperado do volume de dados??

6. Quanto de Armazenamento será nescessário??

7. Quanto de capacidade computacional será necessário??

8. Usaremos dados em Batch, Streaming ou ambos??

9. Já temos tecnologia que permita criar os pipelines??

10. Quais tecnologias devem ser consideradas??

11. Quais são os Acordos de Nível de Serviço (SLA's)??

12. Qual o custo de implementar e manter os pipelines??

13. Qual será o destino do Pipeline?? 

14. Como será o monitoramento??

15. Usaremos diversos pipelines encadeados??

16. Vamos criar pipelines locais, na nuvem ou ambos??




















