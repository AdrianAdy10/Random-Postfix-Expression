# Random Postfix Expression

Generates a random postfix expression.

## Quick Start

### Compile

```sh
javac RandomExpression.java
```

### Run

```sh
java RandomExpression <length = 10>
```

To generate an expression of length `15`,

```sh
java RandomExpression 15
```

By default, the expression length is 10. 

Length won't be exact.

It will output the expression and an evaluation of the expression. For example,

```sh
java RandomExpression 6
```

produces the result

```
18*74*/
Evaluation: 0.2857142857142857
```

Since `(1*8)/(7*4) = 0.2857142857142857`
