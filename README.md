# E-commerce com Integração WhatsApp

## Visão Geral do Projeto

Este projeto é uma aplicação web de e-commerce que permite aos clientes selecionar produtos, adicioná-los a um carrinho de compras e finalizar o pedido diretamente via WhatsApp. Além disso, inclui um painel de administração para o gerente da loja, que pode adicionar, remover e atualizar produtos e seus preços em tempo real.

## Funcionalidades

### Para o Cliente

*   **Navegação de Produtos:** Visualização de uma lista de produtos disponíveis.
*   **Adicionar ao Carrinho:** Seleção de produtos e adição ao carrinho de compras.
*   **Gerenciamento de Carrinho:** Visualização, atualização de quantidades e remoção de itens do carrinho.
*   **Checkout via WhatsApp:** Geração de uma mensagem pré-preenchida com o resumo do pedido para envio direto ao vendedor via WhatsApp, agilizando o processo de compra.

### Para o Gerente (Painel Administrativo)

*   **Gestão de Produtos:** Adicionar novos produtos, editar detalhes de produtos existentes (nome, descrição, preço, imagem) e remover produtos.
*   **Controle de Estoque:** Atualização de quantidades de produtos.
*   **Atualização de Preços:** Modificação dinâmica dos preços dos produtos.

## Tecnologias Utilizadas

*   **Front-end:**
    *   HTML5
    *   CSS3 (com foco em responsividade)
    *   JavaScript (Vanilla JS para manipulação do DOM e lógica de negócio)
*   **Back-end (Simulado/Gerenciamento):**
    *   JavaScript (para a lógica de gerenciamento de produtos no painel administrativo, possivelmente usando armazenamento local ou um mock de API para demonstração).
*   **Integração:**
    *   API do WhatsApp (via URL de mensagem pré-preenchida).

## Como Rodar o Projeto Localmente

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/ecommerce-whatsapp-portfolio.git
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd ecommerce-whatsapp-portfolio
    ```
3.  **Abra o arquivo `index.html` no seu navegador:**
    Basta dar um duplo clique no arquivo `index.html` ou abri-lo através do seu editor de código e usar a funcionalidade "Open with Live Server" (se disponível).

## Estrutura de Pastas (Sugestão)

```
 ecommerce-whatsapp-portfolio/
 ├── index.html             # Página principal do e-commerce
 ├── admin.html             # Painel administrativo
 ├── css/
 │   └── style.css          # Estilos CSS globais
 ├── js/
 │   ├── main.js            # Lógica do carrinho e interação do cliente
 │   └── admin.js           # Lógica do painel administrativo
 └── assets/
     └── images/            # Imagens dos produtos
```

## Próximos Passos e Melhorias (Opcional)

*   Implementar um banco de dados real (e.g., Node.js com Express e MongoDB/PostgreSQL) para persistência de dados de produtos e pedidos.
*   Adicionar autenticação de usuário para o painel administrativo.
*   Melhorar a interface do usuário com um framework CSS (e.g., Bootstrap, Tailwind CSS).
*   Implementar testes unitários e de integração.
*   Deploy da aplicação em um serviço de hospedagem (e.g., Netlify, Vercel para o front-end, Heroku para o back-end).

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

*   **Seu Nome**
*   [Seu LinkedIn](https://www.linkedin.com/in/seu-perfil)
*   [Seu Email](mailto:seu.email@example.com)

---
