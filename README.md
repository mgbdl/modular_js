# modular_js

Some ground rules:
- self-containd module
  - everything to do with my module is in my module
  - no global variables
  - if a module manages more than one thing it should be split up
- separation of concerns
- efficient DOM usage
  - very few $(selectors)
- no memory leaks
  - all events can be unbound
