# Loja Drip

## Descrição

O **Loja Drip** é uma aplicação frontend de e-commerce desenvolvida com React, utilizando Vite como bundler e Tailwind CSS para estilização.

O projeto simula uma loja virtual com navegação entre páginas, listagem de produtos, categorias, carrinho de compras e fluxo básico de cadastro de usuários.

---

## Tecnologias Utilizadas

- React
- Vite
- React Router DOM
- Tailwind CSS
- Axios
- React Icons
- ESLint

---

## Estrutura do Projeto
'''loja-drip/
├── src/
│ ├── assets/ # Imagens e ícones
│ ├── components/ # Componentes reutilizáveis
│ │ ├── HomePage/
│ │ └── AbaProdutos/
│ ├── contexts/ # Context API (ex: carrinho)
│ ├── data/ # Dados mockados (produtos)
│ ├── pages/ # Páginas da aplicação
│ ├── services/ # Integração com APIs
│ ├── App.jsx # Componente principal
│ └── main.jsx # Entry point
│
├── index.html
├── vite.config.js
├── tailwind.config.js
├── package.json'''

---

## Funcionalidades

- Navegação entre páginas com React Router
- Listagem de produtos
- Filtro por categorias
- Carrinho de compras (Context API)
- Componentes reutilizáveis para exibição de produtos
- Estrutura preparada para integração com API

---

## Requisitos

- Node.js >= 18
- npm ou yarn

---

## Instalação

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
cd loja-drip
```

2. Instale as dependências:

```bash
npm install
```

## Execução

Ambiente de desenvolvimento

```bash
npm run dev
```
A aplicação estará disponível em:

http://localhost:5173

Build para produção

```bash
npm run build
``` 

Preview do build

```bash
npm run preview
```

## Integração com API

O projeto utiliza o Axios para comunicação com APIs externas.

Arquivo principal:

src/services/api.js

Atualmente, também utiliza dados mockados em:

src/data/products.js


## Padrões e Organização

Separação por responsabilidades (components, pages, services)
Uso de Context API para gerenciamento de estado global (carrinho)
Componentização para reuso de UI
Estilização com Tailwind CSS

## Contribuição:
1. Faça um fork do projeto
2. Crie uma branch para sua feature:

```bash
git checkout -b minha-feature
```

3. Commit suas alterações:

```bash
git commit -m "feat: descrição da mudança"
```

4. Envie para o repositório:

```bash
git push origin minha-feature
```

5. Abra um Pull Request

## Licença

Este projeto não possui uma licença definida até o momento.

Caso seja necessário uso em produção ou distribuição, recomenda-se adicionar uma licença apropriada (ex: MIT, Apache 2.0).