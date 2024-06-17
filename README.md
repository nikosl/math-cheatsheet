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
  - [References](#references)
  - [License](#license)

<!-- /code_chunk_output -->

 Sets and Logic cheatsheet for markdown

## Math expressions

### Inline

surround with:

- `$`
- `` $` ``.. `` `$ ``

example

```text
$\sqrt{3x-1}+(1+x)^2$
```

$\sqrt{3x-1}+(1+x)^2$

### Multiline block

start a newline and delimit with:

- `$$`
- ` ```math `

example:

```text
$$
\sqrt{3x-1}+(1+x)^2
$$
```

$$
\sqrt{3x-1}+(1+x)^2
$$

### Escape delimiter

escape `$` :

- `\` inside expression, `$\$x$`
- `<span></span>` outside expression

## Math

### Sets

Symbol          | Name              | Description                                                  | LaTeX        | Examples
----------------|-------------------|--------------------------------------------------------------|--------------|----------------------------------------------------------------------------
$\{ \}$         | Set               |                                                              | \\{\\}       | $\{1, 2, 3\}$
$\emptyset$     | Empty Set         |                                                              | \emptyset    | $\emptyset$
$\in$           | Element           | element part of the set                                      | \in          | $1\in\{1, 2, 3\}$
$\notin$        | not an element    | element not in set                                           | \notin       | $4\notin\{1, 2, 3\}$
$\mid$, or $:$  | such that         | set builder, for all x : condition                           | \mid         | $\{x\mid x \gt 1\} = \{2, 3, 4\}$
$\cup$          | union             | a set with elements that exist in A **or** B                 | \cup         | $A\cup B=\{1, 3, 5\}$
$\cap$          | intersection      | set with elements that exist in A **and** B                  | \cap         | $A\cap B=\{1, 3, 5\}$
$\subset$       | proper subset     | true if elements of A are in B **and** $A\neq B$             | \subset      | $A=\{1, 2, 3\}; B=\{1, 2\}; A\subset B $
$\subseteq$     | subset            | true if elements of A are in B                               | \subseteq    | $A=\{1, 2\}; B=\{1, 2\}; A\subseteq B $
$\supset$       | proper superset   | A is superset of B when B is a subset of A **and** $A\neq B$ | \supset      | $A=\{1, 2, 3\}; B=\{1, 2\}; A\supset B B\subset A$
$\supseteq$     | superset          | A is superset of B when B is a subset of A                   | \supseteq    | $A=\{1, 2\}; B=\{1, 2\}; A\supseteq B B\subseteq A$
$\times$        | Cartesian product | a set with all combinations from two sets                    | \times       | $A=\{1, 2\}$; $B=\{3, 4\}$; $A \times B=\{(1, 3), (2, 3), (1, 4), (2, 4)\}$
$A^\complement$ | complement        | a set of elements not in A                                   | ^\complement | $U=\{1, 2, 3\}; A=\{1, 2\}; A^\complement \implies \{3\}$
$\rightarrow$   | function          | map elements of A, domain, to B, codomain                    | \rightarrow  | $f(x)=x+2; $ is a fuction $f: \Z \rightarrow \Z$
$\mapsto$       | function map      | function map to elements                                     | \mapsto      | $f(x)=x+2$ can be written as $f:x\mapsto x+2$

### Logic

Symbol                 | Name        | Description                                 | LaTeX
-----------------------|-------------|---------------------------------------------|---------
$\land$                | And         |                                             | \land
$\lor$                 | Or          |                                             | \lor
$\lnot$                | Not         |                                             | \lnot
$\oplus$, or $\veebar$ | XOr         |                                             | \loplus
$\forall$              | forall      |                                             | \forall
$\exists$              | exists      |                                             | \exists
$\iff$                 | iff         | if and only if, $P\implies Q; Q\implies P$  | \iff
$\implies$             | implication | $P\implies Q$, Q is true whenever P is true | \implies

## References

- [Github - writing mathematical expressions](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)

- [https://www.geeksforgeeks.org/set-notations-in-latex/](https://www.geeksforgeeks.org/set-notations-in-latex/)

- [http://notes.imt-decal.org/sets/cheat-sheet.html](http://notes.imt-decal.org/sets/cheat-sheet.html)

- [https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

## License

- [Public Domain, CC0 1.0 Universal](https://creativecommons.org/public-domain/cc0/)
