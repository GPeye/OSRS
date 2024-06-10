# Open Source Recipe Standard
#### Author: GPeye
#### Created On: 06/10/2024

---------
# Introduction
### a. Overview
    Sharing recipes has been a common occurrence for as long as there has been recorded history. The knowledge of preparing any given food has changed hands so many times that often attempting to find a dish's origin is a fools errand and even when the source is clear, it's been altered and changed so much as to be unrecognizable. The idea that anyone could legally own a recipe is absurd. While a list of ingredients cannot have copyright protection, everything beyond that list, such as exact wording of instruction is subject to copyright.
    
    I feel this is holding us back. There have been numerous attempts to provide clever and useful recipe based tooling that end up being shut down due to litigation regarding recipe copyright. Good recipe tooling needs recipes in order to be useful. It is not necessarily feasible for a small startup to generate great quantities of recipes and thus aggregation becomes necessary.

    The purpose of this standard is to define only the minimally required components of a recipe as a list of ingredients, collecting those ingredients into a sequence paired with predefined cooking verbs and predefined descriptive words, such that useful instructions for the recipe can be entirely generated from this open source standard, ensuring that the resulting recipe should be free from any relation to existing copyright. Since the resulting recipe is generated programmatically, even if it does somehow overlap with an existing recipe copyright, this standard provides several options for defense. For example, the only data collected is not subject to copyright therefore any generated work via this pre-defined standard is essentially clean room and therefore cannot infringe on the copyright of a potentially earlier work. Any similarities would merely be a consequence of the nature of the problem of expressing a recipe and not a copied creative expression.

### b. Glossary / Terminology

### c. Goals / Requirements
- Define a schema of recipe details not subject to copyright
- Define a method of generating generating a full recipe with instructions based on the provided schema details

### d. Out Of Scope
While lots of additional details can be derrived from the data within the schema, such as nutritional information and portion modification, but this is out scope for this standard.

# Schema
tbd