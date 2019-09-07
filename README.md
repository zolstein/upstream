# Upstream

Upstream allows users of the fish shell to easily type `'@{u}'`, shorthand in git
for the upstream branch, more quickly, without needing to remember the pesky
quotes around curly braces. (Or, in fact, the pesky curly braces.)

## Installation

```fish
$ omf install https://github.com/zolstein/upstream
````

## Usage

Type `@u` in the command line and this code will replace it with `'@{u}'`.

## Why?

Because I used bash for years and got very used to typing `@{u}` to refer to the
upstream branch. And now having to type `'@{u}'` or `@\{u\}` makes me
irrationally angry. `@u` is even shorter than the bash version, and at least
when I make a mistake I can correct to the nicer version and get a warm fuzzy
feeling, rather than to an uglier version that makes me feel sad.
