# Null Object Design Pattern

Intent

The intent of a Null Object is to encapsulate the absence of an object by providing a substitutable alternative that offers suitable default do nothing behavior. In short, a design where "nothing will come of nothing"

Use the Null Object pattern when

    an object requires a collaborator. The Null Object pattern does not introduce this collaboration--it makes use of a collaboration that already exists
    some collaborator instances should do nothing
    you want to abstract the handling of null away from the client


Problem

Given that an object reference may be optionally null, and that the result of a null check is to do nothing or use some default value, how can the absence of an object — the presence of a null reference — be treated transparently?

## Overview


## Structure
![](/src/null/null-object-structure.png)
