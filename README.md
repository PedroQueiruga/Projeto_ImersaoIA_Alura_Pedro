# Projeto Imersão IA Alura: Criando seu Texto de Divulgação Científica

## Descrição

Neste projeto descobrir o poder dos sistemas multiagentes de IA. Ao receber um tópico do usuário, o sistema vai iniciar uma investigação profunda na web para identificar as descobertas mais recentes e relevantes na área. Para isso, irá entrar tanto em sites se notícias, quanto artigos, tendo foco sempre em encontrar o artigo original de uma determinada publicação. Os agentes vão atuar filtrando as informações relevantes sobre os resultados recentes nas diversas áreas do conhecimento e posteriormente produzindo um texto de divulgação científica que não apenas resume os achados, mas também eexplica sua importância e contexto. Esta ferramenta busca produzir um texto acessível até para quem não tem um conhecimento aprofundado na área, transformando informações complexas em conteúdo compreensível para um público amplo. Além disso, ela é muito útil para quem busca entender o "estado da arte" em uma área específica ou para auxiliar na criação de conteúdo educadional e informativo.

## Agentes

O projeto é dividido em três agentes principais:

1.  **Agente Pesquisador:** Responsável por pesquisar o tópico, encontrar artigos ou notícias relevantes (até 5) e extrair informações chave como título, autores, instituição, ano, resumo e link.
2.  **Agente Simplificador e Interpretador:** Processa as informações do agente pesquisador, simplificando o conteúdo técnico para um público amplo e estruturando as informações de cada fonte nos seguintes pontos: O que é, como foi feito, o que descobriram, porque é importante, link de acesso original, quem descobriu, instituição de ensino, ano de publicação.
3.  **Agente Gerador de Texto de Divulgação Científica:** Compila as informações simplificadas em um texto coeso e envolvente, formatado para publicação em blogs ou revistas de divulgação científica.

## Estrutura do Código

O código está organizado em seções, para facilitar o entendimento do usuário, do que está sendo realizado a cada passo.

*   **Sessão 1: Configurações Iniciais:** Instalação de bibliotecas, configuração da chave de API e SDK, importação de ferramentas auxiliares.
*   **Sessão 2: Definindo os Agentes:** Definição das funções para cada um dos três agentes (`agente_pesquisador`, `agente_simplificador`, `agente_gerador`) e suas instruções.
*   **Sessão 3: Resultados:** Lógica principal para obter o tópico do usuário, chamar os agentes em sequência e exibir os resultados.

## Configuração

1.  **Chave de API do Google AI:** Configure sua chave de acesso pessoal para acessar os serviços do Google AI. Você precisará armazená sua chave de API como um segredo no Google Colab com o nome `GOOGLE_API_KEY`. Para fazer isso basta abrir o google colab e no botão de chave do lado esquerdo da tela clicar em chaves da Gemini e importar do google IA estúdio. 
2.  **Configuração da SDK do Gemini:** O código configura a SDK do Gemini com o modelo `gemini-2.0-flash`.

## Como Usar

1. Clone ou baixe o notebook `.ipynb`.
2. Abra o notebook no Google Colab.
3. Garanta ter sua `GOOGLE_API_KEY` configurada como um segredo no Colab.
4. Execute todas as células do notebook
5. Quando solicitado ao final, digite o tópico que você deseja pesquisar na entrada.
6. O sistema de agentes irá processar o tópico e gerar o texto de divulgação científica.

## Requisitos

*   Conta Google para usar o Google Colab e gerar uma chave de API do Google AI.
*   Acesso à internet.

## Agradecimentos

*  A criação deste notebook só foi possível devido ao curso imersão IA Alura 3° Edição, onde os conceitos básicos por trás da inteligencia artificial e o uso de agentes foram trabalhados de forma excelente.

## Autor

Pedro Gonçalves Queiruga
