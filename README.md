# Module 2 Practice: Stylesheet Refactor

## Most useful refactor

Moved every raw color into customer properties in `:root`. The same hex values were repeated across the header, buttons, cards, callouts, form, and footer. Now the pallette lives in one place, so a brand color change is one edit instead of a search through the whole file. It also made the duplicate button, card, callout, and form control rules identical, which made them easy to merge into single grouped rules. 

## Browser checks

Checked `index.html` 

- **375px** cards and resources stack to one column, nav stacks vertically, hero heading shrinks. 
- **1280px** cards are in three columns, two column resources, horizontal nav, content is centerd at 1100px max. 

At both widths I also checked the nav link hover, the current-page nav highlight, hover on 
`.button`, `.btn`, and `<button>`, and the focus outline on the form fields. 

Testing caught two regressions that were fixed, `body` lost its font settings when the Base section was created, and a `.siteheader` typo removed the current-page nav hightlight. 


## AI Usage
No AI was used. 

Commited files: 