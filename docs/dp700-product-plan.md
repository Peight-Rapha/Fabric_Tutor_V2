# Fabric Tutor — Plano de Produto DP-700

## Visão

O Fabric Tutor será principalmente uma plataforma de preparação para a certificação DP-700, usando um projeto prático completo em Microsoft Fabric como laboratório de aplicação.

O produto deve ajudar o aluno a:

- estudar os objetivos da DP-700;
- responder questões autorais alinhadas à certificação;
- praticar decisões técnicas em cenários realistas;
- executar laboratórios no Microsoft Fabric;
- apresentar evidências do trabalho realizado;
- identificar lacunas de conhecimento;
- revisar erros e conceitos fracos;
- chegar mais preparado para o exame e para situações reais de engenharia de dados.

## Posicionamento

O produto não será apenas:

- um banco de questões;
- um simulador de prova;
- um curso linear de Microsoft Fabric;
- um projeto isolado de portfólio.

Será uma plataforma de preparação para a DP-700 com um laboratório Fabric integrado.

O eixo principal será a certificação. O projeto prático servirá para validar e aprofundar os conceitos estudados.

## Experiência principal

```text
Diagnóstico
    ↓
Plano de estudo
    ↓
Questões autorais
    ↓
Laboratório prático relacionado
    ↓
Evidência da execução
    ↓
Avaliação explicada
    ↓
Revisão dos pontos fracos
    ↓
Simulado
```

## Modos da aplicação

### 1. Practice Mode

Modo principal para preparação para a DP-700.

O usuário responde questões organizadas por:

- domínio;
- subcompetência;
- dificuldade;
- tipo de questão;
- desempenho anterior;
- relação com laboratório prático.

### 2. Build Mode

Ambiente de laboratórios práticos baseados em um projeto de dados no Microsoft Fabric.

O projeto de referência será uma plataforma brasileira de inteligência sobre investimentos de longo prazo. O domínio financeiro será apenas o contexto de negócio; o objetivo principal será praticar engenharia de dados no Fabric.

### 3. Review Mode

Área de revisão personalizada com base em:

- questões respondidas incorretamente;
- conceitos com baixo desempenho;
- laboratórios incompletos;
- evidências reprovadas ou insuficientes;
- erros recorrentes;
- tópicos que não foram praticados recentemente.

### 4. Exam Mode

Simulados com tempo, distribuição de questões, dificuldade progressiva e relatório de desempenho por domínio.

## Questões autorais

As questões serão criadas internamente e alinhadas aos objetivos oficiais da DP-700.

O banco não deve depender da reprodução de questões reais do exame. A proposta é avaliar as mesmas competências por meio de cenários originais, explicações próprias e referências oficiais.

### Tipos de questão

#### Conhecimento

Avaliam conceitos, funcionalidades, limitações e diferenças entre recursos do Microsoft Fabric.

#### Cenário

Apresentam uma necessidade de negócio ou restrição técnica e pedem a solução mais adequada.

#### Prática

Pedem ao usuário para configurar, implementar, consultar ou validar algo no Fabric.

#### Troubleshooting

Apresentam um erro, resultado inesperado, problema de desempenho ou falha de pipeline e pedem diagnóstico ou correção.

### Metadados de cada questão

Cada questão deve registrar:

```text
ID
Domínio DP-700
Subcompetência
Tipo: conhecimento | cenário | prática | troubleshooting
Dificuldade
Cenário
Enunciado
Alternativas
Resposta correta
Explicação da resposta correta
Explicação das alternativas incorretas
Conceito avaliado
Erro comum
Laboratório relacionado
Evidência esperada
Referência oficial
Versão ou data da referência
```

### Critério de qualidade

Toda questão deve seguir este fluxo:

```text
Objetivo oficial
    ↓
Competência observável
    ↓
Cenário plausível
    ↓
Resposta única ou justificadamente superior
    ↓
Explicação técnica
    ↓
Referência oficial
```

O sistema não deve apenas informar se a resposta está certa ou errada. Deve explicar:

- qual decisão técnica era necessária;
- por que a resposta escolhida é adequada;
- por que as demais alternativas são menos adequadas;
- qual evidência prática comprovaria o conhecimento;
- qual conceito o usuário deve revisar.

## Projeto Fabric como laboratório

O projeto prático não precisa reproduzir toda a sequência do exame. Ele funcionará como um conjunto de laboratórios independentes e conectados.

Laboratórios previstos:

- ingestão e transformação;
- Lakehouse e Delta Lake;
- Data Warehouse;
- pipelines e Dataflow Gen2;
- notebooks e Spark;
- SQL e modelagem dimensional;
- streaming e Eventhouse;
- segurança e governança;
- monitoramento e troubleshooting;
- otimização de cargas e consultas;
- deployment e ciclo de vida.

Cada laboratório deve indicar:

- objetivos da DP-700 relacionados;
- capacidade prática exercitada;
- pré-requisitos;
- tarefa a ser executada;
- evidências esperadas;
- critérios de aceitação;
- questões de revisão;
- erros comuns;
- conceitos aprendidos.

## Matriz de rastreabilidade

O produto deve manter uma relação explícita entre certificação, teoria e prática:

```text
Objetivo DP-700
    ↓
Questões autorais
    ↓
Laboratório relacionado
    ↓
Evidência produzida
    ↓
Avaliação de domínio
```

Nem todo objetivo precisa ser ensinado exclusivamente pelo projeto prático. Alguns serão cobertos principalmente por questões teóricas ou de cenário.

O projeto deve aprofundar os principais conceitos, enquanto o banco de questões deve cobrir toda a matriz da DP-700.

## Diagnóstico e progresso

O sistema deve medir progresso por competência, não apenas por quantidade de questões respondidas.

Indicadores possíveis:

- taxa de acerto por domínio;
- taxa de acerto por tipo de questão;
- desempenho por dificuldade;
- tempo médio de resposta;
- reincidência de erros;
- laboratórios concluídos;
- evidências aprovadas;
- conceitos revisados;
- confiança estimada versus desempenho real;
- prontidão para o exame.

O plano de estudo deve recomendar as próximas atividades com base nas lacunas identificadas.

## Segurança e qualidade do conteúdo

- As questões devem ser autorais e não copiar conteúdo protegido do exame.
- O conteúdo deve ser alinhado aos objetivos oficiais vigentes.
- Referências oficiais devem ser registradas para conceitos sujeitos a mudanças.
- Questões ambíguas ou com mais de uma resposta defensável devem ser revisadas ou removidas.
- A versão da matriz de habilidades deve ser identificada.
- O sistema deve separar fatos, recomendações e inferências.

## Escopo inicial recomendado

O foco inicial será exclusivamente a preparação para a DP-700.

O primeiro ciclo deve priorizar:

1. modelo de dados das questões;
2. cadastro de objetivos e subcompetências;
3. criação de questões autorais;
4. resolução e avaliação;
5. explicação das respostas;
6. acompanhamento de erros e desempenho;
7. relação entre questões e laboratórios;
8. um primeiro conjunto de laboratórios Fabric;
9. diagnóstico inicial;
10. revisão personalizada.

Funcionalidades como colaboração multiusuário, gamificação avançada, publicação pública, autenticação completa e infraestrutura de produção podem ficar para fases posteriores.

## Princípio central

> A certificação organiza o caminho; o projeto Fabric prova que o conhecimento pode ser aplicado.

