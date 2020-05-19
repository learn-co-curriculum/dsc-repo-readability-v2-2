# Readability

So far you have gone from enhanced the ![repository image], then the content of the documents themselves[quick image], and now you examine how to brest annotate the content itelf. 

To fully communicate the quality of your work it needs to be readable. What does readability mean? It means the most important information is highlighted and complex code is explained. Since your analysis is in a Jupyter notebooks, you have the narrative of your analysis and important code in the same place. You will use two different tools to enhance the readability of your notebook: markdown for the narrative and comments for the code. is its ability to combine code and html rendered and enhanced text. With your analysis in a Jupyter notebook, you will enhance the readability of your analysis through code comments and markdown.

## Learning Goals:
- Use markdown to enhance the readability of text
- Use comments to enhance the readability of code

## Markdown

Markdown is a **plain text formatting syntax**, that allows you to format text quickly without needed to write in a text editor. Markdown allows you to quickly  format plain text using special characters like asterisks, dashes, underscores, etc. Markdown enables you to create headers, lists, code blocks and more without lifting your fingers off your keyboard. 

For example, which chunk of text is more readable?

Example A:
[Lindsey - raw text example]

**or**

Example B:
[formatted text exammple]

Example B! But what makes them different? The only difference between examples A and B is that example b adds __Markdown__ syntax to example A. Here is what Example B looks like before it is  rendered:

```
[Lindsey - same content from B, but in this code block so it doesn't render]
```
### Headings example
When you use text editing software like Microsoft Word or Google Docs, you use different level headings to create a consistent heirarchy of information in your documentation. h1 headings  are  the  highest level, like  the title of the document, while h2 and h3 headings are lower in value. You denote a line is a heading by putting a hash mark next to the text, so the title in your analysis:

[snippet  from  notebook  of text]

once you add one hash mark:

[snippet of raw text  with # level]

becomes large and bold:

[updated  snippet of rendered text]

The title of your analysis should have the highest level of header and your section headings, such as "Business Question", "Data Understanding" should have h2 headings. 

### Practice

You can practice your understanding of markdown using the following exercise:
- Examine the text below
[larger text example]

- example the image of rendered text bellow it and find **4 examples** of markdown being used to enhance its readability. 
[image of rendered text]

- Once you have identified four examples, look at the numbered image below to confirm your answers
[another numbered image]

- Review the numbered answers listed below to confirm what was updated. Try updating the text in our messy repo to match the updated formatting.

1. example of link embedding
2. example of heading
3. example  of code block
4. example of bold text

### Further markdown  resources:

 - [GitHub markdown cheat sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
 - [Document design free ebook](https://pressbooks.bccampus.ca/technicalwriting/)
 
 
 ## Code Comments
 
 The [Zen of Python](https://www.python.org/dev/peps/pep-0020/) states that "Readability counts". You covered how to make text more readable, but what about code? Enter code comments and docstrings.
 
 ### Comments
 Code comments can show up three main ways
 
 #### at the top, before code, to say what it will do
 ```
 # Prints the zen of python
 print(this)
 ```
 
  #### on the side, explaining what the code does
  ```
  print(this) # prints the zen of python
  ```
  
  #### in the midst of code, telling python to ignore that section of code and to not run it
  ```
  # print(this)
  print("something else")
  ```
  
  ### Comments example
  
   [Lindsey, I want an example like this, but using our code]   [MIT example](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2011/lectures/MIT6_189IAP11_comment.pdf)
  
  
  ### docstrings
  Docstrings are multi-line comments that usually explain what a _function_, _class_, or _module_ is intended to do. Whenever you type `shift+tab` in a code cell and get the documentation? The documentation is populated by docstrings writen in the code itself. Examine [the source code for the pandas groupby object](https://github.com/pandas-dev/pandas/blob/master/pandas/core/groupby/groupby.py#L1168) to see docstrings in action. 
  
  
  ```
  """docstrings are the  text in tripple quotes
  
  
  that can take multiple lines and still not interfere
  
  
  
  with the code"""
  
  ```
 Docstrings help future employers AND our future selves to understand our code at a later date. It not only makes code more readable, but makes it more _usable_ in the future.
 
 ### Docstrings example
 
 If you wanted to make FUNCTION A and FUNCTION B more readable, you could use BOTH comments and docstrings.
 
 #### Example A code:
 ``` 
 Lindsey
 ```
 
 #### Example A code with comments and docstrings:
 

Try it yourself with Function B in the messy repository!
 
 
 ### Further reading on creating readable code
 - Ultimate guide for readable code, [pep8 standards](https://www.python.org/dev/peps/pep-0008/)
 - If you want more information on docstring expectations look [here](https://www.python.org/dev/peps/pep-0257/)
 
