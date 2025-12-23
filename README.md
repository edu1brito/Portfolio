# 🎨 Portfolio Pessoal - Eduardo Brito

Portfolio pessoal desenvolvido para apresentar projetos, habilidades e informações de contato de forma profissional e moderna.

![Portfolio Preview](meuportfolio/assets/images/hero-bg.jpg)

## 📋 Sobre o Projeto

Este é um portfólio web responsivo e moderno, desenvolvido com foco em design clean e experiência do usuário. O projeto apresenta uma interface intuitiva com animações suaves e navegação fluida, destacando projetos pessoais e habilidades profissionais.

## ✨ Características

- **Design Responsivo**: Adaptável para dispositivos móveis, tablets e desktops
- **Navegação Suave**: Scroll suave entre seções com menu hamburger para mobile
- **Animações CSS**: Efeitos de revelação de texto e transições elegantes
- **Interface Moderna**: Uso de gradientes, sombras e efeitos hover
- **Menu Mobile**: Menu hamburger animado para dispositivos móveis
- **Seções Bem Definidas**: Home, Serviços, Projetos, Sobre e Contato

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e moderna
- **CSS3**: Estilização avançada com:
  - Flexbox para layouts responsivos
  - Animações e transições
  - Media queries para responsividade
  - Gradientes lineares
  - Efeitos de hover e transformações
- **JavaScript**: Interatividade e funcionalidades:
  - Menu hamburger toggle
  - Mudança de cor do header ao scroll
  - Navegação dinâmica

## 📂 Estrutura do Projeto

```
Portfolio-main/
└── meuportfolio/
    ├── assets/
    │   ├── icons/
    │   │   ├── github.png
    │   │   ├── linkedin.png
    │   │   ├── icone1.png
    │   │   ├── icone2.png
    │   │   └── icone3.png
    │   ├── images/
    │   │   ├── favicon.jpg
    │   │   ├── fotobonitao.JPG
    │   │   ├── hero-bg.jpg
    │   │   ├── projeto1.jpg
    │   │   ├── projeto2.png
    │   │   ├── projeto3.png
    │   │   └── projeto4.png
    │   └── resume.pdf
    ├── index.html
    ├── style.css
    └── index.js
```

## 🎯 Seções do Portfolio

### 🏠 Home (Hero)
- Animação de revelação do nome
- Call-to-action para projetos
- Background com overlay escuro

### 💼 Serviços
Apresenta três principais serviços oferecidos:
1. **Desenvolvimento de Sites**: HTML, CSS e JavaScript
2. **Suporte Técnico**: Manutenção de computadores, impressoras e redes
3. **Design e Protótipos**: Criação de layouts e interfaces

### 📁 Projetos
Showcase de 4 projetos principais:
- **Concept Art do Site ALEMA**: Redesign do site da Assembleia Legislativa usando Figma
- **Lista de Tarefas**: Aplicação web com HTML5, CSS3 e JavaScript
- **MedStats**: App de saúde para acompanhamento de indicadores médicos
- **PayEver Shop**: Protótipo de plataforma e-commerce

### 👨‍💻 Sobre Mim
- Apresentação profissional
- Foto pessoal com efeito de borda
- Download do currículo em PDF

### 📞 Contato
Informações de contato organizadas:
- Telefone
- Email
- Endereço

## 🎨 Paleta de Cores

- **Primária**: Crimson (#DC143C)
- **Secundária**: Tons de cinza escuro (#29323c, #485563)
- **Neutras**: Branco e preto para contraste

## ⚙️ Como Usar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Nenhuma dependência externa necessária

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/portfolio.git
```

2. Navegue até o diretório do projeto:
```bash
cd portfolio/meuportfolio
```

3. Abra o arquivo `index.html` no seu navegador preferido:
```bash
# Linux/Mac
open index.html

# Windows
start index.html
```

Ou simplesmente arraste o arquivo `index.html` para o navegador.

## 📱 Responsividade

O portfolio é totalmente responsivo com breakpoints em:
- **Mobile**: < 768px
- **Tablet**: 768px - 1199px
- **Desktop**: ≥ 1200px

### Características Responsivas:
- Menu hamburger em telas menores
- Layout de grid adaptativo para projetos
- Imagens responsivas
- Tipografia escalável

## 🎭 Funcionalidades JavaScript

### Menu Hamburger
```javascript
// Toggle do menu mobile ao clicar no hamburger
hamburger.addEventListener("click", () => {
  hamburger.classList.toggle("active");
  mobileMenu.classList.toggle("active");
});
```

### Header Dinâmico
```javascript
// Mudança de cor do header ao fazer scroll
document.addEventListener("scroll", () => {
  var scroll_position = window.scrollY;
  if (scroll_position > 250) {
    header.style.backgroundColor = "#29323c";
  } else {
    header.style.backgroundColor = "transparent";
  }
});
```

## 🔧 Personalização

### Alterar Informações Pessoais

1. **Nome e Título**: Edite as tags `<h1>` na seção hero
2. **Foto**: Substitua `fotobonitao.JPG` na pasta `assets/images/`
3. **Projetos**: Atualize as seções de projeto no HTML com seus próprios projetos
4. **Contato**: Modifique os dados de contato na seção `#contact`
5. **Currículo**: Substitua o arquivo `resume.pdf` na pasta `assets/`

### Alterar Cores

Modifique as variáveis de cor no `style.css`:
- Cor primária (crimson): `.section-title span`, `.cta`, etc.
- Background gradientes: `#services .service-item::after`

## 🌐 Deploy

### GitHub Pages

1. Faça push do código para o GitHub
2. Vá em Settings > Pages
3. Selecione a branch main e a pasta raiz
4. Aguarde alguns minutos e seu site estará online!

### Netlify

1. Arraste a pasta do projeto para [Netlify Drop](https://app.netlify.com/drop)
2. Ou conecte seu repositório GitHub para deploy automático

### Vercel

1. Instale a CLI do Vercel: `npm i -g vercel`
2. Na pasta do projeto: `vercel`
3. Siga as instruções

## 📊 Performance

- ✅ HTML semântico para melhor SEO
- ✅ CSS otimizado sem frameworks pesados
- ✅ JavaScript vanilla (sem dependências)
- ✅ Imagens otimizadas
- ✅ Carregamento rápido

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Eduardo Brito**

- Portfolio: [DUDU DEV](https://seu-portfolio.com)
- LinkedIn: [Eduardo de Brito](https://www.linkedin.com/in/eduardo-de-brito-437347231/)
- GitHub: [@edu1brito](https://github.com/edu1brito)
- Email: edudbcprof@gmail.com

## 🙏 Agradecimentos

- Ícones por [Icons8](https://icons8.com)
- Fonte Montserrat por [Google Fonts](https://fonts.google.com)
- Inspiração de design da comunidade web dev

---

⭐ Se este projeto te ajudou, considere dar uma estrela no repositório!

**Desenvolvido com ❤️ por Eduardo Brito**
