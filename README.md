![Logo do cardápio](https://raw.githubusercontent.com/BrunoToniatti/cardapio-online/main/cover.jpg)

# Cardápio Online

Esse é um projeto de um cardápio online que permite que os usuários 
visualizem os itens disponíveis e façam pedidos diretamente pelo site. 
O objetivo desse projeto é tornar mais fácil e conveniente a experiência 
do usuário ao fazer um pedido em um restaurante.


## Funcionalidades

* Poder observar nossos itens e chamar o gaçom (por enquanto estamos no BETA então não acrescentamos muitos itens)

## Tecnologias usadas

* HTML
* CSS
(Obs: o css esta dentro do html no <script>)

### Código da página
```
<!DOCTYPE html>
<html>
<head>
	<title>Cardápio</title>
	<style>
		body {
			font-family: Arial, sans-serif;
		}
		
		.container {
			max-width: 800px;
			margin: 0 auto;
			padding: 20px;
		}
		
		.menu {
			display: flex;
			flex-wrap: wrap;
		}
		
		.item {
			flex: 1 1 200px;
			margin: 10px;
			border: 1px solid #ccc;
			padding: 20px;
			text-align: center;
		}
		
		.item h2 {
			margin-top: 0;
		}
		
		.item p {
			margin-bottom: 0;
		}
	</style>
</head>
<body>
	<div class="container">
		<h1>Cardápio</h1>
		<div class="menu">
			<div class="item">
				<h2>Prato principal</h2>
				<p>Arroz, feijão, frango e salada</p>
				<p>R$ 20,00</p>
			</div>
			<div class="item">
				<h2>Sobremesa</h2>
				<p>Pudim de leite</p>
				<p>R$ 5,00</p>
			</div>
			<div class="item">
				<h2>Bebida</h2>
				<p>Refrigerante lata</p>
				<p>R$ 4,00</p>
			</div>
		</div>
	</div>
</body>
</html>

```




## Como executar o projeto.

1. Clone o repositório para o seu computador:
```
git clone https://github.com/BrunoToniatti/cardapio-online.git
```

2. Navegue até a pasta do projeto:
```
cd cardapio-online
```

3. Abra o arquivo index.html que é onde contém a página.

## Autores

* Bruno Ferrari Toniatti
* Gabriel Varuzza
* João Pedro Moreira

## Observações
* Esse projeto está em fase de desenvolvimento e pode ter bugs.
* Agradecemos qualquer contribuição ou sugestão de melhoria.
* Entre em contato se tiver dúvidas ou precisar de ajuda.
