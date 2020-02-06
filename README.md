# ThemeGlobe

A directory of Professional Joomla Templates for the Joomla CMS. https://themeglobe.com

## Submitting a template

### Option 1

- Fork this repo and create a new markdown `.md` file in `content/joomla` folder.
- The markdown filename should be named with the provider followed by the template name (replacing spaces with a "-"), for example `provider-template-name.md`
- Submit a pull-request with the title **Template Submission: template-name**

### Option 2

- Create new markdown `.md` file in `content/joomla` folder via Github.. https://github.com/ciar4n/themeglobe/new/master/content/joomla
- The markdown filename should be named with the provider followed by the template name (replacing spaces with a "-"), for example `provider-template-name.md`
- Under 'Propose new file', set the title **Template Submission: template-name**
- Submit


The markdown file should contain the following front-matter.

```yaml
---
title: "Template Name"
details: https://www.provider.com/template/details
demo: https://www.provider.com/template/demo
date: 2020-01-28 # The date the template was released YYYY-MM-DD

provider:
  - Provider Name
archetype:
  - Creative
  - Visionary # Available archetypes: Advocate, Athlete, Caregiver, Creative, Explorer, Intellectual, Performer, Rebel, Spiritual, Tastemaker, Visionary

description: A brief decription of the template displayed on the list page. 
---

# Details template decription

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec odio. Quisque volutpat mattis eros. Nullam malesuada erat ut turpis. Suspendisse urna nibh, viverra non, semper suscipit, posuere a, pede.

## Features

* Aliquam tincidunt mauris eu risus.
* Vestibulum auctor dapibus neque.
* Nunc dignissim risus id metus.
* Cras ornare tristique elit.
* Vivamus vestibulum ntulla nec ante.
* Praesent placerat risus quis eros.

```

Template screenshots, Lighthouse and carbon details will be added upon merge.

## Develop Locally

This site is built on [Hugo](https://gohugo.io/)

```
hugo serve
```

## Lighthouse Auditing

The lighthouse auditing is done through https://web.dev. Note that the performance value does vary slightly with each audit. If you feel an audit is inaccurate, you can submit a PR with the data for the specific template removed from https://github.com/ciar4n/themeglobe/blob/master/data/themes.json. The template demo will be re-audited on merge of the PR.