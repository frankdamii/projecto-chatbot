# projecto-chatbot

## Descrição do Projeto

Este projeto é um aplicativo móvel desenvolvido para aprimorar os serviços consulares da Embaixada da Guiné Equatorial em Moçambique. Construído usando o Ionic Framework 7, o aplicativo integra um chatbot assistente virtual chamado Gemoz, alimentado pela API OpenAI. O chatbot auxilia os usuários com consultas relacionadas aos serviços da embaixada, proporcionando um canal de comunicação eficiente e fluido.

## Funcionalidades

- Interface de Chat Intuitiva: Imita aplicativos de chat populares com bolhas de mensagens diferenciadas — respostas do bot à direita e mensagens do usuário à esquerda.
- Saudações Automáticas: O bot cumprimenta automaticamente os usuários ao abrir o chat e os incentiva a apresentar suas perguntas.
- **UI Personalizável**: As respostas do bot aparecem com texto branco em fundo roxo, e as mensagens dos usuários com texto roxo em fundo cinza.
- Funcionalidade de Limpeza de Chat: Um botão responsivo permite que os usuários limpem facilmente o histórico de chat.
- Sistema de Feedback: Coleta classificações dos usuários (0-5 estrelas) e comentários, armazenando-os no Firebase para análise e melhoria contínua do desempenho do chatbot.
- Alternância de Mostrar Mais/Menos: Melhora a experiência do usuário, permitindo visualizar conteúdo estendido dentro do aplicativo.

### Tecnologias Utilizadas

- Ionic Framework 7: Fornece a base para um aplicativo móvel robusto e multiplataforma.
- Angular: Utilizado juntamente com o Ionic para o desenvolvimento front-end, garantindo uma interface de usuário suave e responsiva.
- API OpenAI: Alimenta o processamento de linguagem natural do chatbot, permitindo que ele compreenda e responda às consultas dos usuários com precisão.
- Firebase: Gerencia os dados de feedback dos usuários, permitindo a coleta e análise das interações para refinar a eficácia do chatbot.

## Configuração de Desenvolvimento

1. Clonar o Repositório:
    ```sh
    git clone https://github.com/frankdamii/projecto-chatbot.git
    cd projecto-chatbot
    ```

2. Instalar Dependências:
    ```sh
    npm install
    ```

3. Configurar o Firebase: Adicione suas credenciais do Firebase ao arquivo `firebase.service.ts`.

4. Executar o Aplicativo:
    ```sh
    ionic serve
    ```

## Contribuições

Contribuições são bem-vindas! Por favor, faça um fork do repositório e envie um pull request com suas mudanças. Certifique-se de que seu código segue o estilo estabelecido e inclui testes relevantes.


---
