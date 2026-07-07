# tgb-media

Public image asset host for TheGateBreaker articles (Zenn / Qiita).

## Scope

This repository contains **only final, approved PNG figures** for already-published
or approved-for-publication articles. It never contains:

- article draft text
- unpublished/unapproved content
- ops reports, tooling, or internal workflow files

Images are pushed here **after** an article has passed Human review
(quality gate + content-review-request synthesis), as part of the
`content-package` publication step — never during drafting.

## Structure

```
images/issue_<N>_<slug>/fig1_*.png
images/issue_<N>_<slug>/fig2_*.png
...
```

## Usage

Images are referenced directly via raw GitHub URLs in Qiita/Zenn article Markdown:

```
https://raw.githubusercontent.com/hyqube/tgb-media/main/images/issue_<N>_<slug>/fig1_*.png
```
