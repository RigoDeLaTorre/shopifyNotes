# shopifyNotes

## links

- [Yaml](http://www.yamllint.com/) - Checks validity of config.yml
- [Liquid Commands](https://cheat.markdunkley.com/) - Liquid template cheat sheet

### general notes

- Collection: Just a category..cannot create sub-categories
- Variants : size, color etc

### theme commands

- theme watch : basically starts the server and any changes will be made to the live store.
- theme download - if changes are made in shopify, get latest
- theme upload -if you forgot to run theme watch, do this..sort of like git push

### SCSS : Seems to be all in one giant file

- styling: assets/theme.scss.liquid
- functionality: assets/theme.js // ex...user clicks a different color
- config: ????
- locales: looks like language translation files
- section: basically modules...header,footer etc
- snippets: looks like custom styles for the modules..ex adding in a color swatch instead of a normal selection box for the variant color
- templates: self explanatory
