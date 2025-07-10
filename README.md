# Desafio 01: Criando sua primeira Landing Page com HTML e CSS

## 🎯 Sobre o Projeto

Este é um projeto da **Trilha de CSS da DIO**, onde construí uma Landing Page completa utilizando apenas HTML e CSS. O desafio me permitiu aplicar conceitos fundamentais e avançados de estilização web, criando uma página responsiva e moderna.

## 🚀 O Que Aprendi

Durante o desenvolvimento desta Landing Page, adquiri conhecimentos sólidos em diversas áreas do CSS:

### 📚 **Fundamentos CSS**
- **Reset CSS**: Remoção de estilos padrão dos navegadores para controle total
- **Box Model**: Compreensão de margin, padding, border e box-sizing
- **Unidades de Medida**: Uso de rem, vh, px e porcentagens
- **Seletores**: Classes, IDs e pseudo-elementos

### 🎨 **Estilização Avançada**
- **Background Images**: Aplicação de imagens de fundo responsivas
  - `background-size: cover` para cobertura total
  - `background-position: center` para centralização
  - `background-repeat: no-repeat` para evitar repetição

### 🔧 **Layout com Flexbox**
- **Display Flex**: Criação de layouts flexíveis e responsivos
- **Align-items**: Alinhamento vertical de elementos
- **Justify-content**: Alinhamento horizontal de elementos
- **Flex-direction**: Organização em linha ou coluna

### ✨ **Efeitos Visuais**
- **Pseudo-elementos**: Uso de `::before` para criar overlays
- **Text-shadow**: Aplicação de sombras em textos para melhor legibilidade
- **Transitions**: Animações suaves em hover effects
- **Z-index**: Controle de camadas e sobreposição de elementos

### 📱 **Responsividade**
- **Media Queries**: Adaptação para diferentes tamanhos de tela
  - Breakpoint 768px para tablets
  - Breakpoint 480px para dispositivos móveis
- **Design Mobile-First**: Estratégia de desenvolvimento responsivo

### 🎭 **Interatividade**
- **Hover Effects**: Efeitos ao passar o mouse
- **Focus States**: Melhoria de acessibilidade para navegação por teclado
- **Smooth Scroll**: Rolagem suave na página

## 🛠️ **Técnicas Implementadas**

### **1. Overlay com Pseudo-elementos**
```css
.banner::before {
  content: '';
  position: absolute;
  background: rgba(0, 0, 0, 0.4);
  z-index: 1;
}
```

### **2. Layout Responsivo**
```css
.banner {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
```

### **3. Media Queries**
```css
@media (max-width: 768px) {
  .banner h1 {
    font-size: 2rem;
  }
}

## 📋 **Etapas de Desenvolvimento**

1. **Reset CSS** - Preparação do ambiente
2. **Background Image** - Aplicação da imagem de fundo
3. **Layout Structure** - Definição de altura e flexbox
4. **Overlay Creation** - Melhoria de legibilidade
5. **Content Styling** - Estilização de textos e botões
6. **Main Sections** - Desenvolvimento das seções principais
7. **Footer** - Finalização do rodapé
8. **Responsiveness** - Adaptação para dispositivos móveis

## 🌟 **Principais Conceitos Aprendidos**

- **Hierarquia CSS**: Especificidade e cascata
- **Posicionamento**: Relative, absolute e z-index
- **RGBA Colors**: Transparência e sobreposições
- **Typography**: Tamanhos de fonte e espaçamento
- **Performance**: Otimização de imagens e carregamento


## 🚀 **Próximos Passos**

Com este projeto, desenvolvi uma base sólida em CSS que me permitirá:
- Criar layouts mais complexos
- Implementar animações avançadas
- Trabalhar com CSS Grid
- Explorar pré-processadores como Sass
- Desenvolver componentes reutilizáveis

---

**Desenvolvido como parte da Trilha de CSS da DIO** 🎓
