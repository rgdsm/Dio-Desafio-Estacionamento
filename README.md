# Projeto de Estacionamento

Este projeto é um sistema de gerenciamento de estacionamento desenvolvido em C# como parte do meu aprendizado na linguagem durante o bootcamp "XP Inc. - Full Stack Developer" oferecido pela plataforma DIO.

## Descrição do Projeto

O sistema de estacionamento tem como objetivo permitir o gerenciamento simples de veículos em um estacionamento. Ele oferece funcionalidades para registrar a entrada e saída de veículos, calcular o custo do estacionamento com base no tempo de permanência, e listar todos os veículos atualmente estacionados.

## Funcionalidades

O sistema possui as seguintes funcionalidades principais:

- **Cadastrar Veículo**: Permite ao usuário adicionar um novo veículo ao estacionamento digitando sua placa.
- **Remover Veículo**: Permite remover um veículo estacionado ao informar sua placa e o tempo que permaneceu estacionado, calculando o valor total a ser cobrado.
- **Listar Veículos**: Exibe uma lista de todos os veículos que estão atualmente no estacionamento.
- **Encerrar Sistema**: Opção para encerrar a execução do sistema.

## Como Usar

### Pré-requisitos

Para executar este projeto, você precisa ter o .NET SDK instalado na sua máquina. Você pode baixá-lo no [site oficial do .NET](https://dotnet.microsoft.com/download).

### Instruções

1. **Clone o Repositório**: Clone o repositório para sua máquina local usando o comando:

   ```bash
   git clone https://github.com/rgdsm/Dio-Desafio-Estacionamento.git
   ```

2. **Navegue até o Diretório do Projeto**: Use o terminal ou prompt de comando para ir até o diretório do projeto:

   ```bash
   cd Dio-Desafio-Estacionamento
   ```

3. **Execute o Projeto**: Use o seguinte comando para compilar e executar o projeto:

   ```bash
   dotnet run
   ```

4. **Interaja com o Sistema**: Após executar, siga as instruções exibidas no console para interagir com o sistema de estacionamento.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **Models/Estacionamento.cs**: Contém a classe `Estacionamento` que implementa a lógica de gerenciamento dos veículos, incluindo métodos para adicionar, remover e listar veículos.
- **Program.cs**: Contém o ponto de entrada do aplicativo, gerenciando a interação do usuário através de um menu de opções.

## Aprendizado e Tecnologias

Durante o desenvolvimento deste projeto, aprendi e utilizei as seguintes tecnologias e conceitos:

- **C# e .NET Core**: Linguagem de programação C# para desenvolver aplicações robustas e escaláveis.
- **Manipulação de Listas**: Uso de listas genéricas para armazenar e gerenciar os dados dos veículos.
- **Interação com o Console**: Criar uma interface simples baseada em console para interação com o usuário.
- **Tratamento de Erros e Validações**: Garantir que as entradas do usuário sejam válidas e lidar com possíveis erros de execução.

## Contribuição

Se você deseja contribuir para este projeto, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma branch para suas alterações (`git checkout -b minha-feature`).
3. Faça commit das suas mudanças (`git commit -m 'Adicionando nova feature'`).
4. Faça push para a branch (`git push origin minha-feature`).
5. Abra um Pull Request.

## Contato

Se você tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato:

- GitHub: [@rgdsm](https://github.com/rgdsm)
- Plataforma DIO: [XP Inc. - Full Stack Developer](https://web.dio.me/)
```
