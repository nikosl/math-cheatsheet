# math-cheatsheet

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [math-cheatsheet](#math-cheatsheet)
  - [Math expressions](#math-expressions)
    - [Inline](#inline)
    - [Multiline block](#multiline-block)
    - [Escape delimiter](#escape-delimiter)
  - [Math](#math)
    - [Sets](#sets)
    - [Logic](#logic)
    - [Examples](#examples)
  - [References](#references)
  - [License](#license)

<!-- /code_chunk_output -->

## Math expressions

Prefer backtick math syntax[^1]. Inline with `$``$` and block with ` ```math`.
Each delimiter could render differently under different platforms.

### Inline

surround with:

- `$`
- `` $` ``.. `` `$ ``

example

```latex
$\sqrt{3x-1}+(1+x)^2$
```

$\sqrt{3x-1}+(1+x)^2$

### Multiline block

start a newline and delimit with:

- `$$`
- ` ```math `

example:

```latex
$$
\sqrt{3x-1}+(1+x)^2
$$
```

$$
\sqrt{3x-1}+(1+x)^2
$$

### Escape delimiter

escape `$` :

- `\` inside expression
  `$\$x$`
- `<span></span>` outside expression

## Math

### Sets

Symbol          | Name              | Description                                      | LaTeX
----------------|-------------------|--------------------------------------------------|---------------
$`\{ \}`$       | Set[^1]           |                                                  | `\{\}`
$\emptyset$     | Empty Set         |                                                  | `\emptyset`
$\in$           | Element           | element part of the set                          | `\in`
$\notin$        | not an element    | element not in set                               | `\notin`
$\mid$, or $:$  | such that         | set builder, for all x : condition               | `\mid`
$\cup$          | union             | a set with elements that exist in A **or** B     | `\cup`
$\cap$          | intersection      | set with elements that exist in A **and** B      | `\cap`
$\subseteq$     | subset            | true if elements of A are in B                   | `\subseteq`
$\subset$       | proper subset     | true if elements of A are in B **and** $A\neq B$ | `\subset`
$\supseteq$     | superset          | A is superset of B when B is a subset of A       | `\supseteq`
$\supset$       | proper superset   | A is superset of B **and** $A\neq B$             | `\supset`
$\times$        | Cartesian product | a set with all combinations from two sets        | `\times`
$A^\complement$ | complement        | a set of elements not in A                       | `^\complement`
$\rightarrow$   | function          | map elements of A, domain, to B, codomain        | `\rightarrow`
$\mapsto$       | function map      | function map to elements                         | `\mapsto`

### Logic

Symbol                 | Name        | Description                                          | LaTeX
-----------------------|-------------|------------------------------------------------------|--------------------
$\land$                | And         | $true \land true = true$                             | `\land`
$\lor$                 | Or          | $true \lor false = true; true \lor true = true$      | `\lor`
$\lnot$                | Not         | $\lnot true = false$                                 | `\lnot`
$\oplus$, or $\veebar$ | XOr         | $true \oplus false = true; true \oplus true = false$ | `\oplus`, `\veebar`
$\forall$              | forall      | $\lnot (\forall x P(x))$                             | `\forall`
$\exists$              | exists      | $\exists x \lnot P(x)$                               | `\exists`
$\iff$                 | iff         | if and only if, $P\implies Q; Q\implies P$           | `\iff`
$\implies$             | implication | $P\implies Q$, Q is true whenever P is true          | `\implies`

### Examples

Symbol          | Name            | Examples
----------------|-----------------|------------------------------------------------------------------------------
$`\{ \}`$       | Set             | $`\{1, 2, 3\}`$
$\emptyset$     | Empty Set       | $\emptyset$
$\in$           | Element         | $`1\in\{1, 2, 3\}`$
$\notin$        | not an element  | $`4\notin\{1, 2, 3\}`$
$\mid$, or $:$  | such that       | $`\{x\mid x > 1\} = \{2, 3, 4\}`$
$\cup$          | union           | $`A\cup B=\{1, 3, 5\}`$
$\cap$          | intersection    | $`A\cap B=\{1, 3, 5\}`$
$\subset$       | proper subset   | $`A=\{1, 2, 3\}; B=\{1, 2\}; A\subset B `$
$\subseteq$     | subset          | $`A=\{1, 2\}; B=\{1, 2\}; A\subseteq B `$
$\supset$       | proper superset | $`A=\{1, 2, 3\}; B=\{1, 2\}; A\supset B B\subset A`$
$\supseteq$     | superset        | $`A=\{1, 2\}; B=\{1, 2\}; A\supseteq B B\subseteq A`$
$\times$        | Cartesian       | $`A=\{1, 2\}$; $B=\{3, 4\}$; $A \times B=\{(1, 3), (2, 3), (1, 4), (2, 4)\}`$
$A^\complement$ | complement      | $`U=\{1, 2, 3\}; A=\{1, 2\}; A^\complement \implies \{3\}`$
$\rightarrow$   | function        | $f(x)=x+2; $ is a function $f: \mathbb{Z} \rightarrow \mathbb{Z}$
$\mapsto$       | function map    | $f(x)=x+2$ can be written as $f:x\mapsto x+2$

## References

- [Github - writing mathematical expressions](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)

- [Wikipedia - logic symbols](https://en.wikipedia.org/wiki/List_of_logic_symbols)

- [Mathjax - tex](https://docs.mathjax.org/en/latest/input/tex/)

- [https://www.geeksforgeeks.org/set-notations-in-latex/](https://www.geeksforgeeks.org/set-notations-in-latex/)

- [http://notes.imt-decal.org/sets/cheat-sheet.html](http://notes.imt-decal.org/sets/cheat-sheet.html)

- [https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

- [https://jdhao.github.io/2019/05/30/markdown2pdf_pandoc](https://jdhao.github.io/2019/05/30/markdown2pdf_pandoc/)

## License

- [Public Domain, CC0 1.0 Universal](https://creativecommons.org/public-domain/cc0/)

[^1]:use **double backslash '\\'** or [use backtick math syntax to render **curly braces {}** correctly](https://github.com/orgs/community/discussions/16993)
