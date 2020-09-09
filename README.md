# Lab MarkDown NoteBook (LMDNB)

Possible implementation of lab-wide notebook using (R)markdown, `bookdown`, or
`blogdown`.


## Key implementation requirements

Two major requirements:
1. Easy to view/add/edit/submit notes
1. Easy to maintain and organise

For the first point, if no one is able to add or edit notes collaboratively, no
one will make good use out of it.
If people can't share their knowledge easily, people won't bother spending
their time and energy to do so.

For the second point, if it is difficult to maintain and organise the notebook,
then it would be harder for you (and other people) to navigate and add/edit
notes, and therefore make the notebook relatively useless.
If the notebook is implemented simply with less things to do manually, the
better it would be (I think).

Here are the sub-requirements that I think would make it even better:
- Light (in terms of data size)
- Multi-platform (everyone can download and work on it)
- Easy to reference
- Code compatible (able to add code chunks with output)
- Some sort of topic organisation (tagging/indexing/keywords)


Considering the above, `bookdown` or `blogdown` would be ideal for this, as it
can already automatically gather and compile multiple documents.


## Software requirements

Probably the following:
- R
- `bookdown`
- `blogdown`
- `git`


## TODOs and considerations

TODOs:
- implement the basic structure/system for a notebook
- automatic compilation with push and/or merging of pull requests


Considerations:
- directory structure that will keep everything organised and clean at the root directory
- storage of images -- ideally not in this repo
- what to do when we want codes (and outputs) from other languages (e.g. bash, python)
- possible `make` system to organise the files and render them properly


