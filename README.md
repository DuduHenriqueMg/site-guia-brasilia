# Site Guia Turístico de Brasília

**Link:** https://duduhenriquemg.github.io/site-guia-brasilia/index.html

## 1. Introdução

Este site foi desenvolvido durante a disciplina de Desenvolvimento Web, com o objetivo de praticar o conteúdo de HTML e CSS aprendido durante as aulas.  

## 2. Estrutura Semântica, Conceitos e Tags HTML Aplicadas no Projeto

A utilização de tags semânticas no HTML é essencial para a estrutura, acessibilidade e otimização para mecanismos de busca. Nesse projeto foram utilizadas as tags `<header>`, `<nav>`, `<main>`, `<section>` e `<footer>`, que definem claramente as diferentes áreas e conteúdos do site.

### Cabeçalho e Navegação
- `<header>`: Representa o cabeçalho da página.
- `<nav>`: Representa um menu de navegação.
- `<ul>` e `<li>`: Lista não ordenada contendo os links do menu de navegação, representa uma lista de elementos.
- `<a href="...">`: Links para as páginas e seções do projeto.

### Conteúdo Principal
- `<main>`: Representa o conteúdo principal da página.
- `<section>`: Divide o conteúdo em seções com temas especifícos.
- `<h1>` a `<h5>`: Tags para títulos e subtítulos, sendo `<h1>` o mais importante e `<h5>` menos.
- `<p>`: Tag para parágrafos.

### Imagens
- `<img src="..." alt="...">`: Imagens com atributo (`alt`) que é essencial para acessibilidade da página.

### Rodapé
- `<footer>`: Rodapé da página, onde geralmente contém informações complementares ou formulários de contato/newsletter, nesse projeto contém um formulário para inscrição na newslwtter.

### Formulários
- `<form>`: Representa um formulário para o usuário inserir dados.
- `<label>`: Textos descritivos descrevendo os campos do formulário.
- `<input>`: Elemento para entrada de texto, números e outros tipos de dados.
- `<select>` e `<option>`: Elemento para selecionar opções.
- `<button type="submit">`: Botão para enviar o formulário.

### Classes e IDs
- Classes (`class`): Usadas para estilizar e aplicar comportamentos comuns a vários elementos com CSS.
- IDs (`id`): Identificam exclusivamente um único elemento para estilização e interações específicas do elemento com JavaScript ou CSS.

### Fontes Externas
- Google Fonts: Inclusão de fontes personalizadas para melhorar a estética visual do texto.

### Boas Práticas Utillizadas
- Uso de tags semânticas (`header`, `nav`, `main`, `section`, `footer`) para melhorar a acessibilidade e otimização para mecanismos de busca (SEO).
- Estrutura clara com títulos e subtítulos para facilitar leitura e navegação.

## 3. Estrutura e Organização do CSS

O CSS foi organizado conforme as classes definidas no HTML, permitindo a estilização de elementos comuns entre as páginas e facilitando a manutenção do código. IDs e Classes especificadas permitem uma estilização flexível.

### Principais Conceitos Utilizados no CSS

- **Flexbox:** Utilizado na navbar para alinhar e distribuir elementos com flexibilidade.
- **Grid:** Utilizado nos cards e no formulário para uma distribuição dinâmica e responsiva dos elementos.
- **Unidades Relativas (rem):** Foram utilzadas unidades relativas (`rem`) para facilitar escalabilidade, mantendo a consistência de tamanhos em diferentes resoluções e aumentando a acessibilidade para usuários.
- **Transições e Animações:** Efeitos suaves implementados nos links, cards e botões para melhorar a interação nas páginas.

## 4. Responsividade e Acessibilidade

### Responsividade

As propiedades CSS (Grid,FlexBox e rem) utilizadas no projeto proporcionam uma boa responsividade adaptando o site para diferentes telas. Também foi utilizado media queries para garantir que o conteúdo seja bem apresentado em diferentes dispositivos, adotando breakpoints específicos:

- **Janelas Acima de 990px**: Layout dos cards em três colunas, para desktop.
- **Janelas Entre 990px e 700px**: Ajuste dos cards para duas colunas, para telas menores.
- **Janelas Menores que 700px**: Layout com coluna única, para telas de dispositivos movéis. A navbar também muda para um layout vertical, se adptando a tela.

O Grid utilizado com `auto-fit` e `minmax()` proporciona uma grande flexibilidade ajustando automaticamente a quantidade de colunas conforme o espaço disponível.

### Acessibilidade

Elementos importantes de acessibilidade foram utilizados:

- Textos alternativos (`alt`) para todas as imagens, facilitando a utilização de leitores de tela.
- Contraste adequado entre texto e fundo.
- Uso de tamanhos de fonte e espaçamento (`rem`) que permitem melhor leitura e interação para usuários com ajustes específicos no navegador ou diferentes telas.

Esses elementos de acessibilidade visam garantir que o site seja acessível e fácil de usar para todos os públicos.

