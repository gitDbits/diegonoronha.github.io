---
layout: post
title: Novas skills - Spotify
image: /img/spotify.png
tags: RubyOnRails React
---

Eu sempre me perguntei e demorou eu entender que a profissão de programador se faz necessário sempre buscar inspiração, seja em um projeto, uma linguagem e até mesmo a necessidade de resolver um problema ou uma crise.


Pra, vamos de: [<span class="fa fa-music"></span> CyberPunkMix - 2077 ](https://www.youtube.com/watch?v=vSFmDxn-cK8){:target="_blank"} 


# Job GO! [Ver o projeto <span class="fa fa-external-link"></span>](https://jobgo.herokuapp.com/){:target="blank"}

[![Build Status](https://travis-ci.org/gitDbits/job_go.svg?branch=master)](https://travis-ci.org/gitDbits/job_go) [![Maintainability](https://api.codeclimate.com/v1/badges/9636fa9165d3c122b696/maintainability)](https://codeclimate.com/github/gitDbits/job_go/maintainability)


![Screenshot](https://i.imgur.com/J3FsQn4.png)

Fique a vontade em utilizar o projeto, ou caso queira enviar alguma alteração, basta enviar **aquele fork**
  
### Com o JobGO você podera fazer: 

* Cadastrar e editar empresas.

* Cadastrar e editar categorias.

* Cadastrar vagas de trabalho.

* Visualizar vagas de trabalho por empresa e por categoria.

* Visualizar vagas em destaque, através de uma marcação.

* Visualizar empresa que estão em destaque.

* Visualizar vagas recentes.

* As vagas de trabalho que expiraram após 90 dias.


### Setup básico...

1. **Instalar o Ruby on Rails:**
	- No **Linux**, sem segredo, **it's simple**: [Install Ruby on Rails Ubuntu <span class="fa fa-external-link"></span>](https://gorails.com/setup/ubuntu/18.04){:target="_blank"} Lembre de verificar a sua versão, nesse link é para a versão **18.04 Ubuntu**

	- No **Windows** :( ok ok ok =p, [Install Ruby on Rails Windows 10 <span class="fa fa-external-link"></span>](https://gorails.com/setup/windows/10){:target="_blank"}

	- No **MAC OS** "you rico man :o", [Install Ruby on Rails MAC OS <span class="fa fa-external-link"></span>](https://gorails.com/setup/osx/10.15-catalina){:target="_blank"}

2. **Realizar o clone do projeto**
	- O projeto se encontra no GitHub [Job GO on GitHub <span class="fa fa-external-link"></span>](https://github.com/gitDbits/job_go.git){:target="_blank"}, ou se preferir, abra o seu terminal e **execute o seguinte comando:** <br><br>
		
	
```
	git clone https://github.com/gitDbits/job_go.git
```
<hr>
<hr>
## Vamos lá

Abra o seu terminal e **execute os seguintes comandos:**

*Acesse a pasta em que se encontra o projeto*
```
cd job_go 
```

*Instale a dependência das GEMS*
```
bundle 
```

*Crie o banco de dados, por default ele ira criar em SQLite*
```
rails db:create 
```

*Rode as migrations do schema do banco de dados*
```
rails db:migrate 
```

*Execute o servidor local para visualizar o projeto*
```
rails s
```

<hr>
<hr>
## Conferindo os testes :)

Caso queira **executar os testes** basta **executar no seu terminal:**

```
rspec
```

O **TDD**  *(Test Drive Development)* se bem aplicado tem **ótimos resultados na manutenção de um projeto**, logo os 27 testes da aplicaçao encontra-se na pasta **job_go/spec/features/** confere lá :)

Que tal melhorar a **cobertura no projeto**, depois de alterar faça aquele fork no GitHub :)

![Cobertura testes](/img/simplecov.png)


## Construido com

*  [Ruby on Rails](http://www.dropwizard.io/1.0.2/docs/) - The web framework used

*  [Rspec](https://github.com/rspec/rspec) - Framework BDD

*  [Capybara](https://github.com/teamcapybara/capybara) - Helps you test web applications

*  [SimpleCov](https://github.com/colszowka/simplecov) - Code coverage analysis tool for Ruby

*  [Rubocop](https://github.com/rubocop-hq/rubocop) - A Ruby static code analyzer

*  [friendly_id](https://github.com/norman/friendly_id) - Create pretty URL’s and work with human-friendly

*  [Jquery mask rails](https://github.com/maurcarvalho/jquery_mask_rails) - A Rails gem of the jQuery Plugin mask

## Conclusão

Ficou com **dúvida**, **alguma sugestão?** Fique a vontade em utilizar os **comentários :)** 