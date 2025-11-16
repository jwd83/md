# markdown editor

simple single-page markdown editor with dark mode theme.

## features

- tabbed interface for editing multiple files
- syntax highlighting via codemirror
- live preview panel using marked.js
- file operations (new, load, save)
- keyboard shortcuts (cmd+s, cmd+n, cmd+o)
- toggle preview on/off

## usage

open `index.html` in a modern browser that supports the file system access api (chrome, edge, etc).

the editor starts with one blank tab. create new tabs, load markdown files, or start typing. preview updates as you type.

## tech

single html file with inline css and javascript. uses cdn-hosted libraries:
- codemirror for editor with markdown mode
- marked for markdown parsing
- monokai theme for syntax highlighting

## notes

file system access api needed for load/save. won't work in older browsers or safari without workarounds.
