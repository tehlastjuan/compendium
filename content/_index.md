---
title: "Compendium"
type: "docs"
toc_hide: true

cascade:
  - _target:
      path: "/blog/**"
    type: "blog"
    toc_root: true
  - _target:
      path: "/**"
      kind: "page"
    type: "docs"
  - _target:
      path: "/**"
      kind: "section"
    type: "docs"
  - _target:
      path: "/**"
      kind: "section"
    type: "home"
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}

This section is where the user documentation for your project lives - all the
information your users need to understand and successfully use your project.

For large documentation sets we recommend adding content under the headings in
this section, though if some or all of them don’t apply to your project feel
free to remove them or add your own. You can see an example of a smaller Docsy
documentation site in the [Docsy User Guide](https://docsy.dev/docs/), which
lives in the [Docsy theme
repo](https://github.com/google/docsy/tree/master/userguide) if you'd like to
copy its docs section.
