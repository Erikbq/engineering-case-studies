# Transformação de uma ferramenta científica em aplicação web

> Modelo para levantamento interno. Preencher com base no projeto e no relato de Erik. As perguntas e os marcadores de confirmação serão retirados na redação pública final.

## Resumo

[Descrever em 2–3 frases o problema, a solução e a contribuição de Erik.]

| Aspecto | Informação |
| --- | --- |
| Contexto | [Organização e domínio, sem identificar o cliente.] |
| Atuação | [Individual ou em equipe; contribuição a confirmar com Erik.] |
| Situação atual | [Implementado, em andamento ou planejado; indicar a data do levantamento.] |
| Tecnologias principais | [Somente as relevantes; detalhar a função na arquitetura.] |

## 1. Contexto e objetivo

- O que a ferramenta científica fazia e qual era o objetivo de disponibilizá-la pela web?
- Como o programa original estava organizado e quais responsabilidades estavam misturadas?
- Quais requisitos funcionais e restrições foram estabelecidos? Prazo e contexto dependem de confirmação se não estiverem documentados.

**Conteúdo a preencher:** [A CONFIRMAR]

## 2. Minha contribuição

- Relacionar a atuação de Erik na refatoração, frontend, backend, integração, infraestrutura, filas, auditoria e acesso, para validação por ele.
- Distinguir a contribuição individual das entregas da equipe.
- Identificar os limites entre o motor científico preexistente e o software desenvolvido no projeto.

| Frente | Contribuição de Erik | Participação da equipe / escopo preexistente |
| --- | --- | --- |
| [Frente de trabalho.] | [Atividade concreta, a confirmar com Erik.] | [A CONFIRMAR] |

## 3. Solução, arquitetura e fluxo de dados

- Como a refatoração separou interface, cálculos e integração? Quais módulos resultaram?
- Descrever o fluxo de uma análise: solicitação, validação, entrada na fila, processamento, persistência e consulta do resultado, apenas onde houver implementação.
- Qual a função de Next.js, NestJS e Python e como esses componentes se comunicam?
- Onde entram SQS, RDS e S3? Quais componentes leem ou escrevem em cada serviço?
- Como EC2, Docker Compose e Nginx participam da execução? Distinguir infraestrutura configurada de implantação comprovada.
- Quais estados de tarefa e mecanismos de acompanhamento estão implementados?

**Fluxo principal:** [Origem → etapas de processamento → destino → uso.]

**Diagrama:** [Se útil, propor um Mermaid conceitual com conexões verificadas. Identificar componentes planejados.]

| Tecnologia ou componente | Função no projeto | Situação / evidência |
| --- | --- | --- |
| [Componente.] | [Papel concreto.] | [Implementado, configurado, documentado ou planejado.] |

## 4. Desafios e decisões técnicas

- Quais decisões foram necessárias para integrar o código científico à web?
- Por que foi utilizado processamento assíncrono, se o motivo estiver documentado?
- Como o sistema trata falhas, repetição de mensagens e tarefas interrompidas, se houver esses mecanismos?
- Como são implementados hierarquia de acesso, auditoria e MFA? Descrever o comportamento, sem expor segredos ou detalhes restritos.
- Registrar limitações e escolhas conhecidas sem afirmar garantias de segurança não verificadas.

| Desafio concreto | Abordagem adotada | Motivo conhecido e limitações |
| --- | --- | --- |
| [Problema observado.] | [Solução implementada.] | [Justificativa confirmada ou A CONFIRMAR.] |

## 5. Qualidade e verificação

- Como foi ou é verificada a preservação dos resultados científicos após a refatoração?
- Há testes, casos de referência, verificações de integração ou registros de validação?
- Quais verificações de permissão, processamento e falha estão presentes?
- Distinguir testes existentes, resultados registrados e itens que ainda não foram verificados.

**Verificações existentes:** [A CONFIRMAR]  
**Resultados registrados:** [A CONFIRMAR]  
**Limitações conhecidas:** [A CONFIRMAR]

## 6. Entregas, resultados e estágio atual

- Quais componentes e funcionalidades foram implementados e quais ainda estão em desenvolvimento?
- Existe informação confirmada sobre disponibilização ou uso da aplicação?
- Há medidas documentadas de processamento, volume, desempenho ou esforço de refatoração?
- Quais limitações e pendências precisam ser descritas?

| Entrega | Situação atual | Evidência ou resultado confirmado |
| --- | --- | --- |
| [Entrega concreta.] | [Concluída, em andamento ou planejada.] | [Descrição ou métrica com base identificada.] |

## 7. Competências e aprendizados

- Identificar aprendizados em refatoração, desenvolvimento fullstack, processamento assíncrono, integração científica, infraestrutura, auditoria e acesso.
- Separar os desafios enfrentados por Erik daqueles descritos apenas como requisitos gerais da equipe.

**Conteúdo a preencher:** [A CONFIRMAR]

## 8. Informações a confirmar com Erik

[Reunir perguntas sobre contexto, autoria, motivos de decisões, estágio de entrega e resultados que o repositório não permite verificar.]

## Evidências internas — retirar da versão pública

[Referenciar os arquivos, módulos ou documentos que sustentam o levantamento, sem copiar código. Identificar o que foi observado no código, o que veio de documentação e o que foi informado por Erik.]

---

[Voltar ao índice](./README.md)
