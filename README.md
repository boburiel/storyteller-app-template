
# Storyteller App Template

Este repositório contém a estrutura inicial para o desenvolvimento de um aplicativo mobile para jogos de *storyteller*. O objetivo é fornecer uma base com a separação de backend, frontend (mobile) e uma organização de pastas adequada para que você possa iniciar rapidamente o desenvolvimento.

## Estrutura do Repositório

- `mobile/`: Contém o código do aplicativo mobile, desenvolvido com React Native.
  - `src/`: Diretório com todos os arquivos de código.
    - `components/`: Componentes reutilizáveis do aplicativo.
    - `screens/`: Telas (views) do aplicativo.
    - `navigation/`: Configurações de navegação.
    - `services/`: Serviços como comunicação com API.
    - `utils/`: Funções utilitárias.
- `server/`: Backend da aplicação, construído com Node.js e Express.
  - `src/`: Código do backend.
    - `controllers/`: Lógica dos controladores.
    - `models/`: Modelos de dados.
    - `routes/`: Definição das rotas da API.
    - `middlewares/`: Middlewares para validação e autenticação.
    - `config/`: Configurações do servidor.
- `docs/`: Documentação adicional, como o formato de fichas de personagens.
- `postman/`: Coleção de testes para a API usando Postman.
- `.gitignore`: Arquivos a serem ignorados pelo Git.
- `LICENSE`: Licença MIT para distribuição do código.
- `README.md`: Este arquivo, que contém informações sobre o projeto.

## Como Usar

### Backend

1. Clone o repositório e acesse a pasta `server/`.
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o servidor:
   ```bash
   npm start
   ```

### Frontend

1. Clone o repositório e acesse a pasta `mobile/`.
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Execute o aplicativo com Expo:
   ```bash
   expo start
   ```

## Contribuições

Se você tiver ideias de melhorias ou quiser contribuir para este projeto, sinta-se à vontade para fazer um *fork* e enviar um *pull request*.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
