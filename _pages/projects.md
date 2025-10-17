---
title: "Projects"
permalink: /projects/
layout: single        # ← 改用 single，不用 collection 版型
classes: no-pager    # 這頁不要 Prev/Next（可留可不留，看你需求）
---

{%- include documents-collection.html
      collection="projects"
      entries_layout="grid"
      show_excerpts=true
      sort_by="date"
      sort_order="reverse"
-%}
