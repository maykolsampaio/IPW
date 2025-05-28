---
layout: page
title: Tags de Formatação Textual HTML
permalink: /tags-formatacao-textual/
---

# IPW
E-book de Introdução a Programação para Web


# Tags de Formatação Textual HTML

HTML oferece diversas tags para formatação de texto. Esta página apresenta as principais tags com suas funções e exemplos de uso.

## Cabeçalhos (h1 a h6)

> **Função:**  
> Definir títulos e subtítulos hierárquicos em uma página. H1 é o título principal e mais importante, enquanto h6 é o menos importante. São fundamentais para acessibilidade e SEO.

**Exemplo de código:**
```
<h1>Cabeçalho Nível 1</h1>
<h2>Cabeçalho Nível 2</h2>
<h3>Cabeçalho Nível 3</h3>
<h4>Cabeçalho Nível 4</h4>
<h5>Cabeçalho Nível 5</h5>
<h6>Cabeçalho Nível 6</h6>
```

**Resultado:**

# Cabeçalho Nível 1
## Cabeçalho Nível 2
### Cabeçalho Nível 3
#### Cabeçalho Nível 4
##### Cabeçalho Nível 5
###### Cabeçalho Nível 6

---

## Parágrafo (p)

> **Função:**  
> Criar blocos de texto separados, com espaçamento antes e depois. É o elemento básico para organizar conteúdo textual em uma página web.

**Exemplo de código:**
```
<p>Este é um exemplo de parágrafo em HTML. Parágrafos são usados para separar blocos de texto.</p>
```

**Resultado:**

Este é um exemplo de parágrafo em HTML. Parágrafos são usados para separar blocos de texto.

---

## Negrito (strong, b)

> **Função:**  
> **Tag strong** – Indica que o texto tem forte importância, seriedade ou urgência. Possui valor semântico.  
> **Tag b** – Aplica estilo de negrito ao texto sem adicionar significado semântico especial.

**Exemplo de código:**
```
<p>Este texto tem <strong>forte importância</strong> usando a tag strong.</p>
<p>Este texto está em <b>negrito</b> usando a tag b.</p>
```

**Resultado:**

Este texto tem **forte importância** usando a tag strong.  
Este texto está em **negrito** usando a tag b.

---

## Itálico (em, i)

> **Função:**  
> **Tag em** – Indica ênfase no texto, alterando o significado da frase. Possui valor semântico.  
> **Tag i** – Aplica estilo itálico ao texto sem adicionar significado semântico especial. Usado para termos técnicos, expressões idiomáticas, etc.

**Exemplo de código:**
```
<p>Este texto tem <em>ênfase</em> usando a tag em.</p>
<p>Este texto está em <i>itálico</i> usando a tag i.</p>
```

**Resultado:**

Este texto tem _ênfase_ usando a tag em.  
Este texto está em _itálico_ usando a tag i.

---

## Sublinhado (u)

> **Função:**  
> Aplicar sublinhado ao texto. Geralmente usado para indicar erros ortográficos ou nomes próprios em chinês. Deve ser usado com moderação, pois pode ser confundido com links.

**Exemplo de código:**
```
<p>Este texto está <u>sublinhado</u> usando a tag u.</p>
```

**Resultado:**

Este texto está <u>sublinhado</u> usando a tag u.

---

## Tachado (s, del)

> **Função:**  
> **Tag s** – Representa texto que não é mais relevante ou preciso.  
> **Tag del** – Indica texto que foi deletado ou removido, frequentemente usado em controle de alterações.

**Exemplo de código:**
```
<p>Este texto está <s>tachado</s> usando a tag s.</p>
<p>Este texto foi <del>deletado</del> usando a tag del.</p>
```

**Resultado:**

Este texto está <s>tachado</s> usando a tag s.  
Este texto foi <del>deletado</del> usando a tag del.

---

## Sobrescrito (sup) e Subscrito (sub)

> **Função:**  
> **Tag sup** – Exibe texto como sobrescrito, acima da linha base. Usado para expoentes, notas de rodapé, etc.  
> **Tag sub** – Exibe texto como subscrito, abaixo da linha base. Usado em fórmulas químicas, notações matemáticas, etc.

**Exemplo de código:**
```
<p>Fórmula química da água: H<sub>2</sub>O</p>
<p>Equação matemática: E = mc<sup>2</sup></p>
```

**Resultado:**

Fórmula química da água: H<sub>2</sub>O  
Equação matemática: E = mc<sup>2</sup>

---

## Texto pequeno (small)

> **Função:**  
> Representar comentários laterais ou letras pequenas, como direitos autorais, avisos legais ou outros textos que são menos importantes que o texto principal.

