

# HTML DO ZERO
## Manual Prático para Iniciantes

**Helton Andrade**

São Paulo – 2026

---
<div class="capa"></div>

## SUMÁRIO

### PARTE I — PRIMEIROS PASSOS
- Criando seu primeiro arquivo HTML
- Escrevendo texto simples
- Transformando texto em título (h1 a h6)
- Criando parágrafos
- Formatando texto (b, strong, i, em)
- Quebra de linha e linha horizontal

### PARTE II — ORGANIZAÇÃO DO CONTEÚDO
- Listas não ordenadas (ul, li)
- Listas ordenadas (ol, li)
- Blocos com div
- Elementos em linha com span

### PARTE III — ELEMENTOS ESSENCIAIS DA WEB
- Inserindo imagens (img)
- Criando links (a, href)
- Caminhos relativos e organização de pastas

### PARTE IV — ESTRUTURA COMPLETA DO HTML
- Estrutura mínima de um documento HTML
- Entendendo html, head, body e title
- Organização correta do código

### PARTE V — TABELAS
- Criando tabelas simples (table, tr, td, th)
- Organização e boas práticas em tabelas

### PARTE VI — FORMULÁRIOS
- Criando um formulário básico (form, input)
- Tipos de input (text, email, password, number)
- Botões e envio de dados

### PARTE VII — ESTRUTURA SEMÂNTICA MODERNA
- O que são tags semânticas
- header, nav, main, section
- article e footer
- Comparação entre div e semântica

### PARTE VIII — INTRODUÇÃO A SCRIPT
- Inserindo JavaScript com script
- Primeira interação com alert()

### APÊNDICE
- A. Produtividade no Visual Studio Code
- B. Emmet — Escrita rápida de HTML
- C. Atalhos essenciais
- D. Estrutura recomendada de pastas
- E. Fluxo de trabalho profissional
<div class="page-break">
---

📘 **HTML DO ZERO**
## Construindo Seu Primeiro Site Passo a Passo

---

## PARTE 1 — COMEÇANDO DO NADA

### 1. Criando o arquivo

Abra o **Visual Studio Code**

Clique em:
**Arquivo → Novo Arquivo**

Salve como:
**index.html**

💡 **Dica Profissional**
Pressione:
**Ctrl + S**

Se aparecer uma bolinha branca na aba, o arquivo não foi salvo.

### 2. Escrevendo algo simples

Digite apenas:
```
Meu primeiro site
```

Salve. Vá até a pasta onde o arquivo está e dê dois cliques nele.

Ele abrirá no navegador.

❓ **O que você vê?**

Apenas o texto:
```
Meu primeiro site
```

Sem tamanho especial.
Sem organização.
O navegador apenas mostra texto comum.

---

## PARTE 2 — FAZENDO O TEXTO FICAR GRANDE

### Transformando em título

Volte ao arquivo.

Substitua por:
```html
<h1>Meu primeiro site</h1>
```

Salve.
Atualize o navegador (F5).

❓ **O que mudou?**

O texto ficou grande.
Está em negrito.
Ganhou destaque.

Agora teste:
```html
<h2>Meu primeiro site</h2>
```

Depois:
```html
<h3>Meu primeiro site</h3>
```

Teste até `<h6>`.

🔎 **O que você percebe?**

Quanto menor o número, maior o destaque.
`<h1>` é o título principal.
`<h6>` é o menor título.

---

## PARTE 3 — CRIANDO TEXTO NORMAL

### Criando um parágrafo

Agora escreva:
```html
<h1>Meu primeiro site</h1>
<p>Este é meu primeiro site criado em HTML.</p>
```

Salve. Atualize.

❓ **O que aconteceu?**

O texto ficou separado.
Virou um bloco organizado.

A tag `<p>` cria um parágrafo.

---

## PARTE 4 — FORMATANDO TEXTO

### Negrito e Itálico

Substitua o parágrafo por:
```html
<p>Este é um texto em <b>negrito</b>.</p>
<p>Este é um texto em <i>itálico</i>.</p>
```

Salve. Atualize.

Agora teste também:
```html
<p>Isso é <strong>muito importante</strong>.</p>
<p>Isso tem <em>ênfase</em>.</p>
```

🔎 **O que você percebe?**

```html
`<b>` deixa visualmente em negrito
`<strong>` indica importância
`<i>` deixa em itálico
`<em>` indica ênfase
```

---

## PARTE 5 — QUEBRAS E LINHAS

### Quebra de linha

Teste:
```html
<p>Primeira linha<br>Segunda linha</p>
```
`<br>` quebra a linha.

### Linha divisória

Teste:
```html
<hr>
```
Ela cria uma linha horizontal.

---

## PARTE 6 — LISTAS

### Lista com marcadores

