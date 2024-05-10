---
name: Custom translation template
about: Requesting site translation
title: 'Support language: xxxx'
labels: translation
assignees: ''

---

Step 1) Find your two letter local code. Reference the [link from Wiki](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes)

Step 2) Copy the set of key value data from the [en-US](https://raw.githubusercontent.com/johnson-jesse/far-east-issue-tracker/main/en-US) set and translate the values. Leaving the first entry for version alone: `"version","1.0.0"` as whatever it is set at. Paste the rest of the data replacing `... everything else`.

```json
{
    "version": "1.0.0",
    ... everything else
}
```
