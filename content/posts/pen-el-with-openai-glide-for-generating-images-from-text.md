+++
title = "Pen.el with OpenAI GLIDE for generating images from text"
author = ["Shane Mulligan"]
date = 2022-01-30T00:00:00+13:00
keywords = ["pen", "openai", "glide", "surreal", "melee"]
draft = false
+++

Here are some surreal and surreptitious images
of cat strawberries. I hope it makes you
happy!


## Summary {#summary}

I add `GLIDE` to `Pen.el` as a prompting
engine, to generate images given a text
prompt.

colab
: <https://colab.research.google.com/github/openai/glide-text2im/blob/main/notebooks/text2im.ipynb>

The one with a red background and a cat resting its neck upon a strawberry blending into the background is what is known as a `surrealeptitious` strawberry.
![](/ox-hugo/cat-strawberries-2.png)


## Glossary {#glossary}

surrealeptitious
: <https://www.urbandictionary.com/define.php?term=surrealeptitious>

{{< figure src="/ox-hugo/urban-surrealeptitious.png" >}}


## Examples {#examples}

{{< highlight text "linenos=table, linenostart=1" >}}
A surreal painting of a cat and a strawberry
{{< /highlight >}}

Love the tabby.
![](/ox-hugo/catandstrawberry.png)

{{< highlight text "linenos=table, linenostart=1" >}}
A surreal painting of a cat and a surreptitious strawberry
{{< /highlight >}}

Oh I looove these cat-strawberries. Yo!
![](/ox-hugo/surreal-cat-strawberry-1.png)

The first one here with strawberries for teeth is equally as impressive as the next!
![](/ox-hugo/surreal-cat-strawberry.png)

The first one kinda scares me and that is good.
![](/ox-hugo/surreal-cat-strawberries-4.png)

Strawberries for feet? Hmm
![](/ox-hugo/cat-strawberries-5.png)

Love it.
![](/ox-hugo/cat-strawberries-6.png)


## Me and Flo {#me-and-flo}

This is my cat.
![](./2022-01-30-192651.jpg)


## `Pen.el` code {#pen-dot-el-code}

engine
: <http://github.com/semiosis/engines/blob/master/engines/glide.engine>


prompt
: <http://github.com/semiosis/prompts/blob/master/prompts/given-a-text-prompt-visualise-it-1.prompt>


openai example
: <https://github.com/openai/glide-text2im/blob/main/notebooks/text2im.ipynb>


pen script
: <http://github.com/semiosis/pen.el/blob/master/scripts/glide.py>