**Exemplo de código:**
```
<p>Texto normal com <small>texto pequeno</small> usando a tag small.</p>
```

**Resultado:**

Texto normal com <small>texto pequeno</small> usando a tag small.

---

## Citação (blockquote, q)

> **Função:**  
> **Tag blockquote** – Indicar que o texto é uma citação longa de outra fonte. Geralmente renderizado como um bloco recuado.  
> **Tag q** – Usado para citações curtas, inline. Os navegadores geralmente adicionam aspas automaticamente.

**Exemplo de código:**
```
<blockquote>Esta é uma citação em bloco usando a tag blockquote.</blockquote>
<p>Sócrates disse: <q>Só sei que nada sei</q> usando a tag q.</p>
```

**Resultado:**

> Esta é uma citação em bloco usando a tag blockquote.

Sócrates disse: <q>Só sei que nada sei</q> usando a tag q.

---

## Código (code)

> **Função:**  
> Representar código de computador ou nomes de arquivos dentro de um texto. Normalmente exibido em uma fonte monoespaçada.

**Exemplo de código:**
```
<p>A função <code>console.log()</code> é usada para imprimir mensagens no console.</p>
```

**Resultado:**

A função `console.log()` é usada para imprimir mensagens no console.

---

## Texto pré-formatado (pre)

> **Função:**  
> Preservar espaços em branco, quebras de linha e tabulações exatamente como escritos no código HTML. Útil para mostrar código, poesia ou outros textos onde a formatação é importante.

**Exemplo de código:**
```
<pre>
  Este texto mantém
    a formatação
      exatamente como
    está escrito.
</pre>
```

**Resultado:**
```
  Este texto mantém
    a formatação
      exatamente como
    está escrito.
```

---

## Marca-texto (mark)

> **Função:**  
> Destacar ou marcar texto para referência, como se fosse um marca-texto. Útil para enfatizar partes de texto relevantes para o contexto atual.

**Exemplo de código:**
```
<p>Use a tag mark para <mark>destacar</mark> partes importantes do texto.</p>
```

**Resultado:**

Use a tag mark para <mark>destacar</mark> partes importantes do texto.

---

## Abreviação (abbr)

> **Função:**  
> Indicar uma abreviação ou sigla e fornecer sua explicação completa no atributo title, que aparece como dica quando o usuário passa o mouse sobre o elemento.

**Exemplo de código:**
```
<p>A <abbr title="Organização das Nações Unidas">ONU</abbr> foi fundada em 1945.</p>
```

**Resultado:**

A <abbr title="Organização das Nações Unidas" style="border-bottom: 1px dotted;">ONU</abbr> foi fundada em 1945. (Passe o mouse sobre a sigla)

---

## Texto bidirecional (bdo)

> **Função:**  
> Substituir a direcionalidade do texto, permitindo exibir texto da direita para a esquerda (rtl) ou da esquerda para a direita (ltr). Útil para idiomas como árabe e hebraico.

**Exemplo de código:**
```
<p>Texto normal</p>
<p><bdo dir="rtl">Texto invertido da direita para a esquerda</bdo></p>
```

**Resultado:**

Texto normal  
<bdo dir="rtl">Texto invertido da direita para a esquerda</bdo>

---

## Definição (dfn)

> **Função:**  
> Indicar o termo que está sendo definido dentro de uma definição ou descrição. Geralmente renderizado em itálico. Útil para glossários ou quando se introduz um novo conceito.

**Exemplo de código:**
```
<p>Um <dfn>algoritmo</dfn> é um conjunto de instruções para realizar uma tarefa.</p>
```

**Resultado:**

Um <dfn>algoritmo</dfn> é um conjunto de instruções para realizar uma tarefa.

---

## Quebra de linha (br)

> **Função:**  
> Inserir uma quebra de linha sem iniciar um novo parágrafo. Útil em poesias, endereços ou onde quebras de linha específicas são necessárias.

**Exemplo de código:**
```
<p>Primeira linha<br>Segunda linha</p>
```

**Resultado:**

Primeira linha<br>Segunda linha

---

## Linha horizontal (hr)

> **Função:**  
> Criar uma linha horizontal que separa visualmente conteúdo em uma página. Representa uma quebra temática ou transição entre assuntos.

**Exemplo de código:**
```
<p>Texto antes da linha</p>
<hr>
<p>Texto depois da linha</p>
```

**Resultado:**

Texto antes da linha

---

Texto depois da linha

---

<footer style="margin-top: 40px; text-align: center; border-top: 1px solid #ddd; padding-top: 20px;">
Criado com HTML para demonstrar tags de formatação textual
</footer>
