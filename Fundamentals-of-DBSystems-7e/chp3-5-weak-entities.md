---
tags: CS4347; EER
date: 10.18.23 3:24PM CDT
modified: 
---

Chapter 3.5 Weak Entity Types
-----------------------------

+ **weak entity** -> entity types that _do not_ have key attributes of their own
    + **identifying or owner entity type** -> weak entity types must be identified
          by an association with a strong entity type, along with one of its
          attributes.
    + **identifying relationship** -> the association described above that ties a
          weak entity type to its owner/identifying entity type 
+ **strong/regular/default entity** -> entity types that _do_ have key attributes
+ **partial key** -> the attribute that can uniquely identify weak entites that
    _are related to the same owner entity_
