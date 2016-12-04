# Derivative-based regular expression matcher

Parse regular expressions using derivatives.

AST for regexes given by:

```
regex := CharRange(start, end)
       | Star(e)
       | Or(e1, e2)
       | Seq(e1, e2)
```
