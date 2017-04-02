---
layout: post
id: kapsule
title: Kapsule
description: What brings you here?
---

# Kapsule

Minimalist dependency injection library for Kotlin.


Why create another dependency injection library? Here are the objectives pursued by Kapsule:

* Simple features that most projects will have use for
    - Alternative for projects whose dependency injection needs are quite basic
* Keep the method count to a minimum
    - Dependency injection shouldn't take thousands of methods to implement
* No annotation processing
    - No need for `lateinit` on properties and they can be private and read-only
* No magic, keep everything as a hard reference
    - Reading code is easier when you can click through all the references in your IDE
* Utilize the power of Kotlin
    - Use language features to simplify code instead of focusing on Java compatibility 

To accomplish all of these, Kapsule is based on [delegation](http://kotlinlang.org/docs/reference/delegation.html) and [delegated properties](http://kotlinlang.org/docs/reference/delegated-properties.html). 

## Javadocs

* Version 0.1
    - [kapsule-core](/docs/kapsule/0.1/kapsule-core/index.html)

## Links

* [GitHub](https://github.com/traversals/kapsule)
* [Bintray](https://bintray.com/traversals/maven/kapsule)
* [Maven Central](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22space.traversal.kapsule%22)
