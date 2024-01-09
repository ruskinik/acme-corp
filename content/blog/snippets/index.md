---
title: YouTube, Gists, and other snippets via shortcodes
date: 2024-01-04T00:00:00Z
tags:
  - shortcodes
  - snippets
categories:
  - youtube
  - markdown
---

## Hello

As powerful as Markdown is, it does not have all the possible features that we might
require in our content pages. Elements like those required for YouTube videos,
GitHub Gists, Tweets, etc., are not a part of plain Markdown. While we can add these
as HTML, Hugo provides a better, cleaner solution—shortcodes. Shortcodes are snippets of templates that we can include in the content files. These get replaced with the
actual contents at compile time. They are equivalent to functions in the programming
world.

With shortcodes, we can wrap reusable pieces of HTML into functions compiled
during the page compilation. This way, content creators do not have to deal with the
generation of the perfect HTML for a particular case that the shortcode author handles. Shortcodes can take arguments that can be processed in the template code.
Shortcode authors have access to the entire website configuration and all its variables,
Hugo’s built-in functions, and the entire theme to generate the HTML.