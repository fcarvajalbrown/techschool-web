# Architecture Diagrams — README

## What is Mermaid?

Mermaid is a diagramming tool that lets you write diagrams as plain text inside Markdown files.
Instead of using a visual editor, you describe the diagram in a simple syntax and it renders
automatically in tools like GitHub, GitLab, Notion, and Obsidian.

This means diagrams live alongside your code, can be version-controlled, and are easy to update
without exporting images.

## What is the C4 Model?

C4 is a standard for describing software architecture through four levels of zoom, each targeting
a different audience.

- **Level 1 - Context:** The big picture. Shows your system and how it relates to users and
  external systems. Useful for non-technical stakeholders.

- **Level 2 - Container:** Zooms into your system and shows the major deployable units — apps,
  databases, build pipelines. Useful for architects and tech leads.

- **Level 3 - Component:** Zooms into a single container and shows how it is organized internally.
  Useful for developers joining the project.

- **Level 4 - Code:** The lowest level. Shows how individual files or modules relate to each other.
  Useful when onboarding to a specific part of the codebase.

## Why is it useful?

Most projects grow without documentation. New developers waste time reading code just to understand
the structure. C4 gives a shared vocabulary and a consistent way to communicate architecture at the
right level of detail, depending on who you are talking to.

These diagrams are not meant to be exhaustive. They are meant to answer the question
"how does this system work?" as fast as possible.
