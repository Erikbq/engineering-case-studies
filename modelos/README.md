# Modelos para os estudos de caso

Estes arquivos são instrumentos de coleta de informações. A redação pública final será feita depois de reunir os resumos e confirmar os pontos pendentes com Erik.

## Como usar

1. Abra o Codex no repositório do projeto correspondente.
2. Cole o pedido padrão abaixo.
3. Acrescente o contexto do projeto, disponível nesta página.
4. Cole o conteúdo completo do modelo correspondente.
5. Traga o levantamento, as evidências e as perguntas para a conversa do portfólio.

Não é necessário publicar os modelos no GitHub. As evidências internas servem à revisão; não devem ser copiadas automaticamente para o estudo público.

## Estrutura comum

- Resumo e ficha do projeto.
- Contexto e objetivo.
- Minha contribuição.
- Solução, arquitetura e fluxo de dados.
- Desafios e decisões técnicas.
- Qualidade e verificação.
- Entregas, resultados e estágio atual.
- Competências e aprendizados.
- Informações a confirmar e evidências internas.

## Pedido padrão para o Codex

Analise este repositório e prepare um levantamento técnico para um estudo de caso do meu portfólio no GitHub, seguindo o modelo Markdown que vou fornecer.

O foco do portfólio é desenvolvimento fullstack e engenharia de dados. Escreva em português, de forma objetiva e profissional, como em um currículo técnico.

Instruções:
- Consulte o código, a configuração e a documentação disponíveis. Não altere arquivos.
- Descreva o problema, a solução, a arquitetura, os fluxos relevantes, as tecnologias, os desafios e as entregas.
- Diferencie o que está implementado, o que está apenas configurado ou documentado e o que está planejado. A existência de código ou configuração não comprova implantação em produção.
- Registre a base das afirmações técnicas em uma seção separada de evidências internas: arquivos, módulos ou documentos consultados, sem copiar trechos de código. Essa seção servirá para revisão e não será publicada automaticamente.
- Quando uma informação não puder ser confirmada, escreva [A CONFIRMAR]. Identifique hipóteses como hipóteses. Não deduza os motivos de uma decisão apenas pela tecnologia utilizada.
- A minha contribuição individual e a divisão do trabalho com a equipe devem ser confirmadas por mim. Separe essas informações da descrição geral do sistema.
- Informe as verificações existentes e os resultados já registrados, distinguindo-os do que você verificou nesta análise. Não execute o projeto, testes, migrações ou integrações para produzir o resumo.
- Não invente métricas, ganhos, volume de dados, usuários, disponibilidade, segurança ou conclusão de etapas.
- O código e as imagens dos sistemas originais não podem ser publicados. Produza apenas descrições e, quando úteis, diagramas conceituais autorais. Omita credenciais, dados reais e nomes de clientes.
- Liste somente as tecnologias com papel relevante no projeto e explique a função de cada uma.

Entregue:
1. O levantamento preenchido seguindo o modelo, mantendo [A CONFIRMAR] onde necessário.
2. Uma seção separada com as evidências internas consultadas.
3. As perguntas que dependem de mim para finalizar o estudo de caso.

Priorize detalhes que mostrem como o sistema funciona e quais problemas foram resolvidos. Não reescreva o projeto nem proponha implementações novas.

Modelo e contexto específico: seguem abaixo.


## Contextos específicos

### Dashboard de inteligência comercial

Projeto interno desenvolvido individualmente por Erik para as áreas Comercial e Marketing da Fluxo Consultoria. O relato inicial menciona Next.js, Supabase, APIs do Google e Pipefy, leitura agendada de planilhas, tratamento de dados e backfill para comparar metas, vendedores e funil entre diferentes gestões. Conferir os detalhes no repositório.

[Modelo correspondente](./inteligencia-comercial.md)

### Transformação de uma ferramenta científica em aplicação web

Projeto realizado em equipe, com atuação de Erik nas frentes relatadas. Uma ferramenta local de análise preditiva de rochas, com geofísica e redes neurais, tinha aproximadamente 5 mil linhas de Python misturando interface e cálculos. O trabalho envolveu refatoração e aplicação web com Next.js, NestJS, EC2, SQS, RDS, S3, Nginx, Docker Compose, auditoria, hierarquia de acesso e MFA. O motor científico era preexistente. Conferir o papel e o estado real de cada componente.

[Modelo correspondente](./software-cientifico.md)

### Modelagem e migração de dados de um fundo de endowment

Projeto realizado em equipe. Erik atuou no mapeamento e na elaboração dos modelos descritivo e relacional de um fundo de endowment. No relato mais recente, a equipe estava entrando na fase de migração para banco relacional com ETL em arquitetura medalhão. Confirmar a situação atual no repositório e com Erik; não assumir que a migração terminou. O nome e a posição do cliente em rankings não são necessários para o estudo.

[Modelo correspondente](./engenharia-de-dados.md)
