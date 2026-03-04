🌿 Monte Sinai Ervas — Landing Page com Carrinho e WhatsApp

Landing page desenvolvida para a loja Monte Sinai Ervas, permitindo que clientes montem pedidos diretamente no site e enviem automaticamente para o WhatsApp da loja.

Os produtos são carregados dinamicamente a partir de uma planilha do Google Sheets, facilitando a atualização diária do catálogo sem necessidade de alterar o código.

🚀 Funcionalidades
📦 Catálogo dinâmico

Produtos carregados automaticamente do Google Sheets

Atualização instantânea ao modificar a planilha

⚖️ Venda a granel

Produtos podem ser vendidos por gramagem

Preço calculado automaticamente com base no valor por kg

🧴 Venda por unidade

Produtos vendidos por unidade também são suportados

Controle de quantidade no carrinho

🛒 Carrinho de compras

Adicionar produtos

Ajustar quantidade ou gramagem

Cálculo automático do total

🔎 Busca de produtos

Pesquisa por nome

Pesquisa por código

💬 Integração com WhatsApp

Pedido enviado automaticamente para o WhatsApp da loja

Detecta automaticamente:

📱 celular → abre app do WhatsApp

💻 computador → abre WhatsApp Web

🧠 Como funciona

O fluxo do sistema é simples:
Google Sheets
      ↓
Apps Script (API)
      ↓
Landing Page
      ↓
Carrinho
      ↓
Pedido enviado para WhatsApp

1️⃣ A planilha contém os produtos da loja
2️⃣ Um Google Apps Script transforma a planilha em uma API
3️⃣ O site busca os produtos automaticamente
4️⃣ O cliente monta o pedido
5️⃣ O pedido é enviado para o WhatsApp da loja

🗂 Estrutura da Planilha

A planilha contém as seguintes colunas principais:

Coluna	Descrição
Código	Código interno do produto
Produto	Nome do produto
Categoria	Categoria do produto
Peso Unidade	Unidade de peso
Tipo	GRANEL ou UN
Preço Venda	Preço do produto (por kg ou unidade)

Exemplo:

Código	Produto	    Tipo	    Preço Venda
ERV001	Camomila	GRANEL	    60
GEL001	Gel Arnica	UN	        25

🛠 Tecnologias utilizadas

HTML5

CSS3

JavaScript (Vanilla JS)

Google Sheets

Google Apps Script

WhatsApp API (wa.me)

📱 Demonstração

O usuário pode:

Buscar um produto

Escolher quantidade ou gramagem

Adicionar ao carrinho

Finalizar o pedido

Enviar automaticamente para o WhatsApp da loja

⚙️ Configuração

No arquivo index.html, configure:
const SHEETS_API_URL = "URL_DO_APPS_SCRIPT";
const WHATSAPP_NUMBER = "55919XXXXXXXX";

🔄 Atualização dos produtos

Para atualizar o catálogo da loja:

Abra o Google Sheets

Adicione ou edite produtos

Salve a planilha

O site carregará automaticamente os novos produtos.

📌 Possíveis melhorias futuras

Filtro por categoria

Controle de estoque

Área administrativa

Integração com sistema de pagamento

Sistema de pedidos com banco de dados

Deploy em domínio próprio

👨‍💻 Autor

Allan Arruda

Projeto desenvolvido como solução real para a loja Monte Sinai Ervas, automatizando o processo de pedidos via WhatsApp.

⭐ Contribuição

Sugestões e melhorias são bem-vindas.

Se este projeto foi útil para você, considere deixar uma ⭐ no repositório.