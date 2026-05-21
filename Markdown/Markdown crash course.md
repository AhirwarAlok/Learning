# Markdown Crash Course
# sources:
- https://www.youtube.com/watch?v=_PPWWRV6gbA
- https://blog.webdevsimplified.com/2023-06/markdown-crash-course/

# Introduction
Markdown is a markup language used to format text
# Headings
- We use # symbol mark a text as heading
- Markdown has 6 levels of heading. `#` gives us largest heading and `##`, `###` and so on till `######` which gives us smallest heading
- It is similar to what we find in html
    - Example:

      >**`# Heading_text`** will be Largest heading
      >>  # heading_text
      >**`###### Heading_text`** will be Smallest heading
      >>  ###### Heading_text

# Paragraph
- It is the default layout of any set of text in Markdown.
- If you want to separate two set of text in two paragraph then you have to include a blank line in between.
- if you want to have a new line in one paragraph then you can add two spaces at the end of the line and next line will be a new line.
    - Example:
      > This is a paragraph<br>
      >
      >   This is another paragraph. we have a blank line in b/w them.

      > This paragraph has two lines. This first line and has two extra spaces at the end  
      This is second line in the same paragraph

# Extended Markdown.
- Basic version of MD is very limited in the sense of formating and styling of the text.
- There  are extended versions to this base variant. we will cover some of extended versions as well   
  For Example GitHub use it own flavour of markdown  called GitHub flavoured markdown

# Text Styling
## *Bold/Italics*
- These can be generated using one `*` and `_` wrapping your text for italics or two `*` or `_` for bold. In order to use both for same text use \* or \_ thrice.
- Example:

| Formatting                                | Effect                                  |
|-------------------------------------------|-----------------------------------------|
| \*This is italic text\*                   | *This is italic text*                   |
| \_This is italic text\_                   | _This is italic text_                   |
| \** This is bold  text\**                 | **This is bold text**                   |
| \__This is bold text\__                   | __This is bold text__                   |
| \***This is both bold and italic text\*** | ***This is both bold and italic text*** |
| \***This is both bold and italic text\*** | ___This is both bold and italic text___ |

- Generally, it is recommended to use `*`over `_`.

## ~~Strikethrough~~
- For Strikethrough we use \~~ symbol
- Example
  >\~~crossed off\~~ will render as ~~crossed off~~

## Highlight
-To Highlight a text we use ==text== or \<mark>text\</mark>

# Handling Code
- we can do this is two ways:
    1. Inline code
    2. Code Block

  ## Inline Code
    - For inline wrap the code in single <code>`</code> character.
    - Example:  
      This is `Inline Code` within a paragraph.
  ## Code Block
    - to display block of code we need to wrap  in three <code>`</code> character.
    - You can also specify your language of code after three <code>`</code>
    - Example:
        ``` java 
        public Static void main(Str[] args){
            System.out.println("Hello World");
        } 
      ```

# Other elements
## Links
- sqaure bracket is for label of the link. Round bracket will contain your url.
    - for eg:
        - \[This is a link](link.com)  will render like this  
          [This is a link](link.com)

## Images
- it is similar to link.we just need to add ! mark before Square bracket.
    - for eg:
        - \[This is a link](link.com)  will render like this  
          [This is a link](link.com)

## Blockquotes
- it used to quote another source. we use \> before to start to type. you can also nest these.
- for eg:  
  \> this is quote 1  
  \>> this is nested quote
  >this is quote 1
  > > this is nested quote
## Horizontal line
- For horizontal line we need to add three of `-`, `*` or `_` characters on a single line.
- for eg:  
  This is line one
  <HR>
  This is line two

## Lists
- Two types of list:
    * ordered list
    * unordered list
- to create an unordered list add a `-`, `*`, or `+`.
- to create ordered list you can add the number followed by `.`.
- you can also nest these lists.
- for eg:
    - This is an unordered list Of items

    1. This is an ordered list
    2. The numbers do not matter
    3. This says 3
        * This is a nested list
        * Of items
            1. This is a nested
            2. List of items
## Tables
- to make table just try to draw columns using `|` for header and whole body and then row followed by header, it's content should be `-----`

| Col 1 | Col 2   |
|-------|---------|
| This  | is      |
| an    | example |
| table | with    |
| two   | columns |

- use `| -----: | :----: | :--- |` to align right, centre and left of the cell/

| Right | Center | Left |
|------:|:------:|:-----|
|     R |   C    | L    |

## Checklist
- To create a checklist you can add a - `[ ]` or - `[x]` before each item in your list.
- The - `[ ]` will create an unchecked checkbox while the - `[x]` will create a checked checkbox.
- for eg:
    - [ ] Unchecked
    - [x] Checked