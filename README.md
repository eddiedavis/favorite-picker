# Spongebob Episode Picker

## Intro

Forked from [antialasis's repository](https://github.com/antialiasis/favorite-picker), this is a simple web app that offers the user "A" or "B" or "C" etc. style questions to create an ordering of the user's favorite Spongebob episodes from the first three seasons. The forked repo has the most complete description but here are some quick tips:

### Picking  Elements

When you select a subset from the list given, you are saying that you prefer every element in the selected subset to every element in the list that is not part of the selected subset. For example, you select episode A and B but do not select C or D. This means you prefer A to C or D and you prefer B to C or D. There is no implied ranking between A and B or C and D. Passing reshuffles the array and no new rankings are inferred. After a ranking has started to be generated, you can still rearrange the elements if you disagree.

### Shared Rankings

You can share your results with others by sending the link at the bottom of the page. After opening a shared ranking link, you will see the ranking associatied with that link and the option to continue it or continue your current list.

### List Persistence

There is no way to get back your original list if you continue another list, reset your list, or clear your local browser storage.

Gold Team Rules!