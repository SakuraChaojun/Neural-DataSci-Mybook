---
description: Chaojun Ma Demo 4
---

# Writing Math Equations in Jupyter

## Latex 

Jupyiter allows you to write code, text, mathematical formula and pictures in the same document and others can easily understand your ideas and processes by share this document. You may not familiar how to insert math equations in notebook. So, in this demo, I am going to show how to write formula in Jupiter notebook.

First of all, we need change the cell type to markdown. Because latex is not a programming language. 

![Changing cell type ](.gitbook/assets/image%20%281%29.png)

Once the changes are completed, we can try to enter our first formula. Y=a+bx by typing

```r
$ y = a + b x $
```

$$
y=a+bx
$$

You may have noticed that we need to use the ‘$’ in above example, in fact everything between the ‘$’ will be rendered as mathematical symbol.

How about this one: 

```r
$$P(A \mid B) = \frac{ P(B \mid A) P(A) }{ P(B) }$$
```

$$
P(A \mid B) = \frac{ P(B \mid A) P(A) }{ P(B) }
$$

We are not concerned the specifics of Latex wrting rules in here, you may notice that there are two $$ are applying.

Latex gives us two modes in here: **inline mode** and **display mode**. In-line mode, also known as in-text mode, inlays formulas into regular text, along with text. The display mode is to separate the formulas into a single line and center them. By using s_ingle $ means inline mode_ and _$$ for display mode_.

