<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
![GitHub release](https://img.shields.io/github/tag/Gibbons-Lab/mmmih.svg)
[![slides](https://img.shields.io/website-up-down-green-red/https/shields.io.svg?label=slides)](https://gibbons-lab.github.io/mmmih)


# Data and Materials for the Microbiome Movement workshop 2021

## Output

All output generated during the walkthrough can be found in the
[treasure chest](treasure_chest). The easiest way to get all of that
is to [download the entire repository](https://github.com/Gibbons-Lab/mmmih/archive/main.zip).

## A Deep-Dive into Microbe-Centric Metabolic Modeling

Presentation: [![part 1](https://img.shields.io/website-up-down-green-red/https/shields.io.svg?label=part1)](https://gibbons-lab.github.io/mmmih)
Notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gibbons-Lab/mmmih/blob/main/micom.ipynb)

You can see the actual workshop walkthrough at
https://gibbons-lab.github.io/mmmih. Press `?` to get a list
of available live options such as slide overviews and speaker mode. Note that
some slides are grouped vertically, you can navigate the presentation using
the directional buttons on your keyboard.
A [PDF version](slides.pdf) (lacks the output previews) is also available.



# For instructors

## Use case

The course presentations are meant to be compatible with common equipment available to students, so they
can be encouraged to open it on their smartphone (landscape mode required)
while they run commands on their equipment.

In order to minimize the need to transfer files between a server and the local
machine all output is pre-generated and the visualizations are included directly
in the presentation.

## Technicalities

### How do the presentation slides work?

The presentation itself is a webpage hosted on GitHub. Basically, it
renders dynamically from a [markdown file that includes the course](docs/talk.md).
Editing the markdown file is sufficient to change the content of the presentation.

See the [reveal docs](https://github.com/hakimel/reveal.js/#markdown) for more info.

### Preview locally

Open a terminal in the `docs` folder in the repo and use:

```bash
python -m http.server
```

This will preview the talk at `localhost:8000` in a browser. Editing the
markdown and reloading the page should be enough.

### PDF output

To generate a PDF of the course, open up the website in chromium or chrome and
append `?print-pdf` to the address. For instance, if you ran it locally as
described above, open `localhost:8000?print-pdf` in the browser. Then, choose
'print to PDF' (choose margins: none).
