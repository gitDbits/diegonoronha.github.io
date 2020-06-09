---
layout: post
title: Novas skills - SpotCode
image: /img/spotify.png
tags: RubyOnRails React
---

Eu sempre me perguntei e demorou eu entender que a profissão de programador se faz necessário sempre buscar inspiração, seja em um projeto, uma linguagem ou até mesmo a necessidade de resolver um problema ou uma crise.

Hoje, vamos de: [<span class="fa fa-music"></span> Hadouken Theme Song](https://www.youtube.com/watch?v=ncVGKT9Y7fY){:target="_blank"} 

A ideia é, vamos navegar no universo do front-end, começando com [React](https://pt-br.reactjs.org/){:target="_blank"}, uma biblioteca JavaScript para criar interfaces de usuários, baseados em componentes. 

# SpotCode! 

![Screenshot](https://camo.githubusercontent.com/806831d1765acaf13e23f4c205990b4f29f5a32f/68747470733a2f2f692e696d6775722e636f6d2f6a706b764a4c382e706e67)

## Estrutura
	* Backend API em Ruby on Rails 6
	* FrontEnd em React
	* E muita felicidade em aprender algo novo, ainda mais React :)

### No SpotCode, você poderá: 

* Ouvir as suas músicas pelo seu estilo favorito.

* Ouvir as músicas tocadas recentemente.

* Ouvir as músicas recomendadas.

* Conferir as músicas separadas por álbums e artistas e seus diferentes estilos.

* Favoritar as suas músicas, albums e artistas e conferir essa lista.

* Poderá tocar as musicas aleatoriamente.

* Realizar busca pelo nome: Música, Artista, Album.

* Login e cadastro de usuaŕio e suas validações.


### Setup básico...

1. **Instalar o Ruby on Rails:**
	- No **Linux**, sem segredo, **it's simple**: [Install Ruby on Rails Ubuntu <span class="fa fa-external-link"></span>](https://gorails.com/setup/ubuntu/18.04){:target="_blank"} Lembre de verificar a sua versão, nesse link é para a versão **18.04 Ubuntu**

	- No **Windows** :( ok ok ok =p, [Install Ruby on Rails Windows 10 <span class="fa fa-external-link"></span>](https://gorails.com/setup/windows/10){:target="_blank"}

	- No **MAC OS** "you rico man :o", [Install Ruby on Rails MAC OS <span class="fa fa-external-link"></span>](https://gorails.com/setup/osx/10.15-catalina){:target="_blank"}

2. **Realizar o clone do projeto**
	- O projeto se encontra no GitHub [Job GO on GitHub <span class="fa fa-external-link"></span>](https://github.com/gitDbits/spotcode.git){:target="_blank"}, ou se preferir, abra o seu terminal e **execute o seguinte comando:** <br><br>
		
```
	git clone https://github.com/gitDbits/spotcode.git
```

## Vamos lá

Verifique os requisitos abaixo, fique a vontade para realizar o clone do projeto e realizar suas modificações.

Abra o seu terminal e **execute os seguintes comandos:**

*Acesse a pasta em que se encontra o projeto*
```
cd spotcode 
```

*Instale a dependência das GEMS*
```
bundle 
```

*Instalando o YARN*
```
yarn install --check-files
```

*Arquivos iniciais do spotcode*

- Os arquivos para utilização na aplicação spotcode: Músicas, Imagem,  Artista, Imagem dos álbuns pode ser realizado, no link abaixo;

- Download [cliquei aqui](https://drive.google.com/open?id=1qp4bzU7nYr2P9cM__3SSH16xGCwneP3S) 

**Após realizar o download da pasta seed_files, mover para a pasta /spotcode/tmp/**

*Criar o banco de dados, por default ele ira criar em SQLite*
```
rails db:create 
```

*Rodar as migrations do schema do banco de dados*
```
rails db:migrate 
```

*Executar os seeds*

Neste arquivo você pode conferir as informações iniciais para o projeto spotcode/db/seeds.rb

```
rails db:seed
```

*Instalar o webpacker*
```
bundle exec rails webpacker:install
```

*Atualizar navegador automaticamente*

Após qualquer alteração no código: basta abrir um outro terminal e executar o seguinte comando:  

```
bin/webpack-dev-server 
```

*Execute o servidor local para visualizar o projeto*
```
rails s
```
## Construido com

*  [Ruby on Rails](https://rubyonrails.org/) - Rails is a web application development framework written in the Ruby programming language

* [React](https://github.com/facebook/react/blob/master/README.md) - React is a JavaScript library for building user interfaces.

* [Web Packer Rails](https://github.com/rails/webpacker) - Web Packer Rails

* [JBuilder](https://github.com/rails/jbuilder/blob/master/README.md) - JSON structures that beats manipulating giant hash structures

* [Devise](https://github.com/heartcombo/devise) - Flexible authentication solution for Rails with Warden

* [Rack-cors](https://github.com/cyu/rack-cors) - Rack Middleware for handling Cross-Origin Resource Sharing (CORS)

* [Toast-rails](https://github.com/tylergannon/toastr-rails) - Messages beautiful based toasttrjs

## Conclusão

Ficou com **dúvida**, **alguma sugestão?** Fique a vontade em utilizar os **comentários :)** 