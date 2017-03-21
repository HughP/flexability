# Flexability
The goal with this software is to take the Lift formated XML and pull out body part names, and then insert those names into a SVG formated graphic.

## Reason and goal
In the process of making literacy materials for many indigenous languages it is often the case that a body chart is made. This generally includes a figure of a person with some detail and then something like arrows pointing from the names of those body parts to the body parts. Up till now, these body charts have been made by hand. This process can take more than an hour per chart. These charts also currently suffer from low-quality graphics when printed.

It occurs to me that we could define a workflow or a pipeline in which data would be extracted from dictionaries. This process would speed up the process not just for me in one language but for many people around the world. Here is a proposal:

If we have a body chart in SVG format created with [Adobe Illustrator](https://www.adobe.com/Illustrator) or [Inkscape](https://inkscape.org/), then we could use the XML export from our Dictionary software (in this case [FLEx](http://software.sil.org/fieldworks/) using [Lift in XML](https://github.com/sillsdev/lift-standard)), and then use [XSLT](https://en.wikipedia.org/wiki/XSLT)([quick tutorial](https://www.w3schools.com/xml/xsl_intro.asp)) to transform the data in the XML to the receptacles in the SVG image.
