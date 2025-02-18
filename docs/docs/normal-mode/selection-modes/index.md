---
sidebar_position: 1
---

# Selection Modes

Selection modes [^1] dictates how [core movements](../core-movements.mdx) works.

There are roughly 3 categories of selection modes (not clear-cut):

1. [Syntax tree-based](./syntax-node-based.md)
2. [Regex-based](./regex-based.mdx)
3. [Local/Global](./local-global/index.md)

[^1]: For Vim users, selection mode means text objects.

## Contiguity

Besides the categorization above, selection modes are also separated based on their contiguity.

A selection mode is considered contiguous, if there's no meaningful gap between each of the selections.

A gap is meaningful if it's neither whitespaces only nor separators like `,` or `;`.

The following selection modes are contiguous (exhaustive):

1. Line
1. Column
1. Word
1. Syntax Node
1. Token
