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
Markdown is essentially plan text, like this.

Your focus on what you want to write.

Later, add some formatting, but only if you want.

# This is a Level 1 Heading
Here is a word in **bold**. An example of *italic*.

## A Level 2 Heading
Lorem ipsum dolor sit amet, consectetur adipiscing
elit, sed do eiusmod tempor incididunt ut labore et
dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip
ex ea commodo consequat.

## Another Level 2 Heading
Some text here, also a link [AAS](https://andoverastronomy.org.uk/).

### Here's A Level 3 Heading
Hi there, hey there, ho there!
```
---

## Slide 3

> This is a quote.

---
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# Mermaid

<div class="mermaid">
gantt
    title Astronomical Events and Observations Plan (Jan-Apr 2025)
    dateFormat  YYYY-MM-DD
    axisFormat  %b %d

    section Key Astronomical Events
    Quadrantids Meteor Shower    :active, ev1, 2025-01-03, 2d
    Total Lunar Eclipse          :ev2, 2025-03-14, 1d
    Venus at Greatest Brightness :ev3, 2025-03-26, 1d
    Partial Solar Eclipse        :ev4, 2025-04-29, 1d

    section Observation Opportunities
    New Moon (Jan)               :milestone, nm1, 2025-01-29, 1d
    Dark Skies (Feb)             :op1, 2025-02-05, 10d
    Best Viewing for Venus       :op2, 2025-03-25, 3d
    Lyrids Meteor Shower         :op3, 2025-04-22, 2d

    section Constraints
    Full Moon (Jan)              :constraint, fm1, 2025-01-15, 1d
    Bright Moon (Feb)            :constraint, fm2, 2025-02-14, 5d
    Cloudy Season (Approximate)  :constraint, cs1, 2025-02-20, 20d
    Full Moon (Apr)              :constraint, fm3, 2025-04-13, 1d

</div>

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

