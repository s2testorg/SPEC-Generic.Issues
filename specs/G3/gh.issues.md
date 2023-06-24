---
testspace:
title: GitHub Issues (Ad Hoc)
parent: Ad Hoc
project: https://s2testorg.stridespace.com/projects/s2testorg:ADHOC-GitHub.Issues
before:
  name: github::setup
  description: Setup fixturing
  payload: "@gh.issues.json"
after:
  name: github::teardown
  description: Teardown fixturing
  payload: "@gh.issues.json"
---

{% if page %} {% assign spec = page %} {% endif %}

# {{ spec.title }}
The Test Spec is for **Ad hoc** testing of Issues using GitHub as the "Issue Provider".

There is setup and teardown fixturing provided: **[Test Project]({{ spec.project }})**

- **Open** new Issues; add Markdown, Images, and emojis
- **Close** Issues using GitHub
- **Reference** Issues
- Review the **Issues References** and **Issues Metrics** views
- Do random stuff :monkey_face:


## Open

## Close

## Reference

## Review

## Random

