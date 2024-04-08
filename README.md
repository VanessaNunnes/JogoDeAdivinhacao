
# Jogo de Adivinhação

## Projeto

Desenvolvido durante o curso Fullstack da [Academia do Programador](https://www.academiadoprogramador.net) 2024

---
## Detalhes

O computador escolherá, de maneira aleatória, um número entre 1 e 20, e o jogador deve chutar um número, até adivinhá-lo.

O jogador poderá escolher entre 3 dificuldades, sendo elas: 
- Fácil = 15 tentativas.
- Médio = 10 tentativas.
- Difícil = 5 tentativas.

A cada tentativa do jogador, o computador irá informar se o número chutado pelo jogador é maior ou menor que o número escolhido por ele.

---
## Entrada

Os jogadores são solicitados a inserir um número por vez através do console. 

---
## Funcionalidades

- __Escolha de Número Secreto__: Um número é escolhido aleatoriamente no início de cada jogo.
- __Dicas__: A cada tentativa do jogador, uma mensagem informando se o número chutado é maior ou menor que o número escolhido aparecerá no console.
- __Contagem de Erros__: O jogo acompanha o número de tentativas restantes do jogador e termina quando o máximo permitido é alcançado.

---
## Requisitos

- .NET SDK (recomendado .NET 8.0 ou superior) para compilação e execução do projeto.
---
## Como Usar

#### Clone o Repositório
```
git clone https://github.com/VanessaNunnes/JogoDeAdivinhacao.git
```

#### Navegue até a pasta raiz da solução
```
cd JogoDeAdivinhacao
```

#### Restaure as dependências
```
dotnet restore
```

#### Navegue até a pasta do projeto
```
cd JogoDeAdivinhacao.ConsoleApp
```

#### Execute o projeto
```
dotnet run
```
