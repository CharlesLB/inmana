<h1 align="center">
    <b>:bar_chart:Inmana:bar_chart:</b> 
</h1>

<p align="center">
  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  </a>
  <a>
  <img alt="Language" src="https://img.shields.io/badge/language-Elixir-brightgreen">
  <img alt="Language" src="https://img.shields.io/badge/language-Phoenix Framework-brightgreen">
  <img alt="Language" src="https://img.shields.io/badge/language-BCrypt-brightgreen">
  <img alt="Language" src="https://img.shields.io/badge/language-Credo-brightgreen">
  <img alt="Language" src="https://img.shields.io/badge/language-ExCoveralls-brightgreen">
  <img alt="Language" src="https://img.shields.io/badge/language-Dotenv-brightgreen">
  <img alt="Language" src="https://img.shields.io/badge/language-Bamboo-brightgreen">


</p>


## :bookmark: Sobre

Inmana é uma API em Elixir desenvolvida na Next Level Week #5. A API consiste em um gerenciador de suprimentos onde você pode cadastrar seu estabelecimento e seu abastecimento e receber emails semanalmente com os suprimentos que estão perto do prazo de validade.

<a id="documentacao"></a>

## :rocket: Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias

- [Elixir](https://elixir-lang.org/)
- [Phoenix Framework](https://www.phoenixframework.org/)
- [Bcrypt](https://hex.pm/packages/bcrypt_elixir)
- [Credo](https://hex.pm/packages/credo)
- [ExCoveralls](https://hex.pm/packages/excoveralls)
- [Dotenv](https://github.com/avdi/dotenv_elixir)
- [Bamboo](https://github.com/thoughtbot/bamboo)

<a id="como-usar"></a>

## :fire: Como usar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Elixir](https://elixir-lang.org/)** no mínimo na versão 1.6 instalado na máquina
  - É **necessário** possuir o **[Credo](https://github.com/rrrene/credo#installation-and-usage)** instalado na máquina
  - É **necessário** possuir o **[Bamboo](https://github.com/thoughtbot/bamboo#installation)**  instalado na máquina
  - É **necessário** possuir o **[Postgree](https://www.postgresql.org/download/)**  instalado na máquina

1. Faça um clone :

```sh
  $ git clone https://github.com/CharlesLB/inmana.git
```

2. Para executar:

```
  #Selecione o arquivo
  $cd ./projeto-desejado
  
  # Instale as dependências
  $ mix deps.get

  # Coloque os dados do seu banco de dados
  SECRET_BASE_KEY = [sua key]
  LIVE_VIEW = [sua key]
  USERNAME = postgree
  PASSWORD = postgree

  # Migre o banco de dados
  $ mix ecto.setup

  # Inicie a aplicação na porta 4000
  $ mix phx.server

```

<a id="como-contribuir"></a>

## :recycle: Como contribuir

- Faça um Fork desse repositório,
- Crie uma branch com a sua feature: `git checkout -b my-feature`
- Commit suas mudanças: `git commit -m 'feat: My new feature'`
- Push a sua branch: `git push origin my-feature`

## :memo: License

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
