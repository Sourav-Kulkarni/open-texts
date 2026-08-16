# Open Texts

A curated digital library of public domain texts, freely accessible online.

Maintained by [Sourav Kulkarni](https://souravkulkarni.com).  
Live at: [texts.souravkulkarni.com](https://texts.souravkulkarni.com)

---

## What this is

A personal effort to digitize, translate, and publish texts that deserve better than a scan.

The selection criterion is simple: if a text is in the public domain and its best available form is a blurry PDF or an inaccessible regional language edition, it belongs here. Priority is given to Indian texts — across languages, periods, and traditions — that have not received adequate scholarly digitization elsewhere.

This is not a mirror of Project Gutenberg or Wikisource. Every text here has been manually digitized, structured, and in many cases translated, by Sourav Kulkarni.

---

## Curatorial scope

- **Public domain only.** All texts are out of copyright in India and, to the best of my knowledge, in most major jurisdictions.
- **Needs-based.** A text is included because no adequate digital edition exists, not because it is famous.
- **Transparent provenance.** Every text documents its source — what was digitized from, what editorial decisions were made, and where uncertainty exists.

---

## Folder structure

Texts are organized by author. Where authorship is unknown or multiple, they are organized by work title.

```
docs/
  index.md
  savarkar/
    sanyasta-khadga.md
    essentials-of-hindutva.md
  aryabhata/
    aryabhatiya.md
  arthashastra/
    arthashastra.md
```

---

## Text metadata schema

Every text in `docs/` carries the following YAML front matter:

```yaml
---
title:
author:
language:
translator:          # omit if original language
source:              # what physical or digital source was digitized from
date_of_work:        # approximate date of original composition or publication
date_digitized:      # when this digital edition was produced
license: Public Domain
tags:
  -                  # e.g. marathi, 19th-century, philosophy
---
```

All contributions and corrections must conform to this schema.

---

## Deploying locally

```bash
pip install mkdocs-material
mkdocs serve        # preview at http://127.0.0.1:8000
mkdocs gh-deploy    # build and push to gh-pages branch
```

---

## License

All texts are in the public domain.  
Digitization, translation, and editorial work © Sourav Kulkarni, released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).  
You are free to use, share, and adapt this work with attribution.

---

## Contact

[souravkulkarni.com](https://souravkulkarni.com)