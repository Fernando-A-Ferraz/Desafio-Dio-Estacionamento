# DIO - Trilha .NET - Fundamentos

Este projeto foi proposto como parte de um desafio de código na plataforma [DIO](https://www.dio.me/). Ele simula a gestão de um estacionamento, aplicando conceitos fundamentais do .NET.

## Execução do Projeto

A classe principal contém três variáveis:

- **precoInicial**: (tipo decimal) Define o preço base para estacionar o veículo.
- **precoPorHora**: (tipo decimal) Define o preço cobrado por hora de permanência no estacionamento.
- **veiculos**: (tipo List<string>) Armazena uma coleção de veículos atualmente estacionados, representada apenas pelas placas dos veículos.

### Métodos da Classe

1. **AdicionarVeiculo**  
   Método responsável por receber a placa digitada pelo usuário e adicioná-la à lista de veículos estacionados (**veiculos**).

2. **RemoverVeiculo**  
   Método que verifica se um veículo com a placa informada está estacionado. Caso positivo, solicita ao usuário o tempo (em horas) que o veículo permaneceu no estacionamento e calcula o valor total a ser pago utilizando a fórmula:  
   precoInicial + (precoPorHora * horas).  
   Em seguida, exibe o valor para o usuário e remove o veículo da lista.

3. **ListarVeiculos**  
   Lista todos os veículos atualmente estacionados. Caso não haja nenhum veículo, exibe a mensagem:  
   "Não há veículos estacionados".

## Menu Interativo

O projeto conta com um menu que permite as seguintes ações:

1. **Cadastrar veículo**
2. **Remover veículo**
3. **Listar veículos**
4. **Encerrar**

---

Esse projeto exemplifica o uso de listas, entrada e saída de dados, e estruturas de controle em um cenário prático de gerenciamento de estacionamento.

