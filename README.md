# latexdoc-conset
A simple construction set for LaTeX documents.

It's meant to be a boilerplate kit for manual composing LaTeX documents
from example snippets.

Additionally I use ```pandoc``` to get YAML frontmatter for settings to work.
This is mainly used for font and layout settings but not final.

As this set is for personal use most of the content and examples are
in German language. Don't expect to get an international version but
probably I will add some variables for English (or even universal) usage
later.

## Dependencies

All additional LaTeX packages you need are listed here. Install them with ```tlmgr``` of you LaTeX distribution of choice (MikTeX, MacTex, TeX Live ...).

**Fonts & Layout settings**
- enumitem

**Dummy content creation**
: When using this as an working example we need some dummy content.
  This can be created with the ```lipsum``` or ```blindtext``` package.
  - lipsum
  - blindtext

**Header & Footer**
: For using ```header-footer.tex``` you need
  - fancyhdr 