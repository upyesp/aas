---
marp: true
theme: default
footer: 'https://aas.upyesp.org'
---

# Using Markdown to Take Notes and Create Diagrams

## Helping the Observer

![bg right](https://picsum.photos/800/600)

---

## Making Notes Can Be a Challenge Sometimes

- Pen and paper, so nice, but hard to... share / search / edit / backup.
- Proprietary software... learning curve / compatibility / restricted formats.

---

## Why Use Markdown for Notes?

* **Simplicity**: Easy to learn, essentially plain text.
* **Portability**: Works on any platform.
* **Flexibility**: Convert to various formats (PDF, Word, epub...).

---

## Example

```markdown
# This is a Level 1 Heading

This is plan text. Here is a word in **bold**. An example of *italic*.

## A Level 2 Heading
Some text here with a link to [this site](https://example.com).

### A Level 3 Heading

Numbered lists are supported:

1. this is the first item
1. here's the second
1. and the third

Tables are also supported:

| Animal | Sound |
|--------|-------|
| Dog    | woof  |
| Cow    | moo   |
```

---

## Slide 3

> This is a quote.

---

## Slide 4

| Column 1 | Column 2 |
| -------- | -------- |
| Item 1   | Item 2   |
| Item 3   | Item 4   |

---

![bg opacity](https://picsum.photos/800/600?image=53)

## Slide 5

<div class="columns">
<div>

## Left

- 1
- 2

</div>
<div>

## Right

- 3
- 4

</div>
</div>

---

# <!--fit--> Large Text

---

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# Mermaid

<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
</div>