Digite:
```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

Salve. Atualize.

### Lista numerada

```html
<ol>
  <li>Primeiro</li>
  <li>Segundo</li>
  <li>Terceiro</li>
</ol>
```

---

## PARTE 7 — INSERINDO IMAGEM

### Colocando uma imagem

Você pode testar de duas formas:

**Opção 1 — Usando uma imagem da internet (recomendado para teste):**
```html
<img src="https://via.placeholder.com/300" width="300">
```
Isso cria um quadrado cinza de 300x300 pixels perfeito para testar.

**Opção 2 — Usando uma imagem do seu computador:**
1. Coloque uma imagem na mesma pasta do index.html
2. Escreva:
```html
<img src="nome-da-sua-imagem.jpg" width="300">
```
(Substitua pelo nome correto do arquivo)

Salve. Atualize.

### Ajustando tamanho

`src` é o caminho da imagem.
`width` é a largura.

---

## PARTE 8 — CRIANDO UM LINK

### Criando link clicável

```html
<a href="https://www.google.com">Ir para o Google</a>
```

Salve. Atualize.
Clique.

`href` define o destino.

---

## PARTE 9 — ORGANIZANDO A ESTRUTURA CORRETA

Até agora funcionou.

Mas agora vamos organizar corretamente.

Substitua tudo por:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Meu Site</title>
</head>
<body>
    <h1>Meu primeiro site</h1>
    <p>Estou aprendendo HTML.</p>
</body>
</html>
```

Salve. Atualize.

Visualmente quase nada muda.

Mas agora o documento está estruturado corretamente.

---

## PARTE 10 — ORGANIZAÇÃO COM DIV

### Criando blocos

Adicione dentro do `<body>`:

```html
<div>
    <h2>Sobre mim</h2>
    <p>Eu estou aprendendo HTML.</p>
</div>

<div>
    <h2>Contato</h2>
    <p>Email: exemplo@email.com</p>
</div>
```

`<div>` cria blocos de organização.
Ele não muda visualmente, mas organiza o código.

---

## PARTE 11 — SPAN

### Destacando parte do texto

Teste:
```html
<p>Eu gosto de <span style="color: blue;">programação</span>.</p>
```

`<span>` organiza partes pequenas dentro de uma linha.

---

## PARTE 12 — TABELAS

### Criando tabela simples

```html
<table border="1">
    <tr>
        <th>Nome</th>
        <th>Idade</th>
    </tr>
    <tr>
        <td>João</td>
        <td>30</td>
    </tr>
</table>
```

---

## PARTE 13 — FORMULÁRIOS

### Criando um formulário

```html
<form>
    <label>Digite seu nome:</label>
    <input type="text" name="nome">
    <br>
    <input type="submit" value="Enviar">
</form>
```

💡 **Nota importante:**
Ao clicar em "Enviar", a página pode tentar recarregar ou mostrar um erro. **Isso é normal!**

O HTML cria a **estrutura** do formulário, mas para processar os dados (como enviar um e-mail ou salvar em um banco de dados), precisamos de outra linguagem (como PHP ou JavaScript), que veremos no futuro.

Por enquanto, focamos em criar a estrutura correta.

### Outros tipos de input

```html
<input type="text" placeholder="Texto">
<input type="email" placeholder="Email">
<input type="password" placeholder="Senha">
<input type="number" placeholder="Número">
```

---

## PARTE 14 — TAGS SEMÂNTICAS

### Estrutura moderna

Substitua o conteúdo do `<body>` por:

```html
<header>
    <h1>Meu site</h1>
</header>

<nav>
    Menu principal
</nav>

<main>
    <section>
        <h2>Últimas Notícias</h2>
        
        <article>
            <h3>Lançamento do Novo Site</h3>
            <p>Meu primeiro site está no ar!</p>
        </article>
        
        <article>
            <h3>Aprendendo HTML</h3>
            <p>Estou aprendendo tags semânticas.</p>
        </article>
    </section>
</main>

<footer>
    Rodapé do site
</footer>
```

Elas organizam o **significado** do conteúdo.

---

## PARTE 15 — INTRODUÇÃO A SCRIPT

### Primeira interação

Adicione antes de `</body>`:

```html
<script>
    alert('Olá, mundo!');
</script>
```

Salve. Atualize.

Uma mensagem aparecerá.

💡 **Por que colocar antes do `</body>`?**

Colocamos o `<script>` antes do fechamento do `</body>` para garantir que todo o conteúdo HTML (textos, imagens) seja carregado **primeiro**, e só depois o JavaScript seja executado.

Isso melhora a experiência do usuário, pois a página não "trava" esperando o script carregar.

---

## PARTE 16 — FINALIZANDO

### Seu primeiro mini site completo

Agora combine tudo:

- Título
- Parágrafos
- Lista
- Imagem
- Link
- Formulário
- Estrutura semântica

