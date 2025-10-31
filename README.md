# 🎓 UniALFA Umuarama - Site Institucional

Site institucional moderno e responsivo para a UniALFA Umuarama, desenvolvido com **Bootstrap 5** e boas práticas de desenvolvimento front-end.

## 🌟 Visão Geral

Este projeto apresenta um site institucional completo para uma faculdade, incluindo páginas de apresentação, cursos, infraestrutura e contato. O design é moderno, totalmente responsivo e focado na experiência do usuário.

### 🖥️ Demonstração

- **Homepage**: Apresentação institucional com hero section e destaques
- **Cursos**: Catálogo interativo com modais detalhados
- **Infraestrutura**: Galeria de facilidades e informações sobre bolsas
- **Contato**: Formulário funcional e informações de localização

## 🚀 Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica moderna
- **CSS3** - Estilização avançada com variáveis e animações
- **Bootstrap 5.3.3** - Framework CSS responsivo
- **Bootstrap Icons 1.11.3** - Biblioteca de ícones vetoriais
- **JavaScript** - Interatividade e componentes dinâmicos

### Recursos Implementados
- ✅ **Design Responsivo** - Funciona em todas as telas
- ✅ **Acessibilidade (A11y)** - WCAG 2.1 compliant
- ✅ **SEO Otimizado** - Meta tags e estrutura semântica
- ✅ **Performance** - Carregamento otimizado
- ✅ **Cross-browser** - Compatível com navegadores modernos

## 📁 Estrutura do Projeto

```
trabalho_boot/
│
├── 📄 index.html              # Página inicial
├── 📄 cursos.html             # Página de cursos
├── 📄 infraestrutura.html     # Infraestrutura e bolsas
├── 📄 contato.html            # Página de contato
├── 📄 README.md               # Documentação
│
├── 📁 css/
│   ├── style.css              # CSS da página inicial
│   ├── cursos.css             # CSS específico de cursos
│   ├── infra.css              # CSS da infraestrutura
│   └── contato.css            # CSS do formulário de contato
│
├── 📁 img/
│   ├── hero-campus.jpg        # Banner principal
│   ├── curso-*.jpg            # Imagens dos cursos
│   ├── foto-*.jpg             # Fotos da infraestrutura
│   └── whatsapp.png           # Ícone WhatsApp FAB
│
└── 📁 js/
    └── script.js              # JavaScript personalizado
```

## 🎨 Design System

### Paleta de Cores
```css
:root {
  --brand-primary: #002855;   /* Azul escuro principal */
  --brand-cyan: #00C8FF;      /* Ciano para destaques */
  --brand-light: #f5faff;     /* Azul claro para fundos */
}
```

### Tipografia
- **Fonte Principal**: `system-ui, -apple-system, Segoe UI, Roboto`
- **Hierarquia**: Bootstrap typography scale (display, h1-h6)
- **Pesos**: Normal (400), Semibold (600), Bold (700)

### Componentes Bootstrap Utilizados
- **Navbar** - Navegação responsiva
- **Cards** - Apresentação de cursos e conteúdos
- **Carousel** - Galeria de imagens da infraestrutura
- **Modals** - Detalhes expandidos dos cursos
- **Forms** - Formulário de contato estilizado
- **Buttons** - CTAs e navegação
- **Grid System** - Layout responsivo 12 colunas

## 📱 Responsividade

### Breakpoints
- **Mobile**: < 576px
- **Tablet**: 576px - 768px
- **Desktop**: > 768px

### Adaptações por Tela
- **Mobile**: Menu hambúrguer, layout vertical, FAB otimizado
- **Tablet**: Grid 2 colunas, espaçamentos ajustados
- **Desktop**: Layout completo, animações avançadas

## ♿ Acessibilidade

### Recursos Implementados
- **HTML Semântico**: `<header>`, `<main>`, `<nav>`, `<footer>`
- **ARIA Labels**: Descrições para leitores de tela
- **Alt Text**: Imagens com descrições detalhadas
- **Contraste**: Cores atendem WCAG 2.1 AA
- **Navegação por Teclado**: Todos os elementos acessíveis
- **Landmarks**: Estrutura clara para navegação assistiva

### Exemplo de Alt Descritivo
```html
<!-- ❌ Genérico -->
<img src="biblioteca.jpg" alt="Biblioteca">

<!-- ✅ Descritivo -->
<img src="biblioteca.jpg" alt="Biblioteca moderna da UniALFA Umuarama com amplo acervo e espaços de estudo">
```

## 🛠️ Recursos Técnicos

### CSS Avançado
- **Custom Properties** - Variáveis CSS para consistência
- **Flexbox & Grid** - Layouts modernos e flexíveis
- **Animations & Transitions** - Micro-interações suaves
- **Media Queries** - Responsividade granular
- **Sticky Footer** - Footer sempre no final da página

### JavaScript Features
- **Bootstrap Components** - Navbar, modals, carousel
- **Smooth Scrolling** - Navegação suave entre seções
- **Form Validation** - Validação client-side
- **WhatsApp Integration** - FAB com link direto

### Performance
- **CSS Minificado** - Carregamento otimizado
- **Imagens Otimizadas** - `object-fit: cover` para proporções
- **Lazy Loading** - Carregamento progressivo
- **CDN Resources** - Bootstrap via CDN para cache

