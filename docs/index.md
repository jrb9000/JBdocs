# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


[license](/about/license)

| First Header  | Second Header |
| ------------: | ------------- |
| Content Cell  | Content Cell |
| Content Cell  | Content Cell |


1. Ordered item 1
2. Ordered item 2

* Unordered item 1
* Unordered item 2


A Paragraph.
*   Not a list item.

1. Ordered list item.
* Not a separate list item.


### Admonitions

The Admonition extension adds rST-style admonitions to Markdown documents.

!!! danger "Admonition" 
    The Admonition extension adds rST-style admonitions to Markdown documents.

!!! note "Note"
    The note/notice Admonition

!!! info "Info"
    The Info/tip Admonition

!!! important "Important"
    Important note

!!! warning "Warning"
    or Caution

!!! success "Success"
    Success message

!!! failure "failure"
    Failure message


### pymdownx.details

```
??? optional-class "Summary"
    Here's some content.

??? multiple optional-class "Summary"
    Here's some content.
```

??? optional-class "Summary"
    Here's some content.

??? multiple optional-class "Summary"
    Here's some content.

**Nested Details**

```
???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.
```

???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.


### pymdownx.emoji


The Emoji extension adds support for inserting emoji via simple short names enclosed within colons: :short_name: :grinning:


### SuperFences

-   Allowing the nesting of fences under blockquotes, lists, or other block elements (see Limitations for more info).
-   Ability to specify custom fences to provide features like flowcharts, sequence diagrams, or other custom blocks.
-   Allow disabling of indented code blocks in favor of only using the fenced variant (off by default).
-   Experimental feature that preserves tabs within a code block instead of converting them to spaces which is Python Markdown's default behavior.
