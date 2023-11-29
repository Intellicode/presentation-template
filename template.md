---
marp: true
footer: Presentation, date 2024 by Tom Hastjarjanto - [www.tomh.nl/slides](https://www.tomh.nl/slides)
style: |
  :root {
      --background: #F0F5F8;
      --primary: #E5887C;
      --secondary: #A34748;
      --bg-one: #21BDE6;
      --bg-two: #323757;
      --topic-background-color: var(--bg-two);
      --topic-color: var(--background);
      --padding: 12px;
  }

  * {
     font-family: -apple-system, sans-serif;
     color: var(--bg-two);
  }

  footer {
      text-align: right;
      width: calc(100% - 32px);
      left: 0;
      right: 32px;
      font-size: 12px;
  }

  section {
      padding: 0;
      margin: 0;
      justify-content: unset;
      background-color: var(--background);
  }

  section:has(.variant-title) {
      color: var(--background);
      background-color: var(--bg-two);
      justify-content: center;
  }

  section:has(.variant-title) p {
    color: var(--background);
  }

  section:has(.variant-title) h1 {
      color: var(--bg-one);
  }

  section:has(.variant-title) footer {
      display: none;
  }


  .chip {
      border-radius: 10px;
      padding: var(--padding);
      background-color: var(--topic-background-color);
      color: var(--topic-color);
      font-size: 0.7em;
  }

  .variant-two-columns {
      display: flex;
      flex-direction: row;
  }

  .variant-two-columns aside {
      height: 100vh;
      padding: 64px;
      width: 25%;
      display: flex;
      color: var(--bg-one);
      background-color: var(--bg-one);
      flex-direction: column;
      align-content: top;
  }

  .variant-two-columns main {
      flex: 1;
      padding: 64px;
  }

  .variant-one-column {
      padding: 64px;
  }

  .variant-title {
      padding: 64px;
  }

  .blocks {
    flex: 1;
    display: flex;
    margin-top: 64px;
    flex-direction: row;
    font-size: 0.7em;
    gap: 32px;
  }

  .big-emoji {
    font-size: 5em;
    display: block;
    text-align: center;
  }

  .no-bullets ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }
---

<div class="variant-title">

# 🏋️ Title of the presentation

By Tom Hastjarjanto

</div>

---

<div class="variant-one-column">

<span class="chip">Section</span>

## Single column layout

🤷🏻‍♂️ Random bullet 1
👩🏻‍💻 Something on the second line
🎨 Third line

</div>

---

<div class="variant-two-columns">
<aside>

<span class="chip">Section</span>

# Two columns

</aside>
<main>

```python
def hello():
    return 1
```

</main>
</div>

---

<div class="variant-two-columns">
<aside>

<span class="chip">Section</span>

# Two columns

</aside>
<main>

<div class="no-bullets">

- ✅ Best practice
- ✅ Do this as well
- ✅ Another tip
- ❌ Don't do this
- ❌ Or this
- ❌ Definitely not this

</div>

</main>
</div>

---

<div class="variant-one-column">

<span class="chip">Section</span>

# 🧱 Blocks

<div class="blocks">
<div>

<span class="big-emoji">😀</span>

### Title

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sed viverra ipsum, vitae ultrices est.

</div>

<div>

<span class="big-emoji">👾</span>

### Title

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sed viverra ipsum, vitae ultrices est.

</div>

<div>

<span class="big-emoji">⚡️</span>

### Title

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sed viverra ipsum, vitae ultrices est.

</div>

<div>

<span class="big-emoji">🥷</span>

### Title

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sed viverra ipsum, vitae ultrices est.

</div>
</div>

</div>
