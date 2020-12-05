---
description: Chaojun Ma Demo 5
---

# Using Gitbook or Jupyter book bulid your own page

Using gitbook or juypter book is a good way to present your work to others, and it doesn’t have to be complicated to do so. So, in this demo, I will still use ‘step by step’ methods to tell you how to build your own page by using Gitbook or jupter book. Before you do this, you need to know some basic git knowledge because both Gitbook and jupter book based on git.

{% hint style="success" %}
You can use DataCamp to learn more about Git like  '[Introduction to Git](https://learn.datacamp.com/courses/introduction-to-git)' 
{% endhint %}

## What is Gitbook

In my opinion, [Gitbook](https://www.gitbook.com) is a modern document sharing platform that allows multiple users to collaborate to create, modified , and shared documents. like our textbook use ‘jupyter Books’ \(I will mention later, if you want to use jupyter Books only please skip to section two\) but this one is more user-friendly, and you don’t need spend much time on set up.

### From create an account to your first page

Based on the platform management requirements, first of all you need an [account](https://app.gitbook.com/join?utm_source=homepage&utm_medium=header&utm_content=signup), this step is not difficult, I suggest you choose ‘sign in with’ Github. so that it is easy to access your page in later.

![You can sign up with your Github ](../.gitbook/assets/image%20%2813%29.png)

After that, you can enter dashboard page, like picture shows

![Dashboard Page](../.gitbook/assets/image%20%2814%29.png)

We can click the ‘Edits’ button to go back to the home page, then we click ‘New’ to select a ‘new page’. The default name of the new page is ‘untitled’ and we can easily change this information in later.

![Select new page](../.gitbook/assets/image%20%288%29.png)

In this new page we can select the page template, for demo purposes we select the ‘basic guide’ template. Note that you can also import word, Markdown, and HTML files directly here but unfortunately ipynb files are not supported. This is also a major drawback of Gitbook in my opinion.

{% hint style="danger" %}
Gitbook not support .ipynb fies 
{% endhint %}

After planning the content, we first select how many Heading are needed and then add it. We click the **‘ ^ ’** button to edit heading and paragraph.

![edit heading and paragraph](../.gitbook/assets/image%20%289%29.png)

After finishing the Heading planning, we can click the ' + ' in the blank to add the specific content. In common use, we can select Code block, image or Math to insert mathematical equations.\( For details, you can see my last[ demo](https://sakurachaojun.gitbook.io/psyo3505/demo/latex)\)

![Code block, image, Math Equation or select paragraph insert word](../.gitbook/assets/image%20%283%29.png)

```text
This is code block 
```

Once the content is written, we need to click ‘Save’ in the lower left corner and ‘merge’. Otherwise, our pages won't be saved on Git.

![Don&apos;t forget merge ](../.gitbook/assets/image%20%285%29.png)

Then we'll choose 'Share' and choose Public from Visibility. The link below is our book, and if you need a specific page you need add page slug \(this will be explained below\) and we have successfully published the first page so far.

![](../.gitbook/assets/image%20%2815%29.png)

{% hint style="success" %}
You can change the link in domain settings 
{% endhint %}

### Share and Design 

If you just want to share a specific page to others, you can click on the '... ' on page and select slug option, here is your link to this page, for example, my book link is [https://sakurachaojun.gitbook.io/psyo3505/](https://sakurachaojun.gitbook.io/psyo3505/) the slug here is my - first - page so the page link is [https://sakurachaojun.gitbook.io/psyo3505/my-first-page](https://sakurachaojun.gitbook.io/psyo3505/my-first-page)

![](../.gitbook/assets/image%20%286%29.png)

We can put multiple pages together and create a group, such as Demo, assignment. Again, we're going to home page select ‘new’ and this time we select add ‘new group’ With the new group we can just drag the page and put it inside.

![ just drag the page and put it inside](../.gitbook/assets/image%20%287%29.png)

{% hint style="danger" %}
 If the page belongs to a group, the page link requires the group name followed by the slug name like [https://sakurachaojun.gitbook.io/psyo3505/demo/latex](https://sakurachaojun.gitbook.io/psyo3505/demo/latex). page latex belong to group demo 
{% endhint %}

Unfortunately, if you want to make the page fancy, like changing the font color, theme of the page, you have to pay for it. Of course, you don't have to pay to make some basic adjustments, such as changing the font family. These Settings can be found on the design page.

![](../.gitbook/assets/image%20%2811%29.png)



