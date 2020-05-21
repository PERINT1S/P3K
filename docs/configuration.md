---
layout: default
title: Mau jadi apa?
nav_order: 2
permalink: /docs/configuration
---

# Mau jadi apa?
{: .no_toc }


Pertanyaan yang sungguh sering kita dengar, dan sulit dijawab. "Mau jadi apa?" Apa aku mau jadi bos, _entrepreneur_ (apa bedanya dengan wiraswasta?), pekerja, buruh, pegawai, karyawan, mitra, tenaga ahli? Apa perbedaannya? Apa saja hak dan kewajibannya? Aku sendiri apa?
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Entrepreneur

```yaml
# Set a path/url to a logo that will be displayed instead of the title
logo: "/assets/images/just-the-docs.png"
```

## Bos, atau pemberi kerja

```yaml
# Enable or disable the site search
# Supports true (default) or false
search_enabled: true

# Enable support for hyphenated search words:
search_tokenizer_separator: /[\s/]+/

```

## Pekerja, atau penerima kerja

```yaml
# Aux links for the upper right navigation
aux_links:
  "Just the Docs on GitHub":
    - "//github.com/pmarsceill/just-the-docs"
```

## Buruh

```yaml
# Heading anchor links appear on hover over h1-h6 tags in page content
# allowing users to deep link to a particular heading on a page.
#
# Supports true (default) or false/nil
heading_anchors: true
```

## Pegawai, karyawan

```yaml
# Footer content appears at the bottom of every page's main content
footer_content: "Copyright &copy; 2017-2019 Patrick Marsceill. Distributed by an <a href=\"https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt\">MIT license.</a>"
```

## Tenaga ahli &amp; profesional

```yaml
# Color scheme currently only supports "dark" or nil (default)
color_scheme: "dark"
```
<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script type="text/javascript" src="{{ "/assets/js/dark-mode-preview.js" | absolute_url }}"></script>

See [Customization]({{ site.baseurl }}{% link docs/customization.md %}) for more information.

## Pekerja PKWT &amp; PKWTT

```yaml
# Google Analytics Tracking (optional)
# e.g, UA-1234567-89
ga_tracking: UA-5555555-55
```
