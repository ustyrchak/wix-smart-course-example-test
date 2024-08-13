

<summary><b>Scala</b></summary>

:ok_hand:

```scala
override def getWishlistOwnerDetailed(request: GetWishlistOwnerDetailedRequest)(implicit callScope: CallScope): Future[GetWishlistOwnerDetailedResponse] = ???
```

![Title](/courses/example-course/test_testing_optical_265619.jpg)

:smiley:
:smiley:
:smiley:
🥲
# Project file structure
👉 To use the ML platform, all models should be added to the ds-ml-models git repository as a dedicated project (sometimes referred to as a "_sub-project_" of the ds-ml-models repo.) directory which conforms to the following file structure:
```
ds-ml-models:
⋮
|-> project directory:
    |-> production directory:
        |-> conda.yaml
        |-> model.py
        |-> __init__.py 
    |-> MLproject file
    ⋮
⋮
```
</details>

### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

:point_right:   this is emoji
:ok_hand:

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::

