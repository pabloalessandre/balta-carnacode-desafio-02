![banner-carnacode](https://github.com/balta-io/carnacode-balta-2024-desafio-01/assets/965305/b8cc442c-d64f-4dd1-9414-7fc896b47183)

# CarnaCode 2024 - Desafio 2
O CarnaCode é um evento online e gratuito que acontece nos dias 10, 11, 12 e 13 de Fevereiro, onde você terá a oportunidade de codificar uma aplicação Web (Blazor + PWA) completa, do começo ao fim.


👉 https://go.balta.io/carnacode-2024

## Sobre o Desafio

Neste segundo desafio, desenvolvemos uma aplicação completa para calcular o IMC (Índice de Massa Muscular). Aprendemos conceitos como Razor e Blazor, bem como rotas, componentes e outros itens do ASP.NET.

## Assuntos a pesquisar

- Localstorage
- Componentes
- JsInterop
- Data Bindings
- Validação de Formulários
- Child Content

## Desafios

Fácil: Implementar o cálculo do IMC e histórico.
Médio: Salvar as informações no localstorage.
Avançado: Componentizar o cálculo do IMC.

### Tecnologias Utilizadas
* ASP.NET
* Razor
* Blazor

### Ferramentas Utilizadas
Visual Studio

# Recompensa
<img src="https://baltaio.blob.core.windows.net/temp/carnacode-badge-desafio-02.png" alt="CarnaCode 2024 - Segundo Desafio Completo" width="256" />


# Passo a passo do que foi feito no início do projeto
1. Clone do repositório.
2. Adição do arquivo .gitignore.
3. Criação do projeto Blazor: ```dotnet new blazorwasm -o IMC --pwa```
4. Adição das páginas Calculo.razor e Historico.razor.
5. Ajuste no cabeçalho das páginas incluindo ```@page "/"``` e ```@page "/historico"``` respectivamente.
6. Ajuste do cabeçalho de Home.razor para ```@page "/home"``` para que este seja o link dele.
7. Ajuste no menu para incluir as páginas de cálculo e histórico.
