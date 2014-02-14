Guides
======
- guide
  - id<string> *
  - title<string> *
  - description<string> *
  - introduction<content> *
  - related<ref>[0-n]
  - articles<article>[1-n]
- article
  - id<string> *
  - title<string> *
  - description<string> *
  - introduction<content> *
  - related<ref>[0-n]
  - topics<topic>[1-n]
- topic<content>
  - id<string> *
  - title<string> *

Training
========
- class
  - id<string> *
  - title<string> *
  - description<string> *
  - introduction<content> *
  - related<ref>[0-n]
  - dependencies<ref>[0-n]
  - lessons<lesson>[1-n]
- lesson
  - id<string> *
  - title<string> *
  - description<string> *
  - introduction<content> *
  - related<ref>[0-n]
  - tasks<task>[1-n]
- task<content>
  - id<string> *
  - title<string> *

Linking
-------
- link
  - target-id<string> *
- external-link
  - href<string> *

Content
-------
- simple-content<link | external-link | emphasis | strong>[]
- content<link | external-link | emphasis | strong | paragraph | ordered-list | unordered-list | description-list | image | figure | note | section | subsection | table | code | code-set>[]