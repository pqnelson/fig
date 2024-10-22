# Notes to self

- Apparently macros can be "namespaced" (since [version 2.1](https://www.jonmsterling.com/jms-005O.xml)).
  The documentation is lacking. As I understand it, just write
  `\namespace\foo{...}`
  and any macro defined within `\def\bar{...}` it will _really_ be
  defining `\foo/bar`
- The `\ref` builtin is intended for things like Theorems, Definitions,
  etc. and will produce "Theorem [identifier]" (based on the `taxon` of
  the entry).
- The `\date` frontmatter is overloaded to the point of ambiguity. It's
  _supposed_ to document the date of creation, but for reference
  material it's the date of publication.
  