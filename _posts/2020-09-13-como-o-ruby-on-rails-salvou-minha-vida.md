---
layout: post
title: Como o Ruby on Rails salvou a minha vida!
image: /img/ruby_on_rails.png
tags: RubyOnRails Palestra
---

É isso mesmo, você não leu errado, como é possível uma framework salvar a vida de alguem :) 

Tive o privilégio de trocar uma ideia com o curso de Sistema de Informações da [Farol - Faculdade de Rolim de Moura <span class="fa fa-external-link"></span>](https://www.farol.edu.br){:target="_blank"} em Rondônia. Nessa palestra além de rever antigos alunos :) apresentei um pouco de como o Ruby on Rails "salvou a minha vida" em meio a um grande CAOS e pra não ficar só em teoria realizamos um projeto, um portal com gráficos demonstrando o total de casos de COVID19 por estado.

O Objetivo da palestra é demonstrar a facilidade que a framework proporciona para um iniciante e ao mesmo tempo entrega algo com qualidade em tempo hábil.

- Confira [aqui <span class="fa fa-external-link"></span>](https://docs.google.com/presentation/d/1GdWnDdULta2EFZANGY_33qgAX-l81Cfm2miBAFSzA60/edit?usp=sharing){:target="_blank"} os slides da apresentação

- Confira o portal online [aqui <span class="fa fa-external-link"></span>](http://covidrailsnoronha.herokuapp.com){:target="_blank"}

# Covid19 Rails

<img src="img/screen_home.png">

## Criar um portal que liste os casos de COVID no Brasil por estados

- Quantidade total de casos

- Quantidade de mortos

- Quantidade de curados

- Quantidade de suspeitos 

- Deverá constar uma interface amigável através de graficos para facilitar a interpretação do usuário.

- Deverá possuir um  controle de usuários ao acessar  a aplicação.

- Realizar o deploy da aplicação para que o cliente possa visualizar o projeto

- Deverá ser criado um repositório do projeto no GITHUB


## Vamos lá

Verifique os requisitos abaixo, fique a vontade para realizar o clone do projeto e realizar suas modificações.

### Pré requisitos

* Ruby 2.5.3

* Rails 6.0.2


Caso não tenha o Rails instalado, só seguir as seguintes dicas: 

* [Ruby on Rails Ubuntu](https://gorails.com/setup/ubuntu/18.04)
* [Ruby on Rails Windows](https://gorails.com/setup/windows/10)
* [Ruby on Rails Mac OS](https://gorails.com/setup/osx/10.15-catalina)

### Setup básico Linux

Após a instalação do Rails, abra o seu terminal e execute os seguintes comandos:

Acessando a sua pasta home
```
cd
```
Clone do projeto no github
```
git clone https://github.com/gitDbits/covid_rails
```
Acesse a pasta covid_rails
```
cd covid_rails
```
Instalado a dependências GEMS
```
bundle install 
```
## Dependências YARN

Execute o comando para o yarn verificar todas as dependências
```
yarn install --check-files
```

## Configurando banco de dados PostgreSQL

Execute o comando para instalar no linux
```
sudo apt install postgresql-11 libpq-dev
```

Vamos criar um usuário sudo para o banco de dados
```
sudo -u postgres createuser covid_rails -s
```

Vamos criar uma senha de acesso para esse usuário
```
sudo -u postgres psql
```
  Após abrir o console do postgre digite \password e informe a senha
  Para sair do console basta digitar \q

Vamos criar o banco de dados, execute o comando
```
rails db:create
rails db:migrate
```
Agora vamos popular o banco de dados com algumas informações testes :)
```
rails db:seed
```

## Acessando o covid_rails

Execute o servidor local
```
rails s
```
Basta cadastrar um usuário e o seu portal está pronto para ser utilizado :)

## Construido com

* [Ruby on Rails](https://rubyonrails.org/) - Imagine what you could build if you learned Ruby on Rails

* [Devise](https://github.com/heartcombo/devise) - Flexible authentication solution for Rails with Warden

* [Pagy](https://github.com/ddnexus/pagy) - The ultimate solution pagination Rails

* [Font Awesome](https://fontawesome.com/) - Library icons CSS

* [Bootstrap](https://getbootstrap.com/) - Framework for building responsive, mobile-first sites

* [Apexcharts](https://getbootstrap.com/) - ApexCharts.RB is a ruby charting library that's going to give your ruby app beautiful, interactive, and responsive charts powered by ApexCharts.JS

* [Pagy](https://getbootstrap.com/) - Pagy is the ultimate pagination gem that outperforms the others in each and every benchmark and comparison.

* [Ransack](https://getbootstrap.com/) - Ransack enables the creation of both simple and advanced search forms for your Ruby on Rails application
