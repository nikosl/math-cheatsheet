# math-cheatsheet

 Sets and Logic cheatsheet for markdown

## Math expressions

### Inline

surround with:

* `$`
* `` $` ``.. `` `$ ``

example

```text
$\sqrt{3x-1}+(1+x)^2$
```

$\sqrt{3x-1}+(1+x)^2$

### Multiline block

start a newline and delimit with:

* `$$`
* ` ```math `

example:

```text
$$
\sqrt{3x-1}+(1+x)^2
$$
```

$$
\sqrt{3x-1}+(1+x)^2
$$

### Escape `$`

* `\` inside expression
* `<span></span>` outside expression

## Math

### Sets

Symbol         | Name            | Description                        | LaTeX    I | Examples
---------------|-----------------|------------------------------------|------------|----------------------------------
$\{\}$         | Set             |                                    | \{\}       | $\{123\}$
$\emptyset$    | Empty Set       |                                    | \emptyset  | $\emptyset$
$\in$          | Element         | element part of the set            | \in        | $1\in123$
$\notin$       | not an element  | element not in set                 | \notin     | $4\notin123$
$\mid$, or $:$ | such that       | set builder, for all x : condition | \mid       | $\{x\mid x \gt 1\} = \{2, 3, 4\}$
$\cup$         | union           |                                    | \cup       | $$
$\cap$         | intersection    |                                    | \cap       | $$
$\subset$      | proper subset   |                                    | \subset    | $$
$\subseteq$    | subset          |                                    | \subseteq  | $$
$\supset$      | proper superset |                                    | \supset    | $$
$\supseteq$    | superset        |                                    | \supseteq  | $$

### Logic

Symbol                 | Name   | Description | LaTeX
-----------------------|--------|-------------|--------
$\land$                | And    |             | \land
$\lor$                 | Or     |             | \lor
$\lnot$                | Not    |             | \lnot
$\oplus$, or $\veebar$ | XOr    |             | \loplus
$\forall$              | forall |             | \forall
$\exists$              | exists |             | \exists

### References

[Github - writing mathematical expressions](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
[https://www.geeksforgeeks.org/set-notations-in-latex/](https://www.geeksforgeeks.org/set-notations-in-latex/)
[http://notes.imt-decal.org/sets/cheat-sheet.html](http://notes.imt-decal.org/sets/cheat-sheet.html)
