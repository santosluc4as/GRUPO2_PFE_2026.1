# DOCUMENTAÇÃO DO PROJETO — REFORMULAÇÃO DO SITE ACBRASIL
# Metodologia Scrum | Sprints Semanais | Abril de 2026 | Lucas Santos

================================================================
1. VISÃO GERAL DO PROJETO
================================================================

Objetivo: Reformulação completa do site institucional da ACBrasil
(acbrasil.org.br), com foco em modernização visual, melhoria de UX,
acessibilidade e performance.

Conduzido com metodologia Scrum, sprints semanais e entregas incrementais.

Objetivos Principais:
- Modernizar a identidade visual do site
- Melhorar a navegação e experiência do usuário
- Garantir responsividade em dispositivos móveis
- Otimizar desempenho e tempos de carregamento
- Facilitar a manutenção futura do conteúdo

================================================================
2. EQUIPE SCRUM
================================================================

Membro              | Papel         | Responsabilidade (AP1)
--------------------|---------------|--------------------------------
Prof. Thiago        | Product Owner | Define/prioriza backlog;
Marcondes           |               | valida entregas
--------------------|---------------|--------------------------------
Lucas Santos        | Scrum Master  | Scrum + Organização de Sprints
--------------------|---------------|--------------------------------
Juan Lucas          | Desenvolvedor | Design no Figma
--------------------|---------------|--------------------------------
Marcus Martins      | Desenvolvedor | 5W2H
--------------------|---------------|--------------------------------
Brenno Marques      | Desenvolvedor | Brainstorm
--------------------|---------------|--------------------------------
Bernardo Chagas     | Desenvolvedor | Mapa Mental
--------------------|---------------|--------------------------------
Pedro Lucas         | Desenvolvedor | Documento de Visão
--------------------|---------------|--------------------------------
Rodrigo Abranches   | Desenvolvedor | Análise de Tarefas

Obs: As tarefas secundárias de cada membro correspondem aos
requisitos de documentação da AP1.

================================================================
3. 5W2H — elaborado por Marcus Martins
================================================================

What  (O quê?)   Reformulação completa do site institucional da ACBrasil
Why   (Por quê?) Site atual tem design desatualizado, baixa usabilidade e não é responsivo
Who   (Quem?)    Equipe com 6 devs, 1 Scrum Master e 1 Product Owner
Where (Onde?)    Desenvolvimento remoto/presencial; repositório no GitHub
When  (Quando?)  Em andamento, com sprints semanais e entregas incrementais
How   (Como?)    HTML, CSS e React (progressivo), seguindo o framework Scrum
How much (Custo) Projeto acadêmico — custo baseado em horas de trabalho da equipe

================================================================
4. METODOLOGIA SCRUM
================================================================

Princípios adotados:
- Transparência: progresso e impedimentos visíveis a toda equipe
- Inspeção: artefatos e progresso revisados frequentemente
- Adaptação: ajustes realizados o quanto antes quando necessário

Por que Scrum?
- Permite entregas parciais e validação contínua com o PO
- Facilita identificação rápida de problemas
- Mantém equipe alinhada às prioridades do produto
- Ideal para requisitos que evoluem ao longo do tempo

================================================================
5. ESTRUTURA DAS SPRINTS (duração: 1 semana)
================================================================

Segunda — Sprint Planning
  - Revisão e priorização do backlog com o PO
  - Seleção dos itens da sprint
  - Quebra das histórias em tarefas técnicas
  - Estimativa de esforço e definição da meta

Terça a Quinta — Daily Scrum (15 min)
  - O que fiz ontem?
  - O que farei hoje?
  - Existe algum impedimento?

Sexta — Sprint Review
  - Demonstração das funcionalidades ao PO
  - Validação e feedback

Sexta — Sprint Retrospective (após a Review)
  - O que funcionou bem?
  - O que pode melhorar?
  - Quais ações tomar na próxima sprint?

================================================================
6. BACKLOG DO PRODUTO
================================================================

ID     | História de Usuário                                         | Prioridade | Status
-------|-------------------------------------------------------------|------------|----------
US-01  | Como visitante, quero acessar a página inicial reformulada  | Alta       | A definir
US-02  | Como visitante, quero navegar pelo site pelo celular         | Alta       | A definir
US-03  | Como visitante, quero encontrar informações institucionais   | Média      | A definir
US-04  | Como visitante, quero acessar as redes sociais da ACBrasil  | Média      | A definir
US-05  | Como administrador, quero atualizar o conteúdo facilmente   | Baixa      | A definir

================================================================
7. DEFINIÇÃO DE PRONTO (DoD)
================================================================

Uma tarefa só é considerada pronta quando:
- Código implementado e funcional
- Responsividade verificada (mobile, tablet e desktop)
- Code review feito por ao menos um outro desenvolvedor
- Sem erros de console no navegador
- Compatível com Chrome, Firefox e Edge
- Merge realizado via Pull Request na branch correta
- Funcionalidade aprovada pelo PO na Sprint Review

================================================================
8. STACK TECNOLÓGICA
================================================================

HTML5      | Estrutura e semântica das páginas      | Fase atual
CSS3       | Estilização, layout e responsividade    | Fase atual
React      | Componentização e interatividade        | Fase futura
Git/GitHub | Versionamento e colaboração             | Desde o início

================================================================
9. FLUXO DE TRABALHO GIT
================================================================

Branches:
  main          — produção (código estável)
  develop       — integração das features
  feature/nome  — novas funcionalidades
  fix/nome      — correção de bugs
  docs/nome     — atualizações de documentação

Conventional Commits:
  feat:     adiciona nova funcionalidade
  fix:      corrige um bug
  docs:     atualiza documentação
  style:    ajustes de estilo sem impacto em lógica
  refactor: refatoração de código

Fluxo de uma tarefa:
  1. Criar branch a partir de develop
  2. Desenvolver e commitar com mensagens descritivas
  3. Abrir Pull Request para develop
  4. Code review por outro desenvolvedor
  5. Merge aprovado pelo Scrum Master ou Dev responsável
  6. Ao final da sprint, develop é mergeado em main

================================================================
10. CERIMÔNIAS SCRUM
================================================================

Cerimônia            | Frequência        | Duração | Participantes
---------------------|-------------------|---------|-------------------
Sprint Planning      | Segunda (início)  | até 2h  | Todo o time
Daily Scrum          | Terça a Quinta    | 15 min  | Devs + Scrum Master
Sprint Review        | Sexta (final)     | até 1h  | Todo o time + PO
Sprint Retrospective | Sexta (pós-review)| até 1h  | Todo o time

================================================================
Documentação mantida pela equipe — Projeto ACBrasil | Atualizada a cada sprint
================================================================
