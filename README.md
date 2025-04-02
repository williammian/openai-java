# Integração Java com OpenAI

Este projeto demonstra como integrar uma aplicação Java com a API da OpenAI, abordando conceitos como engenharia de prompts, templates de prompts, requisições de conclusão de chat, contagem de tokens e tratamento de erros.

## Funcionalidades Principais

- **Engenharia de Prompts**: Criação e otimização de prompts para interagir de forma eficaz com a API da OpenAI.
- **Templates de Prompts**: Utilização de templates para estruturar prompts reutilizáveis e consistentes.
- **Requisições de Conclusão de Chat**: Implementação de chamadas à API para obter respostas de modelos de linguagem da OpenAI.
- **Contador de Tokens**: Mecanismo para contar o número de tokens em prompts e respostas, auxiliando no gerenciamento de limites da API.
- **Tratamento de Erros**: Estratégias para lidar com possíveis erros e exceções durante a comunicação com a API.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal do projeto.
- **Maven**: Gerenciador de dependências e automação de build.
- **API da OpenAI**: Interface utilizada para interagir com os modelos de linguagem da OpenAI.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **src/main**: Contém o código-fonte principal da aplicação, incluindo classes para integração com a API da OpenAI e implementação das funcionalidades mencionadas.
- **pom.xml**: Arquivo de configuração do Maven, especificando as dependências e plugins necessários para o projeto.

## Pré-requisitos

Antes de executar o projeto, certifique-se de que os seguintes requisitos estão atendidos:

- **Java 11 ou superior**: Versão necessária para compilar e executar o código.
- **Maven**: Ferramenta para gerenciamento de dependências e build.
- **Chave de API da OpenAI**: É necessário obter uma chave de API válida da OpenAI para acessar os serviços.

## Como Executar o Projeto

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/williammian/openai-java.git
   ```

2. **Configurar a Chave de API**: Adicione sua chave de API da OpenAI ao projeto, seja por meio de variáveis de ambiente ou arquivos de configuração, conforme implementado no código.

3. **Compilar e Executar**: Utilize o Maven para compilar e executar o projeto:
   ```bash
   mvn clean install
   mvn exec:java -Dexec.mainClass="com.seuprojeto.Main"
   ```

## Licença

Este projeto está licenciado sob a licença MIT.

