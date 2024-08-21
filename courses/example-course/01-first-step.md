

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

# How to create and conduct Experiments
😃 😃 :smiley: :smiley:
An experiment is a method of modifying a system's behavior based on context. In a lot of cases, we will use experiments before releasing a new feature. That allows us to get feedback and statistics.

### We use 2 types of experiments:

- Feature toggle - a mechanism that allows code to be turned “on” or “off” remotely without the need for a deploy. Feature toggles are commonly for canary releases (validate new software by releasing software to a small percentage of users) and continuous deployment.
- A/B Testing - comparing two versions against each other to determine which one performs better. A/B tests help PMs to collect data on user behavior before making decisions.

In OneApp, we use Petri to conduct our experiments.

:smiley:

:smiley:

:smiley:

🥲
# Projec

::: warning
*here be dragons*
:::

