# 🍷 Vinharia Agnello – Site Institucional

## 📌 Nome do Projeto

Site Institucional da **Vinharia Agnello**

## 🧠 Descrição

Este projeto foi desenvolvido como parte de um **Check-Point acadêmico**, com o objetivo de aplicar os conhecimentos iniciais de **HTML e CSS** no desenvolvimento de um site estruturado.

O site foi inspirado no caso da **Vinharia Agnello**, uma vinheria familiar localizada em São Paulo que atua há mais de 15 anos oferecendo uma grande variedade de vinhos nacionais e internacionais. Um dos principais diferenciais da vinheria é o atendimento especializado, no qual vendedores orientam os clientes sobre tipos de uva, regiões produtoras, harmonização com alimentos e ocasiões de consumo.

Com os desafios trazidos pela pandemia e a mudança no comportamento dos consumidores, surgiu a necessidade de levar essa experiência também para o ambiente digital, através do desenvolvimento de um portal online.

---

# 🗂 Estrutura do Projeto

O projeto segue a seguinte organização de arquivos:
vinharia-agnello/
│
├── index.html
├── README.md
├── src/
│   ├── assets/
│   │   └── imgs/
│   ├── css/
│   │   ├── style.css
│   │   └── efeitos.css  ← (Adicionado no Check-Point 02)
│   ├── js/
│   └── pages/
│       ├── historia.html
│       ├── produtos.html
│       ├── galeria.html
│       └── contato.html


---

# ✨ Efeitos Visuais (Novidade do Check-Point 02)

Para aprimorar a experiência do usuário e atender aos requisitos da nova etapa do projeto, foram implementados diversos recursos visuais no arquivo `efeitos.css`:

*   **Pseudo-classes:** 
    *   `:hover`: Efeitos dinâmicos de cor, sombra e movimento ao passar o mouse sobre links, botão do banner e imagens da galeria.
    *   `:focus`: Feedback visual com borda dourada e sombra nos campos de entrada do formulário.
    *   `:active`: Mudança de cor nos links de navegação durante o clique.
*   **Pseudo-elementos:**
    *   `::first-letter`: Destaque dourado para a primeira letra do título principal no cabeçalho.
    *   `::first-line`: Destaque na cor da fonte para a primeira linha de texto na seção do banner.
*   **Animações:**
    *   `@keyframes crescer`: Animação contínua e suave (`alternate`) atrelada ao `:hover` do botão de envio do formulário, alterando ciclicamente sua largura.
*   **Transições e Transformações (Extras):** 
    *   `transition`: Suavização nas mudanças de estado (cores e dimensões).
    *   `transform`: Uso de `scale()` para micro-interações na galeria e `translateY()` para flutuação de botões e imagens.

---

# 🌐 Páginas do Site

### 🏠 **Index (Página Inicial)**

Página principal do site, contendo a apresentação da vinheria e navegação para as demais páginas.

### 📖 **História**

Apresenta a história da Vinharia Agnello, sua origem, valores e evolução ao longo dos anos.

### 🍷 **Produtos**

Página dedicada à apresentação de vinhos disponíveis, com imagens e descrições dos produtos.

### 🖼 **Galeria**

Exibe imagens relacionadas ao universo do vinho e da vinheria.

### 📩 **Contato**

Contém um formulário de contato com:

* Campo de **nome**
* Campo de **e-mail**
* **Área de mensagem**
* **Botão de envio**

---

# 🔧 Recursos Utilizados

O projeto inclui os seguintes recursos obrigatórios:

* Estrutura HTML organizada
* Uso de **tags semânticas** (header, nav, main, section, footer)
* **Headings (h1–h6)** e parágrafos
* **Lista HTML (ul ou ol)**
* **Tabela HTML**
* **Formulário de contato**
* **Imagens em todas as páginas**
* **Vídeo incorporado**
* **Menu de navegação funcional**
* **Links internos e externos**
* **Estilização com CSS utilizando classes e IDs**
* **Meta tags para SEO**

  * keywords
  * description

---

# 👥 Integrantes do Grupo

* Felipe Ribas
* Orion Cavalcante França
* Luiz Gonzaga

---

# 🔗 Links do Projeto

📁 **Repositório GitHub:**: https://github.com/orioncavalcante/cp01_front

🌍 **Site publicado no GitHub Pages:**: https://orioncavalcante.github.io/cp01_front/

---

# 📚 Objetivo Acadêmico

Este projeto tem como objetivo praticar conceitos fundamentais de **desenvolvimento web**, incluindo:

* Estruturação de páginas com HTML
* Organização de conteúdo
* Navegação entre páginas
* Aplicação de estilos com CSS
* Trabalho colaborativo utilizando **Git e GitHub**

---

# ✅ Checklist do Projeto

**Check-Point 01:**
* [X] 5 páginas HTML criadas
* [X] Navegação funcional entre páginas
* [X] Uso de headings e parágrafos
* [X] Lista HTML utilizada
* [X] Tabela HTML criada
* [X] Formulário de contato implementado
* [X] Tags semânticas aplicadas
* [X] Meta tags para SEO
* [X] Estilização com CSS
* [X] Imagens em todas as páginas
* [X] Vídeo incorporado
* [X] Links internos e externos funcionando
* [X] Projeto publicado no GitHub Pages

**Check-Point 02 (Atual):**
* [x] Adição de pelo menos 3 pseudo-classes
* [x] Uso de pelo menos 2 pseudo-elementos
* [x] Animação com `@keyframes`
* [x] 2 transformações (`scale`, `rotate`, etc.)
* [x] Transições aplicadas em elementos interativos
* [x] `efeitos.css` criado e importado
* [x] `README.md` atualizado com seção de efeitos

---

🍷 *Projeto desenvolvido para fins acadêmicos.*