# LobCypressTests

Repositório contendo a suíte de testes automatizados com Cypress para o projeto **Lob**.

## Visão Geral

Este projeto utiliza o framework de testes E2E (End-to-End) Cypress para verificar o comportamento e a funcionalidade da aplicação **Lob**. A suíte de testes foi projetada para ser robusta, confiável e eficiente, garantindo que as funcionalidades essenciais do projeto sejam testadas automaticamente.

## Estrutura do Projeto

- **cypress/**: Contém a pasta com todos os testes, fixtures e comandos customizados.
  - **fixtures/**: Armazena arquivos de dados para uso nos testes.
  - **integration/**: Contém os arquivos dos testes automatizados.
  - **plugins/**: Scripts de configuração e customizações do Cypress.
  - **support/**: Funções e comandos globais que podem ser usados por todos os testes.
- **cypress.json**: Arquivo de configuração do Cypress.
- **README.md**: Documentação do projeto.

## Requisitos

- Node.js (versão 14 ou superior)
- Cypress (versão 12 ou superior)

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/GbrlSouza/LobCypressTests.git
   ```

2. Acesse o diretório do projeto:

   ```bash
   cd LobCypressTests
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

## Executando os Testes

- Para abrir o Cypress em modo interativo:

  ```bash
  npx cypress open
  ```

- Para executar os testes no modo headless:

  ```bash
  npx cypress run
  ```

## Configuração

- As configurações de ambiente podem ser ajustadas no arquivo `cypress.json`.
- Adicione credenciais sensíveis ou variáveis de ambiente de forma segura, se necessário.

## Estrutura de Testes

- **Testes de Login**: Verificam a funcionalidade de autenticação do usuário.
- **Testes de UI**: Validam elementos da interface, como botões, formulários e links.
- **Testes de Funcionalidade**: Checam funcionalidades críticas, como envio de formulários e navegação.

## Boas Práticas

- Sempre mantenha os testes atualizados com as funcionalidades da aplicação.
- Use comandos customizados no Cypress para evitar repetição de código.
- Execute os testes em diferentes navegadores e ambientes para melhor cobertura.

## Contribuição

1. Faça um fork do repositório.
2. Crie uma branch para sua feature/bug fix (`git checkout -b minha-branch`).
3. Commit suas mudanças (`git commit -m 'Minha feature incrível'`).
4. Dê push na branch (`git push origin minha-branch`).
5. Abra um Pull Request.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

---

Sinta-se à vontade para contribuir ou abrir issues caso encontre algum problema ou tenha sugestões de melhoria!
