🚗 Sistema de Estacionamento - Desafio

Este projeto é uma aplicação de console em C# que simula um sistema simples de estacionamento.
O objetivo é praticar conceitos de programação orientada a objetos (POO), manipulação de listas e interação com o usuário.

📌 Funcionalidades

O sistema permite:

Cadastrar veículo – Adiciona a placa de um veículo ao estacionamento.

Remover veículo – Calcula o valor a ser pago com base no preço inicial + preço por hora.

Listar veículos – Mostra todos os veículos atualmente estacionados.

Encerrar programa – Fecha o sistema.

🛠 Estrutura do Código

O projeto contém dois arquivos principais:

Program.cs – Controla o fluxo principal do sistema e o menu de opções.

Estacionamento.cs – Contém a classe Estacionamento, responsável pelas regras de negócio, como adicionar, remover e listar veículos.

🚀 Como executar o projeto
✅ Pré-requisitos

.NET SDK
 instalado na sua máquina.

Um editor como Visual Studio ou Visual Studio Code.

▶️ Rodando o projeto

Clone este repositório:

git clone https://github.com/Alan-RiBas/desafio-net-estacionamento


Acesse a pasta do projeto:

cd desafio-estacionamento


Execute o programa:

dotnet run

🖼 Demonstração do Uso
1️⃣ Início

Ao iniciar, o sistema pedirá os valores de preço inicial e preço por hora:

Seja bem vindo ao sistema de estacionamento!
Digite o preço inicial:
5
Agora digite o preço por hora:
2

2️⃣ Menu principal
Digite a sua opção:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar

3️⃣ Cadastrando veículo
Digite a placa do veículo para estacionar:
ABC-1234

4️⃣ Listando veículos
Os veículos estacionados são:
ABC-1234

5️⃣ Removendo veículo
Digite a placa do veículo para remover:
ABC-1234
Digite a quantidade de horas que o veículo permaneceu estacionado:
3
O veículo ABC-1234 foi removido e o preço total foi de: R$ 11

🎯 Objetivo do Desafio

Este desafio foi proposto para exercitar:

Lógica de programação em C#.

Estruturas de repetição e condicionais.

Manipulação de listas (List<string>).

Conceitos de POO (classes, métodos e encapsulamento).

✨ Melhorias Futuras

 Persistir dados em arquivo ou banco de dados.

 Validar formato da placa.

 Criar testes automatizados.

 Melhorar a interface com cores e menus mais interativos.

👨‍💻 Autor

Projeto para fins de aprendizado e demonstração de habilidades técnicas.