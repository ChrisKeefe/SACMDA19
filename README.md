# SACMDA19
Poster: Developing a QIIME 2 plugin - a simple annotation for robust tools
## Copyright (c) 2018 Chris Keefe
### Submitted for presentation at the [3rd Workshop on Statistical and Algorithmic Challenges in Microbiome Data Analysis (SACMDA)](https://www.simonsfoundation.org/event/3rd-workshop-on-statistical-and-algorithmic-challenges-in-microbiome-data-analysis/), 4/1-4/2/19

Copyright details in LICENSE.md

## Abstract
Research software development plays a critical role in microbiome science, but many biologists lack formal training in software development. As such, computational methods for microbiome analysis vary widely in readability, maintainability, error prevention, accessibility to users, and level of user support. Academic publications in biology have addressed best practices for programming1 and software documentation2, providing good road maps to fundamentals. However, even computationally advanced biologists may not be able to prioritize the development of complex software architecture and support infrastructure, when that development time comes at the expense of other important research goals.

Here we present an overview of plugin development for QIIME 23, an open-source microbiome bioinformatics platform designed to support and provide value to developers of computational methods. Developed under a “plugin” model, QIIME 2 provides valuable architecture for type-checking, error reporting, data access communication between disparate methods within a computational pipeline, and convenient visualization of computational results. We present techniques for richly annotating new or existing computational methods to allow users to access them via diverse pre-built user interfaces, while ensuring accurate method citation and provenance tracking. Finally, we discuss platform infrastructure for the dissemination and support of third-party computational methods. In so doing, we provide an introduction, and resources for further study, to developers of computational methods which might benefit from existing architecture. For many computational microbiome scientists, these plugins will improve their return on time invested, and encouraging meaningful collaboration with others in the field.

## [Gemini theme] copyright (c) 2018 Anish Athalye (me@anishathalye.com)
Theme license details inline

Readme text below modified from: [Gemini README] and subject to [Gemini License]

## Dependencies

* A TeX installation that includes [LuaTeX]
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. Navigate into your local poster directory and run `make` to build the poster

1. `make clean` will delete all build-related files including the poster, allowing you to re-run `make` as needed.


[Gemini theme]: https://github.com/anishathalye/gemini
[beamerposter]: https://github.com/deselaers/latex-beamerposter
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[Gemini README]: https://github.com/anishathalye/gemini/blob/master/README.md
[Gemini License]: https://github.com/anishathalye/gemini/blob/master/LICENSE.md
