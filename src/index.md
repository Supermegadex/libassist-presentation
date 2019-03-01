---
marp: true
title: LibAssist
description: All-in-one documentation engine
theme: gaia
class:
  - invert
---

<!-- _class: - lead -->
# LibAssist
### A New Way to Doc.

![bg right 50%](https://github.com/Supermegadex/libassist-client/raw/master/assets/logo.png)

---
<!-- paginate: true -->

# The Problem

**BAD DOCS**

---

# The Problem

**BAD DOCS**

* [Marp](https://marpit.marp.app/)

---

# The Problem

**BAD DOCS**

* [Marp](https://marpit.marp.app/)
* [Phaser](https://photonstorm.github.io/phaser3-docs/index.html)

---

# The Problem

**BAD DOCS**

* [Marp](https://marpit.marp.app/)
* [Phaser](https://photonstorm.github.io/phaser3-docs/index.html)
* [Java](https://docs.oracle.com/javase/7/docs/api/)

---

# What Does Good Documentation Have?
* Human language
* Organized intelligently
* *Extensive* code examples

---

<!-- _class: - lead -->
![bg 30%](https://github.com/Supermegadex/libassist-client/raw/master/assets/logo.png)

---

# What is LibAssist?
#### LibAssist is two things:

1. A text-based documentation format (LADoc)
2. An app that displays files written in such a format

---

# LibAssist Documentation (LADoc)

* Markdown with **annotations**.
* Annotations are blocks of YAML that describe parts of the content
* Code blocks can be extended with annotations to create *examples*.
  * Multiple files in a group
  * Specify directory or template to abstract for readers
  * Runnable and editable

---

### Example: Project Annotation

```yaml
+++project
name: LibAssist
package: com.supermegadex.libassist
description: An all-in-one documentation solution
assets: pictures
+++
```

---

<!-- _class: - lead - invert -->
# Demo

---

# LibAssist App

* Read documentation written in LADoc
* Many libraries/APIs at a time
* Written in TypeScript
  * Angular
  * Electron

![w:150px](https://raw.githubusercontent.com/remojansen/logo.ts/master/ts.png) ![w:150px](https://avatars3.githubusercontent.com/u/13409222?s=200&v=4) ![w:150px](https://angular.io/assets/images/logos/angular/angular.svg)


---

<!-- _class: - lead - invert -->
# Demo

---

# Stuff I Want to Do

1. Add more
