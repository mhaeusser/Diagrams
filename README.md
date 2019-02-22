# Diagrams
This is a collection of diagram types that are all created from a simple text representation.

##### Typora Markdown folders

Markdown files with inlined diagrams. Works nicely with Typora and probably with other Markdown editors.

##### PlantUML folders

From text files (beginning with `@startuml`), PNG diagrams can be created using PlantUML, e.g.:
`java -jar plantuml.jar activity_repeat.txt` creates `activity_arrows.png`.

These picture files can be integrated in Markdown files.

You need plantuml.jar. Unfortunately, the file cannot be automatically downloaded with wget or so. You have  to download in manually from https://sourceforge.net/projects/plantuml/files/latest/download and put it into this folder. Also see http://plantuml.com/starting.

Some diagrams require an installation of graphviz (https://www.graphviz.org/download/ → https://graphviz.gitlab.io/_pages/Download/Download_windows.html).

##### AsciiDoc folder

With AsciiDoctor installed, diagrams can be created inside AsciiDoc files.

AsciiDoctor needs Ruby (https://www.ruby-lang.org/de/ → https://rubyinstaller.org). Once Ruby is installed, execute `gem install asciidoctor` and `gem install asciidoctor-diagram` (see http://asciidoctor.org/docs/asciidoctor-diagram/).

To use IntelliJ IDEA as an editor, open an .adoc file with it an die IDE will suggest downloading the right plugin.