Você acaba de construir seu primeiro site real.

---

## 📘 PARTE FUNDAMENTAL
### A Estrutura Mínima de um Documento HTML

Até agora escrevemos várias coisas soltas.

Mas agora vamos montar o esqueleto correto de qualquer página HTML.

### 1️⃣ Estrutura mínima obrigatória

Apague tudo e escreva exatamente isto:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Meu Site</title>
</head>
<body>

    <h1>Meu Site</h1>
    <p>Estou aprendendo HTML.</p>

</body>
</html>
```

Salve.
Atualize o navegador.

Visualmente quase nada muda.

Mas agora seu documento está estruturado corretamente.

### 🔎 O que significa cada parte?

Agora vamos entender — de forma simples.

**`<!DOCTYPE html>`**

Diz ao navegador:
"Este documento é HTML5."

É como informar o tipo de documento.
Sem isso, o navegador pode entrar em modo de compatibilidade antigo.

**`<html>`**

É a raiz de tudo.
Tudo que existe na página deve estar dentro dela.

Pense como:
A caixa principal que contém tudo.

**`<head>`**

Não aparece na tela.
Serve para configurações da página.

Exemplo:
- `<title>` (nome da aba)
- Metadados
- Conexão com CSS
- Conexão com JavaScript

**`<title>`**

Define o nome que aparece na aba do navegador.

Experimente mudar o texto do `<title>`, salvar e atualizar.
Você verá a aba mudar.

**`<body>`**

Aqui fica tudo que aparece na tela.
- Textos
- Imagens
- Links
- Tabelas
- Formulários

Se aparece na página, está dentro do `<body>`.

### 🧠 Resumo Simples

- `<html>` → envolve tudo
- `<head>` → configura
- `<body>` → exibe
- `<title>` → nome da aba

Essa é a estrutura mínima de qualquer site.

---
<div class="page-break">
## 📘 TAGS SEMÂNTICAS — O QUE SÃO?

Até agora usamos muitas `<div>`.

Funcionam.
Mas não dizem o que o conteúdo significa.

Tags semânticas dizem:
"Qual é o papel dessa parte da página?"

### Vamos testar

Substitua o conteúdo do `<body>` por:

```html
<header>
    <h1>Meu Site</h1>
</header>

<nav>
    Menu principal
</nav>

<main>
    <section>
        <h2>Últimas Notícias</h2>
        
        <article>
            <h3>Lançamento do Novo Site</h3>
            <p>Meu primeiro site está no ar!</p>
        </article>
        
        <article>
            <h3>Aprendendo HTML</h3>
            <p>Estou aprendendo tags semânticas.</p>
        </article>
    </section>
</main>

<footer>
    Rodapé do site
</footer>
```

Salve. Atualize.

Visualmente quase nada muda.

Mas estruturalmente mudou tudo.

### 📖 Explicação Simples de Cada Tag

**`<header>`**

Cabeçalho da página ou de uma seção.
Normalmente contém:
- Título
- Logo
- Introdução

**`<nav>`**

Área de navegação.
Onde ficam:
- Links do menu
- Botões de navegação

**`<main>`**

Conteúdo principal da página.
Tudo que é o assunto central deve ficar aqui.

Só deve existir um `<main>` por página.

**`<section>`**

Seção temática.
Divide o conteúdo em partes organizadas.

Exemplo:
- Sobre mim
- Serviços
- Contato

**`<article>`**

Usado para conteúdo independente.
Exemplo:
- Um post de blog
- Uma notícia
- Um comentário
<div class="page-break">

**`<footer>`**

Rodapé.
Normalmente contém:
- Direitos autorais
- Informações finais
- Contato

### 🤔 Mas por que usar isso se o `<div>` funciona?

Excelente pergunta.

`<div>` apenas organiza visualmente.
Tags semânticas organizam **significado**.

Isso ajuda:
- Motores de busca (SEO)
- Leitores de tela (acessibilidade)
- Organização profissional do código

### 🧱 Comparação simples

**Com `<div>`:**
```html
<div>Topo</div>
<div>Menu</div>
<div>Conteúdo</div>
<div>Rodapé</div>
```

**Com semântica:**
```html
<header>Topo</header>
<nav>Menu</nav>
<main>Conteúdo</main>
<footer>Rodapé</footer>
```

Qual parece mais profissional?

### 🧩 Estrutura moderna recomendada

Modelo básico real:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Meu Site</title>
</head>
<body>
    <header>
        <h1>Meu Site</h1>
    </header>
    <nav>
        Menu
    </nav>
    <main>
        <section>
            Conteúdo principal
        </section>
    </main>
    <footer>
        © 2026
    </footer>
</body>
</html>
```

Essa é uma estrutura moderna e profissional.

