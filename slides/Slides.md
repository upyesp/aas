---
marp: true
theme: default
footer: 'https://aas.upyesp.org'
---

# Using Markdown to Take Notes and Create Diagrams

## helping the observer

![bg right](https://picsum.photos/800/600)

---

## Slide 1

* Item 1
* Item 2
* Item 3

---

## Slide 2

![Image](https://picsum.photos/800/600)

---

## Slide 3

> This is a quote.

---

## Slide icons

<i class="fa fa-window-maximize"></i> Blog: [https://www.upyesp.org](https://www.upyesp.org)
<i class="fa-brands fa-github"></i> GitHub: [https://github.com/upyesp](https://github.com/upyesp)
<i class="fa-brands fa-mastodon"></i> Mastodon: [https://fosstodon.org/@upyesp](https://fosstodon.org/@upyesp)

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
