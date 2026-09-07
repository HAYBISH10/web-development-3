# web-development-3


## Project Description

My Budget Tracker is a simple web application built using HTML and CSS.
The application is designed to help users record and view their expenses
in one place.

This project was developed progressively from Week 1 and improved during
Week 2 and Week 3.

---

## Project Features

### 1. Page Structure

The `index.html` file contains the main structure of the Budget Tracker.

It includes:

- Main page heading
- Description
- Add Expense section
- Expense table
- How to use section
- Budgeting tips video

---

### 2. Add Expense Form

The Add Expense section contains a form with:

- Expense name input
- Amount input
- Category dropdown
- Add Expense button

The category dropdown contains five options:

- Food
- Transport
- Rent
- Entertainment
- Other

The form is currently for visual purposes only. JavaScript functionality
will be added in later weeks.

---

### 3. Expense Table

The Expense Table displays sample expense records.

The table uses:

- `<table>`
- `<thead>`
- `<tbody>`
- `<tr>`
- `<th>`
- `<td>`

The table contains four columns:

- Name
- Amount
- Category
- Date

Five sample expense records are included.

---

### 4. Multimedia Content

An image is displayed near the main heading using the `<img>` element.

A budgeting tips video is embedded using an `<iframe>`.

---

### 5. Interactive Elements

The project contains a collapsible "How to use this tracker" section
using `<details>` and `<summary>`.

The table rows also have a hover effect.

The Add Expense button uses `cursor: pointer` so the mouse changes to
a hand when hovering over it.

---

## Week 3 Visual Design

During Week 3, the Budget Tracker was improved using CSS.

### Color Palette

The project uses a consistent blue, white, and light gray color palette.

Main colors include:

- Primary Blue: `#2563eb`
- Dark Blue: `#1d4ed8`
- Background: `#f1f5f9`
- White: `#ffffff`
- Text: `#1e293b`

---

### Typography

Google Fonts are used to improve readability and visual hierarchy.

The project uses:

- Poppins for headings
- Inter for body text, forms, buttons, and table content

---

### Table Styling

The expense table includes:

- Borders
- Cell padding
- Colored header
- Alternating row colors
- Hover effects
- Collapsed borders

---

### Form Styling

The Add Expense form includes:

- Consistent input spacing
- Borders
- Rounded corners
- Focus effects
- Styled button
- Consistent typography

---

### CSS Box Model

The CSS Box Model was used throughout the project.

The project uses:

- `margin` to separate sections
- `padding` to create internal spacing
- `border` to define sections
- `border-radius` to create rounded corners
- `box-sizing` to control element sizing

The main page heading, Add Expense form, and Expense Table are presented
as separate visual cards.

---

## Advanced CSS Selectors

The stylesheet demonstrates several CSS selectors, including:

### Descendant Selector

```css
.expenses-section td
````

### Direct Child Selector

```css
.add-expense-section > form
```

### Position Pseudo-class

```css
tr:nth-child(even)
```

### Negation Pseudo-class

```css
input:not([type="submit"])
```

### Focus Pseudo-class

```css
input:focus
```

### Hover Pseudo-class

```css
tbody tr:hover
```

---

## Technologies Used

* HTML5
* CSS3
* Google Fonts

---

## Project Files

```text
budget-tracker/
│
├── index.html
├── style.css
└── README.md
```

---

## Future Improvements

Future versions of the Budget Tracker will add JavaScript functionality
so users can actually add, display, and manage their expenses.