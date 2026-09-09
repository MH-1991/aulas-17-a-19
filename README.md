# Essenza Perfumes

Site institucional e landing page para uma marca de perfumes, com página inicial e página de contato.

## Descrição do projeto

O projeto foi desenvolvido em HTML, CSS e JavaScript para apresentar uma marca de fragrâncias com:

- hero section com destaque visual
- seção de benefícios
- catálogo de produtos
- história da marca
- newsletter
- página de contato com formulário
- menu responsivo e interações simples no front-end

## Estrutura do projeto

```text
.
├── index.html
├── contato.html
├── style.css
├── README.md
```

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Imagens externas do Unsplash

## Como executar o projeto

### Opção 1: abrir diretamente no navegador

1. Acesse a pasta do projeto.
2. Abra o arquivo `index.html` no navegador.
3. Para visualizar a página de contato, abra o arquivo `contato.html`.

### Opção 2: rodar um servidor local

Se quiser simular um ambiente mais próximo de um projeto web, use um servidor local.

#### Com Python

1. Abra o terminal na pasta do projeto.
2. Execute:

```bash
python -m http.server 8000
```

3. Acesse no navegador:

```text
http://localhost:8000
```

#### Com VS Code (Live Server)

1. Instale a extensão Live Server.
2. Clique com o botão direito em `index.html`.
3. Selecione a opção "Open with Live Server".

## Funcionalidades atuais

- Layout responsivo para desktop e mobile
- Navegação entre páginas
- Menu hamburguer em telas menores
- Botões de adicionar ao carrinho com contador visual
- Formulário de newsletter com mensagem de confirmação
- Formulário de contato com validação básica e mensagem de sucesso

## Recursos que ainda faltam ser implementados

A estrutura atual funciona como protótipo front-end, mas ainda há diversas melhorias planejadas:

### Funcionalidades de e-commerce

- carrinho persistente com `localStorage`
- cálculo total de compra
- remoção e alteração de quantidade de itens
- página de checkout
- integração com backend ou API de pagamentos

### Backend e dados reais

- conexão do formulário de contato com e-mail real ou API
- banco de dados para produtos
- cadastro de usuários
- autenticação de clientes
- painel administrativo

### Melhorias de UX

- filtros por categoria e preço
- busca por nome do perfume
- favoritos persistentes
- paginação ou carregamento dinâmico de produtos
- animações mais elaboradas
- microinterações mais refinadas

### Acessibilidade e qualidade

- validação mais robusta dos formulários
- suporte melhor a leitores de tela
- contrastes e foco de teclado aprimorados
- organização semântica e melhorias no SEO

### Escalabilidade

- migração para React, Vue ou Next.js
- organização em componentes e módulos
- uso de SASS ou CSS Modules
- deploy em plataforma como Vercel, Netlify ou GitHub Pages

## Melhorias sugeridas para o próximo passo

1. Transformar os produtos em dados dinâmicos.
2. Implementar o carrinho real com armazenamento no navegador.
3. Conectar os formulários a um serviço externo.
4. Adicionar uma página de detalhes do produto.
5. Organizar o projeto em estrutura modular para crescer com mais itens.

## Conclusão

Este é um projeto estático de apresentação de uma marca de perfumes com boa base visual e interativa. Ele já demonstra a identidade da marca e a navegação do site, mas ainda precisa de integrações e funcionalidades mais avançadas para se tornar uma loja completa.
