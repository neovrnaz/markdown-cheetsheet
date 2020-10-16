# Markdown Cheetsheet

---

# Headlines

# H1
```markdown
#
```

## H2
```markdown
##
```

### H3
```markdown
###
```

#### H4
```markdown
####
```

##### H5
```markdown
#####
```

### Paragraphs and line breaks
We create paragraphs by typing the way we would in any other program. Just hit return 
twice to start another paragraph.

Where you see empty space between blocks of text in your Markdown document, you will 
see empty space separating those blocks of text in your formatted HTML document.

I love you without knowing how, or when, or`"  "` (Two spaces )    
from where"  " (Two spaces )    
I love you directly without problems or pride:`"  "` (Two spaces )    
I love you like this because I don't know any`"  "` (Two spaces )    
other way to love    

Neruda, Pablo. "Sonnet 17" The poetry of Pablo`"  "` (Two spaces )  
Neruda, edited by Ilan Stavans, translated by Mark`"  "` (Two spaces )  
Eisner, Farrar, Straus and Giroux, 2005, p. 514.`"  "` (Two spaces )  

### Emphasis and Bolding

#### Italics
*This works* and _works_ too  
```markdown
*This works* and _works_ too
```

#### Bold
**This works** and __works__ too  
```markdown
**This works** and __works__ too
```

#### Bold & Italic
***This is bold and italic***  
```markdown
***This is bold and italic***
```

### Blockquotes
A blockquote sets text apart from the rest of the document. It indicates that the 
text is quoted from another source.

You format a blockquote using the greater than symbol. If you want a blockquote to 
span multiple paragraphs, add the greater than symbol to the line between paragraphs too.

> Markdown is intended to be as easy-to-read and easy-to-write as is feasible.
>
> Readability, however, is emphasized above all else. A Markdown-formatted document 
>should be publishable as-is, as plain text, without looking like it’s been marked up 
>with tags or formatting instructions. — 
>[John Gruber](https://daringfireball.net/projects/markdown/ "Creator of Markdown")
```markdown
>
>
>
```

### Horizontal Rule

---
`---`

## Lists

## Numbered Lists
1. Lvl One
2. Lvl One
    1. Lvl Two
    2. Lvl Two
        1. Three
        2. Three     
```markdown  
1. Lvl One
2. Lvl One
    1. Lvl Two
    2. Lvl Two
        1. Three
        2. Three
```

## Bullet Points
* Lvl One
* Lvl One
    * Lvl Two
    * Lvl Two
        *Lvl Three
        *Lvl Three         
```markdown
* Lvl One
* Lvl One
    * Lvl Two
    * Lvl Two
        *Lvl Three
        *Lvl Three  
```

* ***Bulleted, bold, italicised Lvl One***
    * ***Bulleted, bold, italicised Lvl Two***
```markdown
\* ***Bulleted, bold, italicised Lvl One***
    \* ***Bulleted, bold, italicised Lvl Two***
```
    
## Code
We format code using the backtick character. The backtick is on the same 
key as the tilde on a U.S. English keyboard, which is usually to the left of the number 1 and above the tab key.

You can use a single backtick to create inline code. For example, you 
may type something like this:

#### One-line
To install the latest version of NPM, you can type, `NPM install npm@latest -g`  
```shell script
`NPM install npm@latest -g`
```

#### Multi-line
```ruby
def example_method
  foo = 'foo'
  bar = 'bar'

  print foo + ' ' + bar
end

example_method
```
```
```ruby
def example_method
  foo = 'foo'
  bar = 'bar'

  print foo + ' ' + bar
end

example_method```

```

---

## Links
[Github](https://github.com)
```markdown
[Github](https://github.com)
```

You also have the option to include a title, which appears
when you hover your cursor over the link
[Github](https://github.com "Link to Github")
```markdown
[Github](https://github.com "Link to Github")
```

---
