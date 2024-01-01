- [Markdown Preview Enhanced](#markdown-preview-enhanced)
  - [Math](#math)
  - [Diagrams](#diagrams)
  - [TOC](#toc)
  - [File Imports](#file-imports)
  - [Code Chunk](#code-chunk)
  - [Presentation](#presentation)
  - [Pandoc](#pandoc)

---

- [references](https://shd101wyy.github.io/markdown-preview-enhanced/#/)

# Markdown Preview Enhanced

## Math

KaTeX is faster than MathJax, but it lacks many features that MathJax has. You can check [KaTeX supported functions/symbols](https://shd101wyy.github.io/markdown-preview-enhanced/#/math)

By default:

- Expression within `$...$` or `\(...\)` will be rendered inline
- Expression within `$$...$$` or `\[...\]` or ` ```math ` will be rendered in block

## Diagrams

Markdown Preview Enhanced supports rendering `flow charts`, `sequence diagrams`, `mermaid`, `PlantUML`, `WaveDrom`, `GraphViz`, `Vega & Vega-lite`, `Ditaa diagrams`

You can also render `TikZ`, `Python Matplotlib`, `Plotly` and all sorts of other graphs and diagrams by using [Code Chunk]()

> Please note that some diagrams don't work well with "file exports" such as PDF, pandoc, etc.

## TOC

`Markdown Preview Enhanced: Create Toc` to create TOC

To exclude a heading from the TOC, append `{ignore=true}` after your heading

you can Configuration it

## File Imports

How to use

- `@import "your_file"` 
- `<!-- @import "your_file" -->`

Supported file types

- so many kinds
- include online files
- line_begin && line_end

Configure images

- `@import "test.png" {width="300px" height="200px" title="my title" alt="my alt"}`

## Code Chunk

## Presentation

## Pandoc
