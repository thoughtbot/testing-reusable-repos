# testing-reusable-repos

This is an example of how to use the Dynamic README reusable workflow from https://github.com/thoughtbot/templates

The following footer is rendered from the templates repo and to use it on a repo, we can do it with an inline snippet,

```
<!-- include /templates/footer.md  -->
```

or with a block so you can add more content in between:

```
Reusable Includes :
<!-- START /templates/footer.md  -->

<!-- END /templates/footer.md  -->
```

The README will then be updated to use the markdown content from this file: https://github.com/thoughtbot/templates/blob/main/templates/footer.md

<!-- START /templates/footer.md -->

<!-- END /templates/footer.md -->
