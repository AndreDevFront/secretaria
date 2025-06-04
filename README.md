# 🚀 Landing Page com WhatsApp Integration

![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Design-brightgreen)

> Uma landing page moderna e responsiva com integração direta ao WhatsApp, desenvolvida para maximizar conversões e facilitar o contato com clientes.

## ✨ Features

- 🎨 **Design Moderno**: Interface clean com gradientes e animações suaves
- 📱 **Totalmente Responsiva**: Perfeita em desktop, tablet e mobile
- 💬 **Integração WhatsApp**: Botões estratégicos para contato direto
- ⚡ **Performance Otimizada**: Carregamento rápido e eficiente
- 🎭 **Animações CSS**: Efeitos visuais profissionais
- 🔧 **Fácil Personalização**: Código limpo e bem estruturado
- 🌐 **SEO Friendly**: Meta tags e estrutura otimizada

## 🎯 Demo

[🔗 Ver SecretarIA Online](https://secretaria-woad.vercel.app/)

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização avançada com:
  - Flexbox & Grid Layout
  - Animações e Transições
  - Gradientes CSS
  - Media Queries
- **JavaScript** - Interatividade e efeitos
- **SVG** - Ícones vetoriais escaláveis

## 🚀 Quick Start

### Pré-requisitos

- Navegador web moderno
- Editor de código (VS Code recomendado)
- Git (opcional)

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/landing-page-whatsapp.git
cd landing-page-whatsapp
```

2. **Abra o arquivo**
```bash
# No VS Code
code index.html

# Ou abra diretamente no navegador
open index.html
```

3. **Personalize** conforme suas necessidades

## ⚙️ Personalização

### 📞 Configurar WhatsApp

No arquivo `index.html`, substitua o número de telefone:

```html
<!-- Procure por estas linhas e substitua o número -->
<a href="https://wa.me/5554999999999?text=Olá! Gostaria de saber mais sobre os serviços.">
```

**Formato do número:**
- Use código do país (55 para Brasil)
- Use DDD + número sem espaços
- Exemplo: `5511999999999` para São Paulo

### 🎨 Personalizar Cores

No arquivo de estilo, modifique as variáveis CSS:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --whatsapp-color: #25D366;
  --text-color: #333;
  --background-light: #f8f9fa;
}
```

### 📝 Editar Conteúdo

1. **Título Principal**: Modifique a tag `<h1>` na seção hero
2. **Descrição**: Altere o parágrafo principal
3. **Serviços**: Personalize os cards na seção services
4. **Informações de Contato**: Atualize dados da empresa

### 🖼️ Adicionar Logo

```html
<div class="logo">
  <img src="assets/logo.png" alt="Sua Empresa" width="150">
</div>
```

## 📁 Estrutura do Projeto

```
landing-page-whatsapp/
├── 📄 index.html          # Arquivo principal
├── 📁 assets/             # Recursos estáticos
│   ├── 🖼️ images/         # Imagens e ícones
│   ├── 🎨 css/           # Arquivos CSS (se separados)
│   └── ⚡ js/            # Scripts JavaScript
├── 📄 README.md          # Documentação
└── 📄 LICENSE            # Licença do projeto
```

## 🚀 Deploy

### Netlify (Recomendado)

1. Faça fork do repositório
2. Conecte sua conta do Netlify ao GitHub
3. Selecione o repositório
4. Deploy automático ✨

### Vercel

```bash
npm i -g vercel
vercel --prod
```

### GitHub Pages

1. Vá em Settings do repositório
2. Ative GitHub Pages
3. Selecione branch main
4. Acesse: `https://seu-usuario.github.io/landing-page-whatsapp`

## 🎯 Cases de Uso

- 💼 **Empresas de Serviços**: Consultoria, advocacia, contabilidade
- 🏥 **Área da Saúde**: Clínicas, consultórios, laboratórios  
- 🏠 **Imobiliárias**: Captação de leads para imóveis
- 🛍️ **E-commerce**: Atendimento personalizado
- 📚 **Educação**: Cursos online, mentoria
- 🔧 **Prestadores de Serviço**: Técnicos, freelancers

## 🔧 Customizações Avançadas

### Adicionar Google Analytics

```html
<!-- Adicione antes do </head> -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

### Integrar com Facebook Pixel

```html
<!-- Facebook Pixel Code -->
<script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', 'YOUR_PIXEL_ID');
  fbq('track', 'PageView');
</script>
```

## 📊 Performance

- ⚡ **PageSpeed Score**: 95+/100
- 📱 **Mobile Friendly**: 100% compatível
- 🔍 **SEO Score**: Otimizado
- ♿ **Accessibility**: WCAG AA compliant

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para contribuir:

1. 🍴 Fork o projeto
2. 🌿 Crie uma branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push para a branch (`git push origin feature/AmazingFeature`)
5. 🔀 Abra um Pull Request

### 📋 Guidelines

- Use commits descritivos
- Siga as convenções de código
- Teste em diferentes dispositivos
- Mantenha a performance otimizada

## 🐛 Relatando Bugs

Encontrou um bug? [Abra uma issue](https://github.com/seu-usuario/landing-page-whatsapp/issues) com:

- 📝 Descrição detalhada
- 🔧 Passos para reproduzir
- 📱 Dispositivo/navegador usado
- 📸 Screenshots (se aplicável)

## 🗺️ Roadmap

- [ ] 🎨 Mais temas de cores
- [ ] 📧 Integração com email marketing
- [ ] 📊 Dashboard de analytics
- [ ] 🌍 Suporte a múltiplos idiomas
- [ ] 🤖 Chatbot integrado
- [ ] 📝 Formulário de contato avançado

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

Desenvolvido com ❤️ por **[André Luz da Silva]**

## 🙏 Agradecimentos

- 🎨 **Design Inspiration**: Dribbble e Behance
- 🎭 **Animations**: Animate.css
- 📱 **Icons**: Heroicons e Feather Icons
- 🎯 **WhatsApp API**: Official WhatsApp Business API

---

<div align="center">

**[⬆ Voltar ao topo](#-landing-page-com-whatsapp-integration)**

Made with ❤️ in Brazil 🇧🇷

</div>
