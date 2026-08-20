---
layout: page
title: Where TREE(3) Comes From
permalink: /tree3/
---

### The Tree-Drawing Game

Imagine a simple game where you draw "trees"—collections of nodes (dots) connected by branches (lines). You have a set number of colors available to color the nodes.

The rules of the game are simple:

1. **Step limit:** You are drawing a sequence of trees: Tree 1, Tree 2, Tree 3, and so on.
    
2. **Size limit:** Tree 1 can have at most 1 node. Tree 2 can have at most 2 nodes. Tree n can have at most n nodes.
    
3. **The Homeopathic Rule (No Embeddings):** You cannot draw a tree that "contains" an earlier tree within its structure (technically, no earlier tree can be _infinitary-embeddable_ into a later one preserving color ordering). If an earlier tree can be found tucked inside your new tree, **the game ends immediately.**
    

Kruskal’s Tree Theorem proves that **the game must always end in a finite number of steps**, no matter what choices you make.

TREE(n) represents the **maximum possible number of moves** the game can last if you are allowed to use n colors.

### The Explosion of Growth

- **TREE(1):** With only 1 color, the game ends almost instantly. The max score is **1**.
    
- **TREE(2):** With 2 colors, you can play around a bit longer by building different shapes, but the game quickly hits a wall. The max score is **3**.
    

So we have:

- TREE(1)=1
    
- TREE(2)=3
    

Naturally, you might guess that TREE(3) would be around 7, or maybe 20, or perhaps a few hundred.

Instead, the function experiences a combinatorial explosion so massive that it utterly defies human comprehension.

### How Big is TREE(3)?

TREE(3) is so large that standard scientific notation, power towers, and even Graham’s Number (another notoriously huge math constant) are completely useless to express it.

To put its scale into perspective:

- **Graham's Number** was once in the _Guinness Book of World Records_ as the largest number used in a serious mathematical proof. It is built using "Knuth’s Up-Arrow Notation" (↑), where 3↑↑↑↑3 creates a tower of exponents taller than the observable universe.
    
- TREE(3) is so vast that Graham’s Number is effectively zero by comparison. If you tried to write TREE(3) using up-arrow notation, you couldn't even fit the _number of arrows required_ into our universe.
    

To even express TREE(3) symbolically, computer scientists and mathematicians have to use hyper-advanced fast-growing hierarchies, like the **Veblen function** or **ordinal notation** (Ω).

### The Paradox of TREE(3)

What makes TREE(3) so fascinating to mathematicians and philosophers alike is its paradoxical nature:

1. **It is strictly finite:** It is not infinity. It is a precise, fixed integer.
    
2. **It is completely constructive:** It is defined by simple, finite rules about drawing trees with three colors.
    
3. **It is totally inaccessible:** Even if every subatomic particle in the observable universe were converted into a supercomputer running since the Big Bang, humanity would not be able to compute even a fraction of a percent of its digits.
    

It sits right at the edge of human thought—a perfectly real, finite number that lives completely beyond the physical constraints of our universe.