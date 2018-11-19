# Nebula-grid

Responsive flexbox-based grid system.

Vanilla CSS. No dependencies.

## How To Use

### With Individual Box Sizing
On the container element, set `class="row"`.
On the immediate child elements, set the class corresponding to the width you want. F.i.: `class="col50"` for a 50% width column, or `class="col66"` for a 66% width column.

### With Predefined Column Combinations
On the container element, set `class="row"`. Then add the class corresponding to the row combination you want to use. For instance: `class="row row25-75"`. 
This will cause the immediate child elements to get the correct width and spacing.

Available column combinations:

#### Two Columns
- 50% - 50% (class: `row50-50`)
- 75% - 25% or 25% - 75% (class: `row25-75` or `row75-25`)
- 66% - 33% or 33% - 66% (class: `row66-33` or `row33-66`)

#### Three Columns
- 33% - 33% - 33% (class: `row33-33-33`)
- 50% - 25% - 25% (class: `row50-25-25`)
- 25% - 50% - 25% (class: `row25-50-25`)
- 25% - 25% - 50% (class: `row25-25-50`)

#### Four Columns
- 25% - 25% - 25% - 25% (class: `row25-25-25-25`)
