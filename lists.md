
# List
## Definition
* list  in HML is used to group related elements.

---
### Types of List

1. Ordered List (`<ol>`) - sequence list (1,2,3...) (a,b,c,..) (A,B,C....)(i,ii,iii, .....).
2. Unordered List (`<ul>`) - e.g. bullet list (•, •, •…).
3. Description List (`<dl>`) - Used for definitions (like a dictionary)

---

### Ordered List (`<ol>`)

Think of this as a **step-by-step** list, like instructions.

```html copy code
<ol>
  <li>Wake up</li>
  <li>Brush your teeth</li>
  <li>Eat breakfast</li>
</ol>
```

- The browser will show:
  1. Wake up
  2. Brush your teeth
  3. Eat breakfast

### Attributes

- type–Specifies the numbering style (e.g., 1, A, a, I, i).
- start– Specifies the starting number for the ordered list.
- reversed– Displays the list in reverse order.

---

```html
<ol type="I">
  <li>First</li>
  <li>Second</li>
  <li>Third</li>
</ol>
```

- output:
  - I. First
  - II. Second
  - III. Third

Other types you can use:

- `1` (default) → 1, 2, 3...
- `A` → A, B, C...
- `a` → a, b, c...
- `I` → I, II, III...
- `i` → i, ii, iii...

---

### Unordered List (`<ul>`)

This is just a **regular bullet point** list, like a grocery list.

```html
<ul>
  <li>Milk</li>
  <li>Bread</li>
  <li>Eggs</li>
</ul>
```

- output:
  - Milk
  - Bread
  - Eggs

#### Changing Bullet Points in Unordered Lists

```html
<ul style="list-style-type: square;">
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

🔹 **What happens?**

- ■ Item 1
- ■ Item 2

Other options:

- `disc` (default) → ●
- `circle` → ○
- `square` → ■
- `none` → No bullets at all!

---

## Description List (`<dl>`)

This is for **terms and their meanings**—like a dictionary.

```html
<dl>
  <dt>HTML</dt>
  <dd>A language for making websites.</dd>
  <dt>CSS</dt>
  <dd>A language for styling websites.</dd>
</dl>
```

- Output:
  **HTML**  
   A language for making websites.
  **CSS**  
   A language for styling websites.

---

# Forms

### What is a Form in HTML?

A **form** is a way for users to enter information on a website. Think about:

- **Login pages** (Username & Password)
- **Search bars** (Google search)
- **Contact forms** (Name, Email, Message)
- **Sign-up pages** (Email, Password, etc.)

Forms **send data** somewhere (usually to a server).

---
