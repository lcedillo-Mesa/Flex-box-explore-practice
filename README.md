# CSS Flexbox — Guided Discovery Activity

Welcome! In this activity you will **uncomment** your CSS one block at a time and watch your webpage change in the preview.

> **Your goal:** Figure out what each block of CSS is doing — before we talk about it as a class.

## What Does "Uncomment" Mean?

Delete the line that says "delete this line"

**Example — before:**
```css
/* Delete this line 
.header {
  background-color: #2c3e50;
} 
 
Delete this line */
```

**Example — after:**
```css
.header {
  background-color: #2c3e50;
}
```
---

## Step-by-Step Discovery

Work through each step in order. After each one, look at your preview and answer the reflection question in your notes.

---

### Step 1 — Uncomment `.body`

Find this block and uncomment it:

```css
.body {
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
```


**Reflection question:** What do you notice? Did anything move or change?

---

### Step 2 — Uncomment `.header`

Find this block and uncomment it:

```css
.header {
  background-color: #2c3e50;
  color: white;
  padding: 24px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
}
```

Save and look at your preview.

**Reflection question:** Where did the heading and tagline move to? Which property do you think caused that? Delete flex-direction, what happens?  

> **Hint:** Look at `align-items` and `flex-direction`.


---

### Step 3 — Uncomment `.nav`

Find this block and uncomment it:

```css
.nav {
  background-color: #34495e;
  padding: 12px 24px;
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 24px;
}
```

Save and look at your preview.

**Reflection question:** What happened to the nav links? What is creating the space between them? Change the flex-direction to column, what happens?

> **Hint:** Look at `gap` and `flex-direction: row`.

---

### Step 4 — Uncomment `.a-style`

Find this block and uncomment it:

```css
.a-style {
  color: white;
  text-decoration: none;
  font-size: 1rem;
}
```

Save and look at your preview.

**Reflection question:** What changed about the links? Is this flexbox or something else?

> **Hint:** Not every CSS property is flexbox — some are just styling.

---

### Step 5 — Uncomment `.main`

Find this block and uncomment it:

```css
.main {
  flex: 1;
  display: flex;
  gap: 24px;
  padding: 32px 24px;
  background-color: #ecf0f1;
}
```

Save and look at your preview.

**Reflection question:** What happened to the two sections inside main? What do you think `flex: 1` is doing? add flex-direction: column, what happens?

> **Hint:** The two sections are now sitting side by side. Which property caused that?

---

### Step 6 — Uncomment `.section`

Find this block and uncomment it:

```css
.section {
  display: flex;
  flex: 1;
  flex-direction: column;
  gap: 8px;
  background-color: white;
  padding: 24px;
  border-radius: 6px;
}
```

Save and look at your preview.

**Reflection question:** Both sections are now the same width. What property is making that happen? add flex-direction: column

> **Hint:** Look at `flex: 1` on the section — compare it to `flex: 1` on `.main`. 

---

### Step 7 — Uncomment `.footer`

Find this block and uncomment it:

```css
.footer {
  background-color: #2c3e50;
  color: white;
  padding: 16px 24px;
  display: flex;
  justify-content: center;
  align-items: center;
}
```

Save and look at your preview.

**Reflection question:** The footer text is centred. Which two properties are doing that? What is the difference between them?

> **Hint:** One centres left and right. One centres up and down.

---

## You Did It!

Your page should now have:

- A dark header with centred text
- A navigation bar with links side by side
- Two equal sections sitting next to each other
- A dark footer with centred text

---

## Team Discussion

Talk with your partner and write down:

| | Your answer |
|---|---|
| **One discovery** — something you noticed flexbox doing |  |
| **One wondering** — a question you still have |  |

You will share this with the class.

---

## Challenge (Early Finishers)

Can you change one value in the CSS and predict what will happen before you save?

Try these:

- Change `justify-content: center` in `.nav` to `justify-content: space-between` — what happens?
- Change `flex-direction: row` in `.main` to `flex-direction: column` — what happens?
- Remove `flex: 1` from `.section` — what happens to the two columns?

Write down your prediction first, then save and check.
