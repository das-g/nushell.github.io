---
title: math round
categories: |
  math
version: 0.75.0
math: |
  Returns the input number rounded to the specified precision
usage: |
  Returns the input number rounded to the specified precision
---

# <code>{{ $frontmatter.title }}</code> for math

<div class='command-title'>{{ $frontmatter.math }}</div>

## Signature

```> math round --precision```

## Parameters

 -  `--precision {number}`: digits of precision

## Examples

Apply the round function to a list of numbers
```shell
> [1.5 2.3 -3.1] | math round
```

Apply the round function with precision specified
```shell
> [1.555 2.333 -3.111] | math round -p 2
```
