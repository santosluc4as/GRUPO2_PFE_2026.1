# Documento de Visão - Modernização do Site ACBrasil

## Sumário

- [1. Introdução](#1-introdução)
  - [1.1 Propósito](#11-propósito)
  - [1.2 Escopo](#12-escopo)
  - [1.3 Definições, Acrônimos e Abreviações](#13-definições-acrônimos-e-abreviações)
- [2. Posicionamento](#2-posicionamento)
  - [2.1 Oportunidade de Negócio](#21-oportunidade-de-negócio)
  - [2.2 Descrição do Problema](#22-descrição-do-problema)
  - [2.3 Declaração de Posicionamento](#23-declaração-de-posicionamento)
- [3. Descrição dos Envolvidos e Usuários](#3-descrição-dos-envolvidos-e-usuários)
  - [3.1 Resumo dos Envolvidos](#31-resumo-dos-envolvidos)
  - [3.2 Resumo dos Usuários](#32-resumo-dos-usuários)
- [4. Visão Geral do Produto](#4-visão-geral-do-produto)
  - [4.1 Recursos Principais](#41-recursos-principais)
  - [4.2 Restrições do Produto](#42-restrições-do-produto)
- [5. Requisitos de Alto Nível](#5-requisitos-de-alto-nível)
  - [5.1 Requisitos Funcionais](#51-requisitos-funcionais)
  - [5.2 Requisitos Não Funcionais](#52-requisitos-não-funcionais)
- [6. Restrições e Premissas do Projeto](#6-restrições-e-premissas-do-projeto)
  - [6.1 Restrições do Projeto](#61-restrições-do-projeto)
  - [6.2 Premissas](#62-premissas)
- [7. Riscos e Dependências](#7-riscos-e-dependências)
  - [7.1 Riscos](#71-riscos)
  - [7.2 Dependências](#72-dependências)

---

## 1. Introdução

### 1.1 Propósito

Este documento define o planejamento e a visão da nossa equipe para a recriação do site da Associação de Conselheiros do Brasil (ACB). 

Nosso objetivo principal é desenvolver uma nova versão do portal para corrigir os atuais erros de navegação e modernizar a interface. Queremos entregar um site mais intuitivo, ajudando a associação a divulgar suas notícias, artigos e, principalmente, facilitar a entrada de novos associados.

### 1.2 Escopo

O novo website da ACB consistirá em uma Multi-Page Application (MPA) responsiva, permitindo que os usuários leiam artigos, assinem a newsletter, entrem em contato, acompanhem eventos e associem-se.

O desenvolvimento ocorrerá de forma iterativa em duas fases de avaliação: a primeira entrega será estruturada como uma Multi-Page Application (MPA) utilizando Vanilla JS. Na fase seguinte, o sistema passará por uma refatoração arquitetural, evoluindo para uma Single Page Application (SPA) com a biblioteca React.

### 1.3 Definições, Acrônimos e Abreviações

**ACB:** Associação de Conselheiros do Brasil

**UX:** User Experience (Experiência do Usuário)

**MPA e SPA:** Multi-Page Application (Aplicação de Múltiplas Páginas) e Single Page Application (Aplicação de Página Única)

**SPA:** Single Page Application (Aplicação de Página Única)

**RSS:** Really Simple Syndication (formato de distribuição de conteúdo/notícias em tempo real)

**CMS:** Content Management System (Sistema de Gerenciamento de Conteúdo)

**ESG:** Environmental, Social and Governance (Ambiental, Social e Governança)

**PMEs:** Pequenas e Médias Empresas

**API:** Application Programming Interface (Interface de Programação de Aplicações)

**ENDPOINTS:** endereço específico da Web onde uma API recebe requisições para acessar ou manipular um recurso

**VANILLA JS:** termo utilizado para referir-se à linguagem de programação JavaScript pura em conjunto com HTML e CSS, sem a utilização de frameworks ou bibliotecas adicionais.

**REACT:** Biblioteca JavaScript baseada em componentes, utilizada neste projeto para construir a interface de usuário (UI) e viabilizar a arquitetura de Aplicação de Página Única (SPA).

---

## 2. Posicionamento

### 2.1 Oportunidade de Negócio

A ACB precisa passar credibilidade para atrair conselheiros e educar empresas sobre governança (ESG). O site atual não atende bem a essa necessidade. O novo projeto surge como uma oportunidade de entregar um ambiente digital que realmente funcione e passe confiança para os visitantes.


### 2.2 Descrição do Problema

Analisando o site atual (acbrasil.org.br/cms/), nossa equipe identificou vários problemas técnicos e visuais que atrapalham o usuário:

- O layout não é responsivo e tem links que não funcionam.
- Códigos do painel administrativo vazando na tela (ex: textos como `[acb-contatos]` aparecendo pro usuário).
- Erros graves de sobreposição, como o ícone do WhatsApp ficando em cima do botão de Captcha, o que impede as pessoas de enviarem mensagens.
- Navegação confusa no cabeçalho e excesso de informações no rodapé.


### 2.3 Declaração de Posicionamento

O novo website da ACB é um portal institucional para executivos e empresários que buscam conhecimento e networking em governança corporativa.

Diferente do site atual, ele deve oferecer:

- Experiência otimizada
- Navegação simplificada
- Design acessível
- Integração automatizada de notícias e artigos
- Fluxo de associação direto e funcional

---

## 3. Descrição dos Envolvidos e Usuários

### 3.1 Resumo dos Envolvidos

**Reitor (Cliente e Representante da ACBrasil no projeto):** Valida a identidade visual, aprova as páginas estruturais e fornece os endpoints da API.

**Equipe de Desenvolvimento (Alunos):** Responsáveis pela documentação, prototipação no Figma e o desenvolvimento Front-end do website.

**Thiago Marcondes Santos (Professor):** Responsável pela avaliação do projeto, garantindo o cumprimento do cronograma acadêmico.

### 3.2 Resumo dos Usuários

**Conselheiros Executivos (Potenciais Associados):** Profissionais experientes interessados em se voluntariar para influenciar e transformar positivamente a realidade das empresas brasileiras através de boas práticas de governança, necessitando para isso de um funil ágil de cadastro e acesso rápido ao Código de Conduta da instituição.

**Empresários e PMEs:** Buscam letramento em governança, agenda de eventos, notícias e artigos do blog.

**Público Geral:** Procuram informações institucionais, contatos e redes sociais da associação.

---

## 4. Visão Geral do Produto

### 4.1 Recursos Principais

- **Blog:** Ferramenta dedicada para a publicação e leitura de artigos focados em governança e educação corporativa.
- **Newsletter:** Área dedicada no próprio site que atua como um acervo digital, onde os usuários podem acessar e ler diretamente os boletins informativos (clipping) e iniciativas da associação, sem depender do envio tradicional por e-mail.
- **Monitoração Econômica em tempo real (bolsa brasileira):** Quadro dinâmico integrado via API (feed RSS) para exibir automaticamente as últimas movimentações econômicas e notícias do mercado na página inicial.
- **Eventos Recentes:** Área dedicada para destacar a agenda de próximos eventos, encontros e webinars realizados ou apoiados pela entidade.

### 4.2 Restrições do Produto

**Visuais:** O design de interface deve, obrigatoriamente, seguir a teoria das cores institucional (branco, azul, amarelo e cinza).

**Tecnológicas:** Desenvolvimento puramente Front-end. O sistema dependerá do fornecimento do endpoint da API de Notícias (RSS) por parte do cliente para exibição dos dados, visto que a equipe não desenvolverá a infraestrutura de Back-end. A implantação final (deploy) do projeto deverá ser realizada obrigatoriamente na plataforma Vercel.

---

## 5. Requisitos de Alto Nível

### 5.1 Requisitos Funcionais

- **Recriação do Sistema e Páginas Principais:** O sistema deve conter as páginas e áreas essenciais da ACB para conseguir novos associados e para divulgar notícias e artigos.
- **Correção da Interface de Navegação:** O Header deve ter suas cores revisadas, opções englobadas (ex: trocar "Quem somos e o que fazemos" por "Quem somos?") e o "menu associado" bugado deve ser retirado.
- **Correção de Sobreposições e Formulários:** O ícone do WhatsApp não deve se sobrepor à verificação de segurança (Captcha), e o ícone do Captcha deve ser realocado para o Footer.
- **Busca e Links:** O ícone de busca deve conter recomendação de texto (placeholder) para orientar o usuário sobre o tipo de informação aceita, e todos os links quebrados ou inoperantes do site atual (como o ícone de "Home" do Footer) devem ser corrigidos.
- **Simplificação de Conteúdo:** As seções "Artigos Recentes", "Em Destaque" e o próprio Footer devem ser simplificados para evitar o excesso de informações, além da atualização da data dos direitos autorais.

### 5.2 Requisitos Não Funcionais

- **Plataforma e Tecnologias (Fases de Entrega):** O projeto inicial deve ser desenvolvido utilizando HTML, CSS e JavaScript Vanilla. A versão final deve ser integralmente construída utilizando a biblioteca React.
- **Acessibilidade e Usabilidade:** O sistema deve propor melhorias visuais e técnicas corrigindo os problemas de acessibilidade da versão anterior para não comprometer a qualidade da navegação.
- **Versionamento e Publicação:** O versionamento do código deve ser feito no GitHub. A publicação (deploy) da versão em Vanilla deve ocorrer pelo próprio GitHub, e o deploy da versão final em React deve ser feito no Vercel.

---

## 6. Restrições e Premissas do Projeto

### 6.1 Restrições do Projeto

- **Cronograma e Entregas (Calendário da Ibmec):**
  - O protótipo estrutural no Figma e os documentos devem ser entregues até o dia 17/04/2026.
  - A primeira entrega funcional desenvolvida em Vanilla (HTML/CSS/JS) deve ocorrer entre os dias 08/05/2026 e 22/05/2026.
  - A entrega da versão final desenvolvida em React deve ocorrer impreterivelmente no dia 12/06/2026.
- **Ambiente e Equipe Acadêmica:** O projeto é restrito ao ambiente acadêmico da Ibmec, e seu desenvolvimento técnico deve ser feito somente pelos alunos.
- **Metodologia:** O desenvolvimento do projeto está restrito ao acompanhamento e estruturação em Sprints ditados pelo Scrum.

### 6.2 Premissas

- **Gratuidade:** Assume-se que a infraestrutura completa do ciclo de vida do projeto (ferramentas de design no Figma, versionamento no GitHub, organização no Jira/Trello e a hospedagem na Vercel) continuará sendo fornecida de forma gratuita.
- **Disponibilidade da Equipe:** Assume-se que a equipe distribuirá suas tarefas de desenvolvimento conforme organizado nas Sprints (Scrum) e garantirá as entregas parciais dentro dos prazos da disciplina.

---

## 7. Riscos e Dependências

### 7.1 Riscos
Mapeamos os seguintes riscos que podem atrapalhar nosso projeto:

- **Dificuldade técnica com o React:** A transição do JavaScript puro para o React em um espaço curto de tempo (entre maio e junho) é arriscada. A curva de aprendizado pode atrasar a entrega final.
- **Bloqueio do Cliente:** Dependemos da resposta rápida da ACB para nos fornecer a API de notícias (RSS) e os materiais visuais. Se eles demorarem, o desenvolvimento da página inicial vai ficar travado.
- **Falta de foco da equipe:** Cada membro mapeou muitas melhorias diferentes. O risco é tentarmos fazer tudo ao mesmo tempo (inchaço de escopo) e acabarmos não entregando o básico bem feito. O Scrum Master precisará priorizar as tarefas com rigor.
- **Problemas de Versionamento:** Erros na hora de fazer o "merge" do código no GitHub podem quebrar o site perto dos dias de apresentação.

### 7.2 Dependências

- O andamento da etapa de programação depende diretamente de terminarmos e aprovarmos o design no Figma no prazo certo (17/04).
- Dependemos da estabilidade dos servidores gratuitos do GitHub e da Vercel para que o site fique no ar durante as avaliações.
- O sucesso da equipe depende da comunicação constante nas Sprints e do acompanhamento do professor para tirar dúvidas técnicas ao longo do caminho.