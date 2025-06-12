
# CooperAI - Checkout de Produtos

Uma página de checkout moderna e responsiva para cooperativas agropecuárias, desenvolvida para ser hospedada no GitHub Pages.

## 🌱 Sobre o Projeto

O CooperAI é uma solução de checkout dinâmica que permite receber informações de produtos via parâmetros de URL e montar automaticamente um carrinho de compras interativo.

## 🎨 Design

- **Paleta de Cores:**
  - Verde Principal: #6FB14B
  - Verde Escuro: #344640
  - Fundo Neutro: #F0E4D4

- **Características:**
  - Layout responsivo
  - Design rural-tech moderno
  - Interface limpa e intuitiva
  - Animações suaves

## 🚀 Como Usar

### Parâmetros da URL

A página recebe produtos através do parâmetro `products` na URL, que deve conter um array JSON com os seguintes campos:

```json
[
  {
    "id": "1",
    "name": "Tomate Orgânico",
    "price": 8.5,
    "quantity": 2,
    "unit": "kg"
  },
  {
    "id": "2",
    "name": "Alface Hidropônica",
    "price": 4.9,
    "quantity": 3,
    "unit": "maço"
  }
]
```

### Exemplo de URL

```
https://seusite.github.io/cooperai/?products=[{"id":"1","name":"Tomate Orgânico","price":8.5,"quantity":2,"unit":"kg"},{"id":"2","name":"Alface Hidropônica","price":4.9,"quantity":3,"unit":"maço"}]
```

## 📱 Recursos

- ✅ Carrinho dinâmico via JavaScript
- ✅ Cálculo automático de totais
- ✅ Design responsivo
- ✅ Loading states
- ✅ Estado de carrinho vazio
- ✅ Formatação de moeda brasileira
- ✅ Animações e micro-interações

## 🛠️ Tecnologias

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- JavaScript (ES6+)
- GitHub Pages

## 📦 Deploy

Este projeto está configurado para ser hospedado no GitHub Pages. Basta fazer o upload do arquivo `index.html` para o repositório e ativar o GitHub Pages nas configurações.

## 🤝 Contribuição

Desenvolvido para cooperativas agropecuárias que buscam modernizar seus processos de venda online com tecnologia acessível e eficiente.
