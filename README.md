# Markdown Cheetsheet

---

# Headlines

# H1
`#`
## H2
`##`
### H3
`###`
#### H4
`####`
##### H5
`#####`

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
`*This works* and _works_ too`  

#### Bold
**This works** and __works__ too  
`**This works** and __works__ too`

#### Bold & Italic
***This is bold and italic***  
`***This is bold and italic***`

### Blockquotes
> Markdown is intended to be as easy-to-read and easy-to-write as is feasible.
>
> Readability, however, is emphasized above all else. A Markdown-formatted document should 
be publishable as-is, as plain text, without looking like it’s been marked up with tags 
or formatting instructions. While Markdown’s syntax has been influenced by several existing 
text-to-HTML filters – including Setext, atx, Textile, reStructuredText, Grutatext, and 
EtText – the single biggest source of inspiration for Markdown’s syntax is the format of 
plain text email.  

` > `  
` > `  
` > `

### Horizontal Rule

---
`---`

## Lists

## Numbered Lists

1. Lvl One
    2. Lvl Two

            
```       
1. Lvl One
    2. Lvl Two
        3. Lvl Three
            4. Lvl Four
```

## Bullet Points
  * Lvl One
    * Lvl Two
        * Lvl Three
            * Lvl Four
            
```        
  * Lvl One
    * Lvl Two
        * Lvl Three
            * Lvl Four
```

* ***Bulleted, bold, italicised Lvl One***
    * ***Bulleted, bold, italicised Lvl Two***

1. Lvl One
    * Lvl Two
    * Lvl Two
    
## Code

#### One-line
To install the latest version of NPM, you can type, `NPM install npm@latest -g`
```
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
