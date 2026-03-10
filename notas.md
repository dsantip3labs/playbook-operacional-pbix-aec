# Objetivo

Realizar anotações sobre o desenvolvimento do playbook operacional, definir minhas decisões e desenhar um caminho mental a se seguir.

# Decisões

### Capitulos

- Introdução ao mundo de dados e Business Intelligence
- Filosofia de construção de soluções de BI
- O papel do analista de dados
- Entendimento do problema de negócio
- Introdução às fontes de dados
- Arquitetura de dados e uso estratégico de SQL
- Modelagem analítica de dados
- Introdução ao Power BI
- Preparação e tratamento de dados no Power Query
- Criação de medidas, cálculos e métricas
- Arquitetura mental de um dashboard
- Padrões visuais, design e prototipação de dashboards com Figma
- Construção de dashboards analíticos
- Validação e confiabilidade dos dados
- Performance e escalabilidade
- Documentação e governança
- Publicação em workspace web e ORBI
- Capítulo Final — Caminhos para evoluir além deste Playbook

### Sobre o planejamento - O que precisa estar presente

#### Contexto logo no início

Adicionar uma seção como “Aplicação deste playbook no contexto de planejamento operacional” para deixar claro que o material foi pensado para rotinas como:

- acompanhamento operacional

- leitura de indicadores

- modelagem de bases analíticas

- construção de dashboards

- comparação entre plano, realizado e desvios

Isso ancora o material no mundo real sem deixar tudo rígido demais.

#### Exemplos reais ao longo dos capítulos

O diferencial do playbook está em usar exemplos do ambiente de planejamento, como:

- volumetria

- SLA / NS

- TMA

- aderência

- absenteísmo

- produtividade

- capacidade

- HC

- forecast

- realizado vs planejado

- visões intradia e históricas

A lógica é simples: conteúdo genérico ensina ferramenta; conteúdo contextualizado forma analista.

#### Blocos recorrentes dentro dos capítulos

Em vez de criar novos capítulos, incluir em vários deles um bloco padrão com algo como:

- Aplicação prática em planejamento

Esse bloco serve para mostrar como aquele tema aparece na rotina real.

Exemplos:

- SQL: consolidar bases de forecast, realizado, escala e produtividade

- Modelagem: separar fatos de realizado e plano, com dimensões como data, fila, canal, operação, segmento e operador

- Dashboard: responder perguntas como:
    - estamos dentro da meta?
    - onde está o desvio?
    - o problema é volume, capacidade ou produtividade?
    - o que precisa de ação agora?

#### Um ponto específico sobre BI em planejamento

Vale incluir em algum capítulo inicial um item como:

Particularidades do BI para planejamento operacional

#### Pontos que não podem ser esquecidos:

- confiança no número

- granularidade correta

- diferença entre análise executiva e operacional

- uso de bases tratadas em SQL

- comparação entre plano e real

- cuidado com atualização, corte de hora, intervalo e consistência das fontes

#### Regra principal para não esquecer

O objetivo não é deixar o playbook:

- genérico demais

- nem específico demais

O ideal é o meio-termo:
estrutura sólida + contexto de planejamento + exemplos reais distribuídos ao longo do material.