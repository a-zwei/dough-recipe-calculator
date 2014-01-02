dough-recipe-calculator
=======================

- `Recipe`
  - `name`
  - `unitMass`
  - `quantity`
  - `tags`
  - [`(Ingriedent, percent)`]

- `Ingredient`
  - `name`
  - `flour?`
    flours add up to 100%; others are relative to total flour
  - `priority` or `remainder?`
    automatically adjust when others are changed
  - [`Conversion`]

- `Conversion`
  - `unitA`
  - `unitB`
