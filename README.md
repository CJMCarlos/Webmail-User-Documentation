# Webmail-User-Documentation
**EVERYTHING BELOW THIS HEADER IS TEMPORARY**

## Our 4 Main Tasks!
1. Setting up external email client
2. Setting up an identity (Signature, display name, org)
3. Setting up filters
4. Sign up for student discounts and services

## How to use

(Carlos): 
```
python -m [mkdocs command here]
python -m mkdocs serve --livereload
```

## CAUTION! (Developers Only)

Refrain from pressing `Ctrl+S` as Prettier will automatically format the indents that make Admonitions and Content tabs work!

## STYLE GUIDE (REMOVE ONCE FINISHED)

### STEPS

If you want image and gif with numbered steps:
```
1. Click **My Mail** in the top-right corner.

    === "Image"
        ![alt text](assets/Filter2ndStep.png)

    === "Gif"
        Coming soon! [Gif Here]
```

### Colour Pallete
- Main Header: #013F6A (IN BOLD)
- Sub Header: #625D5D
- Text: #013F6A

Note: Please follow the BCIT colour pallete format for our theme.

### CSS REFERENCE
docs/stylesheet/extra.css

All text:
```
.md-typeset {
  color: #333;
}
```

Paragraphs:
```
.md-typeset {
  color: #333;
}
```

Headings:
```
.md-typeset h1 {
  color: blue; or some other custom colour
}
```

Links:
```
.md-typeset a {
  color: #2962ff;
}
```

Content Tabs:
```
.md-nav__link {
  border-bottom: 3px solid transparent; This is an example
}
```