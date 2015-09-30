# Requisitos - Pappa & Ciccia App

Sistema para pedido de almoço para diminuir a espera de preparo, 
onde o cliente através do app seleciona as opções de prato e 
informa a hora de chegada no restaurante. O administrador recebe a 
notificação no smartphone e dá início a preparação do prato.
Portanto, haverá duas visões do sistema, uma para o cliente fazer 
o pedido e a versão do administrador, para consulta dos pedidos feitos.


# Visão do cliente


## Atores
- Admin
- Cliente


## Casos de Uso

- Login
	- Via Facebook ou token entregue pelo admin?
- Menu do dia
	- Matriz de opções:
	- [carnes], [acompanhamentos], [sucos] 
- Pedido
	- Número pedido (para consulta do cliente e admin)
	- Cliente
	- Selecionar uma ou mais opções de cada elemento do menu
	- Hora de chegada no restaurante
	- Push notification para o admin de novo pedido
	- Quantidade



## Tabelas

- cliente
	- token ou id
- menu
	- data
	- cod_categoria
- menu_categoria
	- cod_categoria
	- descricao
	- modificadores (json)
- opcoes_categoria
	- cod_categoria
	- cod_opcao
	- descricao
- pedido
	- cod_pedido
	- data_hora
	- hora_chegada
	- quantidade
- pedido_item
	- cod_pedido
	- cod_opcao
	- quantidade





