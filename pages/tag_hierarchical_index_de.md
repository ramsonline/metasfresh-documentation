---
layout: default
title: Hierarchical Tag Index
lang: de
---

Testing ground for issue <a href="https://github.com/metasfresh/metasfresh-documentation/issues/36">metasfresh-documentation#36</a><br>
Displays links to all pages as long as they have lang=de and at least one tag.

{% include tag_hierarchical_index.html pages=site.documents lang=page.lang %}