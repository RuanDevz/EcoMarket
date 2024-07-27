# EcoMarket

**EcoMarket** é uma aplicação de e-commerce para venda de tênis e casacos, desenvolvida com **Next.js**, **Tailwind CSS**, **TypeScript** e **Sanity**. O projeto também inclui funcionalidades de carrinho de compras e está integrado com o sistema de pagamento **Stripe**.

## Visão Geral

EcoMarket é uma plataforma de e-commerce intuitiva e moderna, projetada para oferecer uma experiência de compra fluida para os usuários. Com uma interface limpa e responsiva, os usuários podem navegar, selecionar produtos, adicionar ao carrinho e finalizar suas compras com facilidade.
![Captura de tela 2024-07-27 173556](https://github.com/user-attachments/assets/1331bf3e-cdc3-4f74-a139-495d4cc973fc)

## Funcionalidades

- **Navegação de Produtos**: Visualize tênis e casacos disponíveis para compra.
- **Carrinho de Compras**: Adicione e remova itens do carrinho.
- **Checkout**: Finalize a compra utilizando a integração com Stripe.
- **Gestão de Conteúdo**: Utilize o Sanity para gerenciar produtos e conteúdos do site.

## Tecnologias Utilizadas

- **Next.js**: Framework React para construção da interface do usuário.
- **Tailwind CSS**: Framework de CSS utilitário para estilização.
- **TypeScript**: Superset de JavaScript que adiciona tipagem estática.
- **Sanity**: CMS headless para gerenciamento de conteúdo.
- **Stripe**: Plataforma de pagamento online.

## Instalação

Para instalar e rodar o projeto localmente, siga os passos abaixo:

1. Clone o repositório:
    ```bash
    git clone https://github.com/RuanDevz/EcoMarket.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd ecomarket
    ```

3. Instale as dependências:
    ```bash
    npm install
    ```

## Configuração

1. Crie um arquivo `.env.local` na raiz do projeto e adicione as seguintes variáveis de ambiente:

    ```plaintext
    NEXT_PUBLIC_STRIPE_KEY=seu_project_id
    NEXT_PUBLIC_REDIRECT_SUCCESS=seu_dataset
    NEXT_PUBLIC_SANITY_PROJECT_ID=sua_stripe_public_key
    NEXT_PUBLIC_SANITY_DATASET=sua_stripe_secret_key
    ```

2. Configure o Sanity:
    - Siga a documentação oficial do Sanity para configurar o seu projeto e o esquema de dados.

3. Configure o Stripe:
    - Siga a documentação oficial do Stripe para obter suas chaves de API.

## Uso

Para rodar o projeto localmente, execute:

```bash
npm run dev