### 🎓 Conclusão Didática

Você começou digitando:
```
Meu primeiro site
```

Agora você entende:
- Estrutura mínima
- Organização correta
- Diferença entre configurar e exibir
- O que são tags semânticas
- Por que usar estrutura moderna

Isso fecha o ciclo do HTML essencial.

---

## 📎 APÊNDICE
### Produtividade no Visual Studio Code

#### 1️⃣ Antes de Tudo: Entenda a Interface

Quando você abre o Visual Studio Code, observe:

- **Barra lateral esquerda** → Arquivos e extensões
- **Área central** → Editor de código
- **Barra inferior** → Informações do arquivo
- **Aba superior** → Arquivos abertos

Se houver uma bolinha branca na aba do arquivo, significa:
**O arquivo ainda não foi salvo.**

#### 2️⃣ Atalhos Essenciais (Memorize Estes Primeiro)

**💾 Salvar Arquivo**
`Ctrl + S`

Sempre salve antes de testar no navegador.

**🔄 Atualizar Navegador**
No navegador: `F5`

Fluxo profissional básico:
**Escreve → Ctrl + S → F5**

**📂 Criar Novo Arquivo**
`Ctrl + N`
Depois salve com `Ctrl + S`.

**❌ Fechar Arquivo**
`Ctrl + W`

**🔎 Buscar dentro do arquivo**
`Ctrl + F`

**🔁 Substituir texto**
`Ctrl + H`
Muito útil quando quiser alterar várias palavras rapidamente.

#### 3️⃣ Organização Profissional de Pastas

Nunca deixe tudo solto.

Crie uma estrutura simples:

```
meu-site/
│
├── index.html
├── imagens/
│   └── foto.jpg
└── css/
```

Para criar pasta:
**Clique com botão direito → Nova Pasta.**

Organização evita erros futuros.

#### 4️⃣ Emmet — O Superpoder do HTML

O VS Code possui uma ferramenta chamada Emmet.

Ela permite escrever código HTML muito mais rápido.

**🔥 Estrutura HTML automática**

Digite:
```
!
```

Depois pressione:
**Enter**

O VS Code cria automaticamente:
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

Isso economiza tempo e evita erros.

**Criar tag rapidamente**

Digite:
```
h1
```

Pressione:
**Tab**

Ele completa:
```html
<h1></h1>
```

**Criar múltiplos elementos**

Digite:
```
ul>li*3
```

Pressione **Tab**.

Resultado:
```html
<ul>
    <li></li>
    <li></li>
    <li></li>
</ul>
```

Extremamente útil.

**Criar estrutura com classes**

Digite:
```
div.container
```

Pressione **Tab**.

Resultado:
```html
<div class="container"></div>
```

#### 5️⃣ Seleção Inteligente

**Selecionar palavra inteira**
Dê dois cliques sobre a palavra.

**Selecionar várias ocorrências**
Selecione uma palavra.
Pressione: `Ctrl + D`

Cada vez que pressionar, seleciona a próxima ocorrência.
Permite editar várias palavras ao mesmo tempo.

#### 6️⃣ Indentação (Organização Visual)

Código organizado é código profissional.

Para organizar automaticamente:
`Shift + Alt + F`

Ele formata o código.

#### 7️⃣ Comentários no HTML

Para comentar uma linha:
Selecione o trecho e pressione: `Ctrl + /`

Ele cria:
```html
<!-- Comentário -->
```

Muito útil para testar sem apagar código.

#### 8️⃣ Divisão de Tela

Você pode abrir dois arquivos lado a lado.
Arraste uma aba para a direita.

Isso ajuda quando:
- Edita HTML
- Edita CSS
- Consulta outro arquivo

#### 9️⃣ Extensões Úteis (Para o Futuro)

Você pode instalar extensões clicando no ícone de blocos na barra lateral.

Exemplos úteis:
- **Live Server** (atualiza navegador automaticamente)
- **Prettier** (formatação automática)

Mas atenção:
**Primeiro aprenda o básico.**
**Depois automatize.**

#### 🔟 Fluxo de Trabalho Profissional

Sempre siga:

1. Escreva o código
2. `Ctrl + S`
3. Vá ao navegador
4. `F5`
5. Observe o resultado
6. Repita dezenas de vezes

É assim que se aprende HTML de verdade.

---

## 🎯 Conclusão do Livro

Você começou criando:
```
Meu primeiro site
```

Agora você sabe:

✔ Estrutura mínima de HTML
✔ Títulos
✔ Parágrafos
✔ Listas
✔ Imagens
✔ Links
✔ Tabelas
✔ Formulários
✔ Tags semânticas
✔ Organização profissional
✔ Produtividade no VS Code

**Você saiu do zero.**

Isso é construção real.

---

© 2026 Helton Andrade – Todos os direitos reservados