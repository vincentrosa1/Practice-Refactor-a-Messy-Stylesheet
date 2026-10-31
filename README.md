# Module 2 Practice: Stylesheet Refactor

## Most useful refactor

Moved every raw color into customer properties in `:root`. The same hex values were repeated across the header, buttons, cards, callouts, form, and footer. Now the pallette lives in one place, so a brand color change is one edit instead of a search through the whole file. It also made the duplicate button, card, callout, and form control rules identical, which made them easy to merge into single grouped rules. 

