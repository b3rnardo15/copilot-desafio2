# Copiloto Personalizado com Microsoft Copilot Studio

## Descrição do Projeto

Este repositório contém o resumo dos aprendizados e as implementações realizadas na criação de um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio. O objetivo deste projeto é demonstrar o conhecimento adquirido na criação e personalização de um copiloto, seguindo as boas práticas e explorando os recursos da plataforma.

## Minhas Contribuições e Implementações

### Nome do Copiloto

O Copiloto criado para este desafio foi nomeado: `dio_copilot_challenge`.

### Configuração do Agente

*   **Tipo:** Agente
*   **Orquestração:** Utiliza IA Generativa para determinar a melhor forma de responder aos usuários e eventos.
*   **Modelo de Agente:** GPT-4o (Produção).

### Objetivo Principal

O principal objetivo deste Copiloto é fornecer informações claras e concisas sobre o Microsoft Copilot Studio e suas funcionalidades, conforme configurado nos tópicos e fontes de conhecimento.

### Tom de Voz

O Copiloto foi configurado para ter um tom de voz **Formal, objetivo e prestativo**.

### Diretrizes de Resposta

As seguintes diretrizes foram implementadas para guiar o comportamento do Copiloto:

1.  Priorizar respostas baseadas nos tópicos configurados.
2.  Utilizar informações das fontes de conhecimento conectadas (IA Generativa) para fornecer respostas relevantes quando a pergunta não for coberta por um tópico específico.
3.  Em caso de não compreensão (fallback), guiar o usuário para opções claras ou para reformular a pergunta, oferecendo ajuda de forma proativa.
4.  Evitar respostas vagas ou que possam gerar confusão. Se a informação não for precisa, indicar que não possui a informação e sugerir alternativas.

### Fontes de Conhecimento

Uma fonte de conhecimento foi adicionada para informar e aprimorar as respostas geradas pela IA:

*   `https://learn.microsoft.com/pt-br/microsoft-copilot-studio/`

### Tópicos Criados/Personalizados

Foram criados ou personalizados os seguintes tópicos:

*   `Frases de Gatilho`
*   `Horário de Atendimento`

## Entendimento do Desafio (Resumo da Atividade)

### 1. Criar um Copiloto em Branco

*   **Acesso:** O processo se inicia acessando o portal do Microsoft Copilot Studio.
*   **Criação:** É possível criar um copiloto do zero ("em branco") ou utilizar modelos pré-existentes.
*   **Configuração Inicial:** Na configuração inicial, definimos um nome para o copiloto, o idioma principal e conectamos a uma fonte de conhecimento (site, arquivos ou SharePoint) para permitir que a IA generativa responda a perguntas básicas.

### 2. Customizar um Tópico

*   **O que é um Tópico:** Um tópico representa um fluxo de conversa específico, ativado por "frases de gatilho".
*   **Tela de Criação:** A tela de criação visual permite adicionar nós de conversa para:
    *   **Enviar Mensagens:** Exibir textos, imagens e cartões adaptáveis.
    *   **Fazer Perguntas:** Coletar informações do usuário.
    *   **Adicionar Condições:** Criar ramificações na conversa com base nas respostas do usuário.
    *   **Chamar Ações:** Integrar com outras ferramentas, como o Power Automate.

### 3. Personalizar uma Mensagem de Erro de Tópico

*   **Tópico de Fallback:** O tópico de sistema "Fallback" é acionado quando o copiloto não entende a pergunta do usuário.
*   **Customização:** É possível editar este tópico para personalizar a mensagem de erro, oferecendo sugestões, contando tentativas ou escalando para um atendente humano.

### 4. Aumentar/Diminuir a Qualidade da Resposta com GenAI

*   **Respostas Generativas (Conversation Boosting):** Permite que o copiloto responda a perguntas mesmo sem um tópico específico, buscando a resposta na fonte de conhecimento fornecida.
*   **Ajuste de Qualidade (Content Moderation):** É possível ajustar o nível de moderação de conteúdo (Baixo, Médio, Alto) para equilibrar a quantidade e a precisão das respostas.
*   **Instruções Personalizadas (Custom Instructions):** Permitem guiar o comportamento da IA, definindo o tom da conversa e a estrutura das respostas.

## Conclusão

Este projeto permitiu um aprofundamento prático no Microsoft Copilot Studio, desde a criação de um copiloto básico até a personalização avançada de fluxos de conversa e o uso de IA generativa para aprimorar a experiência do usuário.

