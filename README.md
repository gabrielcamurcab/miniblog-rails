# MiniBlog Rails

Um projeto de blog, meu primeiro com Rails, justamente para praticar e entender a estruturação de um projeto Rails, e como codar em Ruby on Rails.

## Pré-requisitos

- Ruby (versão recomendada: 3.x)
- Rails (versão recomendada: 7.x)
- SQLite3 (ou outro banco de dados suportado)

## Instalação

1. Clone o repositório:
	```bash
	git clone <url-do-repositorio>
	cd miniblog-rails
	```

2. Instale as dependências:
	```bash
	bundle install
	```

3. Configure o banco de dados:
	```bash
	rails db:setup
	```
	Ou, se preferir, crie e migre manualmente:
	```bash
	rails db:create
	rails db:migrate
	rails db:seed
	```

## Rodando o servidor

Para iniciar o servidor localmente:

```bash
rails server
```

Acesse [http://localhost:3000](http://localhost:3000) no seu navegador.

## Rodando os testes

Para executar a suíte de testes:

```bash
rails test
```

## Estrutura do Projeto

O projeto segue a estrutura padrão de aplicações Rails, com pastas para controllers, models, views, assets, entre outros.

---

Sinta-se à vontade para explorar, modificar e aprender!