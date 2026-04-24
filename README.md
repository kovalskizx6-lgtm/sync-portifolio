# 🚀 Sync Portfolio

Portfólio profissional e moderno para desenvolvedor focado em networking digital, criação de sites, APIs e automação.

## ✨ Características

- **Design Dark Premium**: Visual moderno com tema escuro (#0D0D0D)
- **Efeitos Visuais Sutis**: Partículas animadas, glassmorphism, glow effects
- **Performance Otimizada**: Código puro (HTML, CSS, JS) sem frameworks pesados
- **Totalmente Responsivo**: Mobile-first design
- **Animações Suaves**: Fade-in, parallax, hover effects com easing moderno
- **Cursor Customizado**: Efeito de glow seguindo o mouse
- **SEO Friendly**: Meta tags e estrutura semântica

## 🎨 Paleta de Cores

- **Fundo Principal**: `#0D0D0D`
- **Cards**: `#1A1A1A`
- **Texto Principal**: `#EAEAEA`
- **Texto Secundário**: `#A0A0A0`
- **Cor de Destaque**: `#2ECC71` (Verde)
- **Hover**: `#27AE60`

## 📁 Estrutura do Projeto

```
sync-portfolio/
│
├── index.html          # Estrutura HTML
├── style.css           # Estilos e animações
├── script.js           # Interatividade e efeitos
└── README.md           # Documentação
```

## 🚀 Como Usar

### Opção 1: Abrir Localmente

1. Clone ou baixe os arquivos
2. Abra o arquivo `index.html` no navegador

### Opção 2: Deploy no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em Settings > Pages
4. Selecione a branch `main` e pasta `root`
5. Clique em Save
6. Seu site estará disponível em: `https://seu-usuario.github.io/nome-do-repo`

### Opção 3: Deploy em Outras Plataformas

- **Netlify**: Arraste a pasta para netlify.com/drop
- **Vercel**: Conecte o repositório GitHub
- **Surge**: `npm install -g surge` e depois `surge`

## 🎯 Seções do Site

1. **Hero**: Apresentação principal com call-to-actions
2. **Sobre**: Breve descrição profissional
3. **Serviços**: 3 cards com serviços oferecidos
4. **Projetos**: Galeria com 3 projetos em destaque
5. **Contato**: Botões para Discord e Email

## ⚙️ Personalização

### Alterar Informações Pessoais

Edite o arquivo `index.html`:

- **Nome**: Linha 52 - `<span class="text-gradient">Sync</span>`
- **Headline**: Linha 54
- **Descrição**: Linha 55
- **Email**: Linha 197 - `mailto:contato@sync.dev`
- **Discord**: Linha 187 - Link do Discord

### Alterar Cores

Edite o arquivo `style.css` nas variáveis CSS (linhas 14-19):

```css
:root {
    --bg-primary: #0D0D0D;
    --bg-card: #1A1A1A;
    --text-primary: #EAEAEA;
    --text-secondary: #A0A0A0;
    --accent-primary: #2ECC71;
    --accent-hover: #27AE60;
}
```

### Alterar Imagens dos Projetos

Substitua as URLs do Unsplash (linhas 130, 143, 156 do `index.html`) pelas suas próprias imagens:

```html
<img src="sua-imagem.jpg" alt="Descrição">
```

### Adicionar Mais Projetos

Copie o bloco de código de um projeto existente e cole abaixo, alterando as informações.

## 🔧 Funcionalidades JavaScript

- **Partículas Animadas**: Canvas com 80 partículas conectadas
- **Cursor Glow**: Efeito de luz seguindo o mouse
- **Scroll Suave**: Navegação suave entre seções
- **Fade-in**: Elementos aparecem ao rolar a página
- **Parallax**: Efeito de profundidade no hero
- **Tilt Effect**: Cards inclinam ao passar o mouse
- **Header Dinâmico**: Muda ao rolar a página

## 📱 Responsividade

- **Desktop**: Layout completo com todos os efeitos
- **Tablet**: Grid adaptado e navegação otimizada
- **Mobile**: Layout em coluna única, menu simplificado

## 🎭 Efeitos Visuais

- ✅ Glow verde em botões e elementos importantes
- ✅ Partículas animadas no fundo
- ✅ Gradientes suaves no hero
- ✅ Glassmorphism nos cards
- ✅ Fade-in ao rolar
- ✅ Hover com scale + brilho
- ✅ Scroll suave
- ✅ Cursor customizado
- ✅ Parallax no hero

## 🚀 Performance

- Código otimizado e minimalista
- Sem dependências externas (exceto Google Fonts)
- Partículas reduzidas em mobile (40 ao invés de 80)
- Cursor glow desabilitado em touch devices
- Animações com `requestAnimationFrame`

## 📝 Licença

Livre para uso pessoal e comercial.

## 🤝 Contato

- **Discord**: [Seu Discord]
- **Email**: contato@sync.dev

---

Desenvolvido com foco em conversão e experiência do usuário 🚀
