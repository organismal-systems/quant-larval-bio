# How to use this book

This book is organized into Parts, each devoted to a different general topic or biological research area (e.g., Biomechanics, Demography, etc.).
Each Part contains Chapters that present, in context, one or more models within the general topic. 
"In context" means that these examples provide brief background (with additional outside references); a working "executable" model; instructions how to use that model and suggested activities for exploring potential implications of the model for interesting questions in Larval Biology.

In most cases, background is presented in short form, on separate "Quick Explainer" pages. 
These pages are intended to be short enough for a reader to internalize the most relevant, essential facts about a topic refered to in a model, without losing continuity of thought while working with that model.
Quick Explainers are not intended to be comprehensive, though ideally they may refer to additional sources that provide in-depth perspectives.
In many cases the most useful reference is simply a link to Wikipedia, which has proven to usually be comprehensive and accurate in many areas of mathematics, physics, statistics and other disciplines.

Models, instructions on how to use them, and activities applying the models to currently relevant questions in Larval Biology are presented in **Jupyter notebooks**. 
Jupyter notebooks are among the latest and (so far) best platforms for embedding working computer code with formatted text and graphical content. 
Jupyter notebooks can be combined and integrated with Markdown and other content in the form of an Executable Book.
Jupyter books can be run on a reader's own computer, can be run online on platforms such as Binder, and can be freely exported using a drop-down menu as a static (non-executable) PDF document.
With additional setup, Jupyter books can also be exported as a LaTeX document, and then reconverted to a variety of other formats.
This flexibility in format and usage makes Jupyter books the best platform, at the time of this writing, for a book aimed at helping Larval Biologists gain experience working with models.

## Terms of Use
The original content of this book can be freely downloaded and used under a **[Creative Commons 4.0 BY-NC-SA license](https://creativecommons.org/licenses/by-nc-sa/4.0/)**. 
This license allows you to *share* and *adapt* the content *for non-commercial purposes*, as long as you use proper *attribution* and *share* the resulting materials under the same license.
Definitions of the italicized terms and other significant details of this license are given in the linked text, a copy of which is also provided with source materials for the book.

## How to download and use this book
This book is available online in multiple forms, each of which has its own uses.

- The **source** documents for the book can be downloaded ("cloned") from GitHub at the main repository, **[quant-larval-bio](https://github.com/organismal-systems/quant-larval-bio/tree/main)**. 
This repository belongs to the **[organismal-systems](https://github.com/organismal-systems)** organization on GitHub, which is associated with the **[Organismal Systems Modeling Network](https://organismal-systems.org/)**. 
The source documents can be used to fully build the book using [JupyterBook](https://jupyterbook.org).

- A **static** (read-only) version of the book constructed with *GitHub Pages* can be viewed online (or downloaded) at the **[organismal-systems GitHub Pages site](https://organismal-systems.github.io/quant-larval-bio/content/overview.html).
This version is quick and easy to read, and can be a useful reference alongside executable pages.

- **Online executable models** are available through [Binder](https://mybinder.org/). 
The great advantage of these models is that they require nothing more than a browser to be running on users' machines.
This makes them accessible to nearly everyone everywhere.
As with most free online resources, though, there are limitations.
One is that the execution speed can be slower, especially at peak times, compared to running the same model on a local workstation (it can also be faster, depending on the workstation...).
Another is that sessions "expire" after a period of inactivity, freeing computing resources for other users. 
The session can easily be restarted, however, with the click of a button.

- **Executable models running locally on your computer** can be launched from downloaded copies of the source repositories, or from copies of those repositories already in the source materials for this book. 
Executable Jupyter notebooks containing models (and supporting Python libraries, if needed) are also incorporated into the book as **submodules**, which it *git* jargon for repositories that are incorporated as components of other repositories.
The source repositories for these models are stored elsewhere on GitHub, at links provided in the text.
**These models are typically cloned and run through their own repositories, or through the copies of their repositories included in the book source materials. These repositories usually have their own license requirements, which supercede (for that content) the licensing requirements for the original content of this book.**
This structure is necessary for two reasons:
	1. The Jupyter notebooks (and, often, a Python code library in which models are implemented) may be created and updated by different authors. 
	Having a separate repository for these models enables the authors to develop their own codes, avoiding requiring them to separately update a book implementation. It also avoids giving all authors editing access to the entire book content, which is not sustainable in the long run.
	2. Different models require different sets of Python libraries. 
	Some of these libraries are quite voluminous, so requiring a user of one model to install all libraries relevant to any of the other models is problematic.
	Moreover, Python libraries are updated and modified frequently; it is quite possible for different models in the book to require conflicting, incompatible versions of the same library.

The easiest way to manage the libraries required to build the book on your own computer and to run the executable models in [Jupyter Lab](https://jupyter.org/) is by creating an [Anaconda](https://www.anaconda.com) environment. 
The required modules for each repository is listed in a file called *environment.yml*, included with the repository.




