# Auto Markdown fixtures

These are saved outputs from the core CLI's 2026-10-18 auto-mode evaluation:

- `auto-single.md`: go-chi/chi commit `3a33ba578e0dd93444e0ff386cc26e665d92e31e`
  against its first parent; includes the context-trimming notice.
- `auto-split.md`: go-chi/chi range
  `aba86186a27484f3cadc55b8d6448d2049af71bf..3d1777a1ef8881f7d1da0b02c76ca8f0a29cd2bc`;
  two diagrams and a visible list of isolated changed files.
- `auto-summary.md`: pmndrs/zustand commit
  `b57db4f86ef179285da216eeb291266da82c361c` against its first parent;
  a file summary with no Mermaid block.

Tests validate these as untrusted artifact content, preserve their Markdown
when constructing comments, and retain them with a stale notice after failure.
No remote repository or GitHub write is needed to run the fixture tests.
