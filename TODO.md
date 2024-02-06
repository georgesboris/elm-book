

- [] Organize pages recursively
    - [] Pages may have "blocks" which can be mapped
    - [] Blocks are pages, markdown and elm components
    - [] User can register elm blocks
    - [] Blocks may receive an additional configuration object
      - Used for dynamic properties?
      - Used for reusing the same block with different state?
      - Dynamic properties (knobs) should be possible through plugins
    - [] User can register decorations (mappers) for any type of block
    - [] Blocks are stored as trees
    - [] Pages store their base url and can be used to create a navigation component
    - [] Pages should be made of titles, blocks and possibly description and meta tags for search purposes
    - [] Last level of navigation should be the page's headings

- [] Search through pages using description and meta tags

- [] Generate pages through markdown blocks (codegen)
- [] Dynamic elm-books? elm-pages as backend?

- [] Elm-book should be embeddable in another elm-app (not be it's own init)
  - [] Should expose init, update, subscriptions and view
  - [] Should receive shared state?
  - [] Elm-book should still provide an option for standalone init (simpler, less boilerplate)

- [] Elm-book CLI (Roc? Gleam?)
  - [] Generate elm-book based on markdown files + settings files (optional)
  - [] Generate elm-book based on url?

- [] Stylised through elm-widgets
- [] Should I make elm-theme be a generic spec? Bindings to other frameworks? (too much of an effort)

