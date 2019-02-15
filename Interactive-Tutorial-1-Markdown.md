# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

My name is Desiree and I'm a senior majoring in environmental engineering.

I love AguaClara!

## Headers

Make a 3rd level header with your name:

### Desiree Sausele

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*water*, **sustainability**, ***environmentalism***, ~~serendipity~~

## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. Run a successful experiment
    1. The team must finish making a new sed tube before we can run a proper experiment.
2. Complete this tutorial
    1. I would like to successfully finish this assignment.
3. Make more friends in AguaClara
    1. I want to go to more AguaClara events to get to know more of the new members!

- CEE 4520
- BEE 4710
- BEE 3922

## Links

Write a sentence describing your major, and insert a link to your major's department website:

Environmental engineering seeks to address a number of environmental issues caused by humans. Read more about it [on the major's website](https://enve.cornell.edu/).

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/Images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)


  ![CornellSeal](./Images/Cornell_University_seal.png)

  ![CornellSeal](https://github.com/AguaClara/aguaclara_tutorial/blob/master/images/Cornell_University_seal.png?raw=true)

## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`Interactive-Tutorial-1-Markdown.md`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

```python
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```


## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

| Animals|   Books  |  Places   |
|:---------- | :---: |  --------: |
| Dogs  |  Bossypants|   Engineering Quad  |
| Cats   |   Inferno |   Hollister Hall  |
|  Tortoises |  The Time Traveler's Wife   |  AguaClara Lab   |


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

> Stay golden, Ponyboy
>
> -Albert Einstein

## Horizontal Rules

Add a horizontal rule:

---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
