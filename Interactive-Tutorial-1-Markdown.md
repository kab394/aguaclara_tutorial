# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

My name is Kara Buhl and I am a sophomore studying Civil Engineering.

I quote Spongebob on a daily basis and I love dogs!

## Headers

Make a 3rd level header with your name:

### Kara

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*swanky* **doodle** ***hehe*** ~~oops~~

## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. I want to not fail all of my classes this semester. This means I have to:
    1. Study a lot
    2. Go to class
    3. Never sleep
2. I would like to get more involved with the Concert Commission by:
    1. Volunteering at concerts
    2. Showing up to meetings
3. I would like to learn more about how the Dissolved Gas reactor will work by:
    1. Researching
    2. Experimenting
    3. Talking to people who know about the topic

* Oceanography
* Diff Eq
* Statics

## Links

Write a sentence describing your major, and insert a link to your major's department website:

My major, [Civil Engineering](http://www.cee.cornell.edu/), involves the design and creation of bridges, buildings, roads, dams, and many other structures.

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/Images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

From a relative file path
![CornellSeal](/Images/Cornell_University_seal.png)

From A URL
![CornellSeal](https://github.com/kab394/aguaclara_tutorial/blob/master/Images/Cornell_University_seal.png?raw=true)

## Code Formatting

Put the name of this file in an in-line (single backtick) code format.
`
Interactive-Tutorial_1_Markdown.md
`


Put the following text in a Python-formatted code block:

```python
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```


## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

|    | Best | 2nd Best | 3rd Best|
|:--:|:---------:|:-----:|:---:|
|FOOD|pasta| pizza|fries|
|BOOKS|The Great Gatsby|Life of Pi|Breakfast of Champions|
|PLACES ON CAMPUS|Snee Hall Reading Room|Statler Library|My dorm|


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

> The
- Albert Einstein

## Horizontal Rules

Add a horizontal rule:

---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
