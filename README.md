<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0a2e,100:e87820&height=180&section=header&text=Agropecuária%20Vida%20Longa%20🌾&fontSize=40&fontColor=ffffff&fontAlignY=40&animation=fadeIn"/>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Online-00ff88?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Pedidos-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
  <img src="https://img.shields.io/badge/Database-Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

<p align="center">
  <strong>E-commerce completo para loja agropecuária — pedidos enviados direto pelo WhatsApp. 🐄</strong>
</p>

---

## 📖 Sobre o Projeto

**Agropecuária e Ferragem Vida Longa** é um e-commerce desenvolvido para facilitar as vendas da loja. O cliente navega pelos produtos, adiciona ao carrinho e finaliza o pedido — que é enviado automaticamente via **WhatsApp** com todos os detalhes: nome, endereço, itens e valor total.

---

## ✨ Funcionalidades

- 🛒 **Carrinho de compras** completo
- 📲 **Pedido via WhatsApp** com endereço, itens e valor automaticamente formatados
- 🗂️ **Filtros por categoria** — Animais, Ferragens, Defensivos, etc.
- ⭐ **Sistema de avaliações** por produto
- 🔐 **Painel administrativo** para gerenciar produtos e fotos
- 🖼️ **Troca de fotos dos produtos** pelo admin
- 📦 **Sugestões de produtos** relacionados
- 📱 **Totalmente responsivo** — funciona no celular e desktop
- 🌄 **Hero section** com chamada para ação
- 💜 **Design elegante** com tema roxo e laranja

---

## 🛠️ Tecnologias

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
</p>

---

## 🛒 Como Funciona o Pedido

```
1. Cliente navega pelos produtos e filtra por categoria
2. Adiciona produtos ao carrinho 🛒
3. Informa nome e endereço de entrega
4. Clica em "Finalizar Pedido"
5. WhatsApp abre com mensagem pronta 📲
   → Lista de produtos, quantidades, valores e endereço
6. Loja recebe e confirma o pedido ✅
```

---

## 📁 Estrutura do Projeto

```
agropecuaria-vida-longa/
└── index.html    # App completo (frontend + integração Supabase)
```

---

## ⚙️ Configuração

No arquivo `index.html`, localize e substitua as chaves do Supabase:

```javascript
const SUPABASE_URL  = 'COLE_SUA_URL_AQUI';
const SUPABASE_ANON = 'COLE_SUA_ANON_KEY_AQUI';
```

E o número do WhatsApp da loja:

```javascript
const WHATSAPP_NUMBER = '55XXXXXXXXXXX'; // DDD + número
```

---

## 🔐 Painel Administrativo

O sistema possui um modo admin que permite:

- 📸 Trocar fotos dos produtos diretamente na loja
- ➕ Adicionar e editar produtos
- 📊 Gerenciar categorias e estoque

Para acessar, utilize as credenciais de administrador configuradas no Supabase.

---

## 🚀 Como Rodar Localmente

```bash
# Clone o repositório
git clone https://github.com/leonardoian/agropecuaria-vida-longa.git

# Abra o arquivo no navegador
# (Não precisa de servidor — é HTML puro!)
```

Ou simplesmente abra o `index.html` direto no navegador. ✅

---

## 👨‍💻 Desenvolvido por

<p align="center">
  Feito com ❤️ por <strong>Leonardo Ian de Oliveira</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/leonardo-ian-b8b410274/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/leonardoian" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:e87820,100:1a0a2e&height=120&section=footer"/>
