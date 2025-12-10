# DevStudio - Portfólio Corporativo 🚀

Um site profissional, moderno e responsivo para apresentação de projetos, equipe e serviços de uma agência de desenvolvimento com suporte a **dark mode**.

## ✨ Características

### Design Responsivo
- ✅ Totalmente responsivo (desktop, tablet, mobile)
- ✅ Mobile-first approach
- ✅ Testes em todas as resoluções

### Dark Mode 🌙
- ✅ Switch de tema com persistência (localStorage)
- ✅ Transições suaves entre temas
- ✅ Cores otimizadas para cada modo
- ✅ Ícone dinâmico que muda com o tema

### Seções Implementadas
- ✅ **Hero** - Apresentação principal com CTA
- ✅ **Sobre** - Informações da empresa com estatísticas animadas
- ✅ **Serviços** - 6 tipos de serviços apresentados em cards
- ✅ **Projetos** - Galeria com 6 projetos e filtro por categoria
  - Web Development
  - Mobile Apps
  - Design
  - Botão "Ver Projeto" com overlay
- ✅ **Equipe** - Cards de 6 membros da equipe com redes sociais
- ✅ **Contato** - Formulário e informações de contato
- ✅ **Footer** - Links sociais e copyright

### Interatividade
- ✅ Menu hambúrguer para mobile
- ✅ Smooth scroll para navegação
- ✅ Animações ao scroll (Intersection Observer)
- ✅ Filtro de projetos por categoria
- ✅ Formulário com validação
- ✅ Notificações de sucesso/erro
- ✅ Efeitos hover em todos os elementos
- ✅ Contador animado de estatísticas

### Tecnologias
- HTML5 semântico
- CSS3 com variáveis CSS e media queries
- Vanilla JavaScript (sem dependências)
- Local Storage para persistência de tema

## 📁 Estrutura de Arquivos

```
portfolio/
├── index.html      # Estrutura HTML
├── styles.css      # Estilos e dark mode
├── script.js       # JavaScript com interatividade
└── README.md       # Documentação
```

## 🎨 Paleta de Cores

**Tema Claro:**
- Primária: `#667eea` (Azul)
- Secundária: `#764ba2` (Roxo)
- Accent: `#f093fb` (Rosa)
- Fundo: `#f8f9fa` (Cinza claro)
- Texto: `#1a1a2e` (Cinza escuro)

**Tema Escuro:**
- Fundo: `#0f0f1e` (Preto azulado)
- Cards: `#1a1a2e` (Cinza escuro)
- Texto: `#e0e0e0` (Cinza claro)

## 🚀 Como Usar

### Instalação
1. Clone ou baixe o repositório
2. Abra `index.html` em um navegador
3. Pronto! Não há dependências externas

### Personalização

#### Mudar Cores
Edite as variáveis CSS em `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
}
```

#### Adicionar/Editar Projetos
Em `index.html`, adicione novos cards na seção `#projects`:
```html
<div class="project-card" data-category="web">
    <div class="project-image">
        <div class="project-placeholder">🌐</div>
        <div class="project-overlay">
            <a href="#" class="project-link">Ver Projeto</a>
        </div>
    </div>
    <div class="project-info">
        <h3>Seu Projeto</h3>
        <p>Descrição do projeto</p>
        <div class="project-tags">
            <span>Tech 1</span>
            <span>Tech 2</span>
        </div>
        <div class="project-meta">
            <span class="project-year">2024</span>
            <span class="project-client">Cliente: Nome</span>
        </div>
    </div>
</div>
```

#### Adicionar Membros da Equipe
Em `index.html`, adicione novos cards na seção `#team`:
```html
<div class="team-card">
    <div class="team-image">
        <div class="member-avatar">👤</div>
        <div class="member-overlay">
            <div class="social-links-member">
                <a href="#" aria-label="LinkedIn">in</a>
                <a href="#" aria-label="Twitter">tw</a>
                <a href="#" aria-label="GitHub">gh</a>
            </div>
        </div>
    </div>
    <div class="team-info">
        <h3>Nome do Membro</h3>
        <p class="member-role">Cargo</p>
        <p class="member-bio">Descrição breve</p>
    </div>
</div>
```

#### Filtro de Projetos
Os filtros estão no início da seção de projetos:
```html
<div class="projects-filter">
    <button class="filter-btn active" data-filter="all">Todos</button>
    <button class="filter-btn" data-filter="web">Web</button>
    <button class="filter-btn" data-filter="mobile">Mobile</button>
    <button class="filter-btn" data-filter="design">Design</button>
</div>
```

## 📱 Breakpoints Responsivos

- **Desktop**: 1200px+ (layout completo)
- **Tablet**: 768px (ajustes para tela média)
- **Mobile**: 480px (layout mobile)

## 🌙 Dark Mode

O dark mode é automaticamente detectado ou pode ser alternado via botão na navegação.

**Funcionalidades:**
- Salva preferência do usuário em localStorage
- Transições suaves
- Todos os elementos adaptados
- Ícone dinâmico (🌙/☀️)

## ✅ Validações

**Formulário de Contato:**
- Campo de nome obrigatório
- Email obrigatório e validado
- Seleção de serviço obrigatória
- Mensagem obrigatória
- Feedback visual com notificações

## 🎬 Animações

- **Slide In**: Elementos do hero
- **Float**: Formas animadas
- **Morphing**: Forma animada do hero
- **Fade In**: Cards ao scroll
- **Scale**: Efeitos hover
- **Slide Out**: Notificações

## 🔧 Funcionalidades JavaScript

1. **Dark Mode Toggle** - Alterna entre tema claro/escuro
2. **Menu Responsivo** - Hambúrguer para mobile
3. **Smooth Scroll** - Navegação suave
4. **Intersection Observer** - Animações ao scroll
5. **Project Filter** - Filtro de projetos por categoria
6. **Form Validation** - Validação de formulário
7. **Notifications** - Sistema de notificações
8. **Counter Animation** - Números animados nas estatísticas
9. **Parallax Effect** - Efeito de paralaxe no hero

## 📧 Informações de Contato

Os dados de contato podem ser editados em `index.html`:
```html
<a href="mailto:contato@devstudio.com">contato@devstudio.com</a>
<a href="tel:+5511999999999">(11) 99999-9999</a>
```

## 🌐 Deploy

Para fazer deploy:

1. **GitHub Pages**: Coloque os arquivos em um repositório público
2. **Netlify**: Conecte seu repositório GitHub
3. **Vercel**: Deploy automático com Git
4. **Qualquer servidor web**: Coloque os arquivos na pasta pública

## 📝 Notas

- Não há dependências externas
- Compatível com navegadores modernos
- SEO-friendly com HTML semântico
- Performance otimizada
- Acessibilidade com labels e ARIA

## 🤝 Contribuições

Sinta-se livre para personalizar e melhorar!

## 📄 Licença

Uso livre para projetos pessoais e comerciais.

---

**DevStudio - Transformando Ideias em Realidade Digital** 🚀
