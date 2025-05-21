

# Fake Site Reserva 🧥🛒

Este é um projeto de e-commerce construído com Django, que simula o funcionamento do site da marca **Reserva**. O projeto foi desenvolvido como parte de um estudo prático com o curso da **Hashtag Treinamentos**, com o objetivo de aplicar e consolidar conhecimentos em desenvolvimento web com Python.

## 🔧 Tecnologias Utilizadas

- **Python**
- **Django**
- **HTML/CSS**
- **JavaScript** (em pontos específicos)
- **SQLite** (banco de dados padrão do Django)
- **Mercado Pago** (integração de pagamentos)

## 🛍️ Funcionalidades

- Cadastro e login de usuários
- Página de listagem de produtos (roupas masculinas)
- Detalhes individuais de cada produto
- Carrinho de compras
- Sistema de checkout com integração ao Mercado Pago
- Painel administrativo (via Django Admin)
- Cadastro e edição de produtos (restrito a admins)
- 
## Como rodar o projeto
- Clone o repositorio
- crie um ambiente virtual (recomendado)
- Instale as bibliotecas presente no arquivo requirements.txt
- use no seu terminal cd ecommerce para adentrar na pasta do projeto
- Rode os comandos padroes para iniciar uma projeto com djando  ex: python manage.py migrate, runserver etc.

## 🏗️ Estrutura do Projeto

```bash
fake_site_reserva/
│
├── core/               # Aplicação principal com views, models e urls
├── static/             # Arquivos estáticos (CSS, JS, imagens)
├── templates/          # Templates HTML
├── media/              # Uploads de imagens de produtos
├── fake_site_reserva/  # Configurações globais do projeto
├── manage.py
└── requirements.txt

