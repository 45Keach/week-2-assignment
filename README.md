# My Budget Tracker - Week 2

A Week 2 HTML and CSS upgrade of the Personal Budget & Expense Tracker from Week 1.

## What I built

This project continues the Week 1 budget tracker and adds the required Week 2 HTML table, upgraded expense form, multimedia content, interactive details section, and advanced CSS selectors.

## Project files

- `index.html` - Page structure, navigation, expense form, expense table, image, YouTube video, collapsible help section, services, contact section, and footer.
- `style.css` - Visual design, table styling, form styling, responsive layout, hover/focus states, and advanced CSS selectors.
- `README.md` - Project documentation and explanation of each file.

## Week 2 requirements completed

### 1. Expense table
- Correct use of `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>`.
- Columns: Name, Amount, Category, and Date.
- Five hardcoded sample expense rows.
- `border-collapse: collapse`, cell padding, colored header, and `tr:nth-child(even)` alternating rows.

### 2. Add Expense form
- Proper `<form>` wrapper.
- Matching IDs: `expense-name`, `expense-amount`, and `expense-category`.
- Category `<select>` with Food, Transport, Rent, Entertainment, and Other.
- `Add Expense` button with `type="button"`.

### 3. Multimedia
- Budget tracker image using `src`, `alt`, and `width`.
- YouTube `<iframe>` using `width`, `height`, `title`, and `frameborder`.

### 4. Interactive elements
- Collapsible `details` / `summary` section explaining how to use the tracker.
- Table-row hover effect.
- `cursor: pointer` on the Add Expense button.

### 5. Advanced CSS selectors
- Descendant selector: `.expenses-section td`
- Direct child selector: `.expense-inputs > button`
- Position pseudo-classes: `.expense-table tr:nth-child(even)` and `.expense-table tbody tr:first-child`
- Negation pseudo-class: `input:not([type="submit"])`
- Focus states: `input:focus` and `select:focus`
- Hover state: `.expense-table tbody tr:hover`

## Future work

The Add Expense button is intentionally not connected to JavaScript yet. Future weeks can add JavaScript functionality to collect form values and dynamically add expenses to the table.