## 📝 Páginas Detalhadas

### 🏠 Homepage (index.html)
- **Hero Section**: Banner com call-to-action
- **Features**: Por que estudar na UniALFA
- **Cursos Destaque**: Cards com cursos principais
- **Infraestrutura**: Carousel de imagens
- **Avaliações**: Conceito MEC e depoimentos

### 📚 Cursos (cursos.html)
- **Grid de Cursos**: Layout responsivo com cards
- **Modals Detalhados**: Informações completas por curso
- **Áreas de Atuação**: Lista de possibilidades profissionais
- **CTAs**: Botões para inscrição e mais informações

### 🏢 Infraestrutura (infraestrutura.html)
- **Carousel Principal**: Fotos das instalações
- **Facilidades**: Grid com imagens e descrições
- **Bolsas de Estudo**: Informações sobre financiamentos
- **Localização**: Detalhes do campus

### 📞 Contato (contato.html)
- **Formulário**: Campos validados e responsivos
- **Informações**: Endereço, telefone, redes sociais
- **Sticky Footer**: Solução para páginas com pouco conteúdo
- **WhatsApp FAB**: Acesso rápido ao atendimento

## 🚀 Como Executar

### Pré-requisitos
- Navegador web moderno
- Editor de código (recomendado: VS Code)
- Servidor local (opcional, para desenvolvimento)

### Instalação
1. **Clone/Download** do repositório
```bash
git clone [url-do-repositorio]
cd trabalho_boot
```

2. **Abrir no Navegador**
```bash
# Método 1: Duplo clique no index.html
# Método 2: Servidor local (VS Code Live Server)
# Método 3: Python server
python -m http.server 8000
```

3. **Acessar o Site**
```
http://localhost:8000
# ou
file:///caminho/para/index.html
```

## 🔧 Desenvolvimento

### Estrutura de CSS
Cada página possui seu próprio arquivo CSS para facilitar manutenção:

```css
/* Ordem de importação recomendada */
1. Variáveis CSS (:root)
2. Reset/Base styles
3. Layout components
4. Page-specific styles
5. Media queries
```

### Convenções de Nomenclatura
- **Classes CSS**: `kebab-case` (ex: `.navbar-customed`)
- **IDs**: `camelCase` (ex: `#infraCarousel`)
- **Arquivos**: `lowercase` com hífens (ex: `infraestrutura.html`)
- **Imagens**: Descritivas (ex: `foto-biblioteca.jpg`)

### Git Workflow
```bash
# Desenvolvimento
git checkout -b feature/nova-funcionalidade
git add .
git commit -m "feat: adiciona nova funcionalidade"
git push origin feature/nova-funcionalidade

# Produção
git checkout main
git merge feature/nova-funcionalidade
```

## 📊 Checklist de Qualidade

### ✅ HTML
- [ ] Estrutura semântica (header, main, footer)
- [ ] Meta tags completas
- [ ] Alt text em todas as imagens
- [ ] ARIA labels onde necessário
- [ ] Validação W3C

### ✅ CSS
- [ ] Variáveis CSS organizadas
- [ ] Media queries implementadas
- [ ] Animações suaves
- [ ] Fallbacks para navegadores antigos
- [ ] CSS limpo e comentado

### ✅ JavaScript
- [ ] Componentes Bootstrap funcionais
- [ ] Validação de formulários
- [ ] Tratamento de erros
- [ ] Performance otimizada

### ✅ Acessibilidade
- [ ] Contraste adequado (AA)
- [ ] Navegação por teclado
- [ ] Leitores de tela compatíveis
- [ ] Landmarks HTML5
- [ ] Foco visível

### ✅ Performance
- [ ] Imagens otimizadas
- [ ] CSS/JS minificados
- [ ] Carregamento assíncrono
- [ ] Cache headers
- [ ] Lighthouse Score > 90

## 🤝 Contribuição

### Como Contribuir
1. **Fork** do repositório
2. **Crie** uma branch para sua feature
3. **Desenvolva** seguindo os padrões do projeto
4. **Teste** em diferentes dispositivos/navegadores
5. **Envie** um Pull Request detalhado

### Padrões de Commit
```bash
feat: nova funcionalidade
fix: correção de bug
docs: atualização de documentação
style: mudanças de estilo (CSS)
refactor: refatoração de código
test: adição/correção de testes
```

## 📞 Contato & Suporte

### Desenvolvedor
- **GitHub**: [@gladson623](https://github.com/gladson623)
- **Projeto**: UniALFA Umuarama Website

### Instituição
- **Site**: UniALFA Umuarama
- **Endereço**: Av. Paraná, 7327 — Zona III — Umuarama-PR
- **WhatsApp**: +55 (44) 99116-8932

---

## 📄 Licença

Este projeto foi desenvolvido como trabalho acadêmico para demonstração de habilidades em desenvolvimento front-end com Bootstrap 5.

**Tecnologias**: HTML5, CSS3, Bootstrap 5, JavaScript  
**Foco**: Responsividade, Acessibilidade, Performance, Semântica  
**Status**: ✅ Completo e Funcional

---

⭐ **Se este projeto foi útil, considere dar uma estrela no repositório!**