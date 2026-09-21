# Tergon Pisos Industriais — Landing Page

Landing page institucional desenvolvida para a **Tergon Pisos Industriais**, empresa fictícia de referência especializada em pisos industriais de alta resistência (epóxi, poliuretano cimentício e antiderrapante) para indústria e logística.

Projeto criado como peça de portfólio, demonstrando uma página de vendas (one-page) completa: copywriting orientado a conversão, prova social com cases reais, e um layout responsivo construído do zero em HTML, CSS e JavaScript puros.

## 🔗 Demo ao vivo

Publicado via GitHub Pages: **https://aline-lih.github.io/tergon-pisos-industriais/**

## ✨ Sobre o projeto

A página foi estruturada como um funil de conversão para geração de orçamentos, com:

- **Hero** de impacto com proposta de valor clara e CTA duplo (orçamento / ver casos).
- **Faixa de números** reforçando autoridade (anos de mercado, m² executados, equipe própria, estados atendidos).
- **Seção institucional** com diferenciais em lista de benefícios.
- **Grade de serviços** com 6 soluções técnicas (epóxi autonivelante, poliuretano cimentício, antiderrapante multicamada, proteção química, demarcação de áreas e recuperação de pisos), cada uma com ícone em SVG.
- **CTA intermediária** para quebrar a rolagem e reforçar a chamada para ação.
- **Cases reais** em formato de card, com problema → resultado, para prova social.
- **Formulário de contato** e dados institucionais (endereço, telefone, e-mail, horário).
- **Botão flutuante do WhatsApp** para contato rápido.
- **Menu responsivo** com toggle mobile (hambúrguer) via JavaScript vanilla.

## 🛠️ Tecnologias

- **HTML5** semântico, com dados estruturados **Schema.org** (`HomeAndConstructionBusiness`) para SEO local.
- **CSS3** puro (custom properties, Grid e Flexbox, `clamp()` para tipografia fluida, media queries para 3 breakpoints).
- **JavaScript vanilla** (sem frameworks) apenas para o toggle do menu mobile.
- Meta tags **Open Graph** e **Twitter Card** para compartilhamento em redes sociais.
- Sem dependências externas — projeto 100% estático, pronto para qualquer hospedagem (GitHub Pages, Netlify, Vercel, etc.).

## 📁 Estrutura

```
├── index.html          # página única com todo o conteúdo e estilos
└── img/                 # imagens usadas na página (hero, equipe, cases)
```

## ▶️ Rodando localmente

Por ser um site 100% estático, basta abrir o arquivo diretamente no navegador:

```bash
git clone https://github.com/Aline-Lih/tergon-pisos-industriais.git
cd tergon-pisos-industriais
open index.html   # ou apenas dê duplo clique no arquivo
```

Ou sirva com qualquer servidor local simples:

```bash
python3 -m http.server 8000
```

## ⚠️ Observações

Este é um projeto de portfólio/demonstração. Nome da empresa, endereço, telefone, e-mail e cases apresentados são **fictícios**, criados para fins de exemplo de copywriting e layout.

---

Feito por [Aline](https://github.com/Aline-Lih) como parte do portfólio de desenvolvimento web.
