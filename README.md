# Subtree-of-another-Tree

Subtree of another Tree

Given the roots of two binary trees, root and subRoot, return true if there is a subtree of root with the same structure and node values as subRoot, and false otherwise.

1️⃣ Find subRoot in tree
2️⃣ Check identical (subTree, node subTree)

Traversal
root.data := subRoot.data

non-identical

1️⃣ node.data ≠ subRoot.data
2️⃣ node = null || subRoot = null
3️⃣ left subtree → non-identical
4️⃣ right subtree → non-identical