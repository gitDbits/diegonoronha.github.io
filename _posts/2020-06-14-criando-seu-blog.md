---
layout: post
title: Criando o seu blog
image: /img/avatar-post-blog.png
tags: RubyOnRails React
---

Uma das melhores maneiras de se aprender ou até mesmo ensinar é: **escrevendo as suas próprias histórias**, a cada novo tutorial é impressionante o quanto você melhora não só como profissional mas também o seu pessoal.

Então, que tal sair um pouco só do falar e **partir para o agir** :)

Para calibrar as suas energias [<span class="fa fa-music"></span> Vegas @ Universo Paralello](https://www.youtube.com/watch?v=6bRGO7r0E-Y){:target="_blank"} 

Pra ajudar no seu começo, vou disponibilizar um projeto de um blog em Ruby on Rails + Framework CSS Bulma(o qual estou apaixonado por ela =p). Fique a vontade em utilizar o repositório, bem como no final eu deixo algumas sugestões para o projeto.

# Meu blog! 

![Screenshot](https://camo.githubusercontent.com/e0cca7940c737ed48a9ba0fa117f15e2c5bb5a2a/68747470733a2f2f692e696d6775722e636f6d2f6c73356154674a2e706e67)

## Estrutura
	* Ruby on Rails 6
	* Framework CSS Bulma
	* Controle de usuário com o Devise
	* Paginação com a gem Pagy
	* Controle e validação no upload de imagem com a gem Image processing
	* Framework para icones FontAwesome 
	* E por fim ActionText para criação dos seus posts no seu blog

### No Meu blog, você poderá: 

* Realizar o cadastros dos seus posts.

* Controle de cadastro de usuários.

* Somente usuários ativos poderão realizar novas postagens.

* Realizar o upload  de imagens no seu posts.

* Editar os seus posts de maneira simples com o ActionText.

* Como sugestão, que tal criar  


### Setup básico...

1. **Instalar o Ruby on Rails:**
	- No **Linux**, sem segredo, **it's simple**: [Install Ruby on Rails Ubuntu <span class="fa fa-external-link"></span>](https://gorails.com/setup/ubuntu/18.04){:target="_blank"} Lembre de verificar a sua versão, nesse link é para a versão **18.04 Ubuntu**

	- No **Windows** :( ok ok ok =p, [Install Ruby on Rails Windows 10 <span class="fa fa-external-link"></span>](https://gorails.com/setup/windows/10){:target="_blank"}

	- No **MAC OS** "you rico man :o", [Install Ruby on Rails MAC OS <span class="fa fa-external-link"></span>](https://gorails.com/setup/osx/10.15-catalina){:target="_blank"}

2. **Realizar o clone do projeto**
	- O projeto se encontra no GitHub [Job GO on GitHub <span class="fa fa-external-link"></span>](https://github.com/gitDbits/spotcode.git){:target="_blank"}, ou se preferir, abra o seu terminal e **execute o seguinte comando:** <br><br>
		
```
	git clone https://github.com/gitDbits/blog_noronha
```

## Vamos lá

Verifique os requisitos abaixo, fique a vontade para realizar o clone do projeto e realizar suas modificações.

Abra o seu terminal e **execute os seguintes comandos:**

*Acesse a pasta em que se encontra o projeto*
```
cd blog_noronha 
```

*Instale a dependência das GEMS*
```
bundle 
```

*Instalando o YARN*
```
yarn install --check-files
```

*Criar o banco de dados, por default ele ira criar em SQLite*
```
rails db:create 
```

*Rodar as migrations do schema do banco de dados*
```
rails db:migrate 
```

*Execute o servidor local para visualizar o projeto*
```
rails s
```

### Sugestões

* Que tal implantar um controle de TAG por cada Post;

* E implementar um módulo de busca por TAG e Autor;


## Construido com

* [Ruby on Rails](https://rubyonrails.org/) - The Ruby on Rails framework for API

* [Devise](https://github.com/heartcombo/devise) - Flexible authentication solution for Rails with Warden

* [Pagy](https://github.com/ddnexus/pagy) - The ultimate solution pagination Rails

* [Image processing](https://github.com/janko/image_processing) - High-level image processing wrapper for libvips and ImageMagick/GraphicsMagick

* [Font Awesome](https://fontawesome.com/) - Library icons CSS
## Conclusão

Ficou com **dúvida**, **alguma sugestão?** Fique a vontade em utilizar os **comentários :)** 