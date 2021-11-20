# Commit Conventions

## 1. Commit Message Format

[Type]

[Scope] 

[Description] 

### 1.1 Type

 The "Type" segment is used for explicitly tell the purpose of the current commit. There are three types of commit so
far as listed below:

- Feature

  Suggesting the current commit contains some feature changes.

- Bug Fix

  Suggesting the current commit aims to fix bugs.

- Documents

  Suggesting the current commit just focus on document rather than source code.

- Merge

  Suggesting the current commit is merged from other branch.

### 1.2 Scope

 The "Scope" segment is used for tell the effect scope of the current commit. For example, suppose we have a module
called "foo" and it is modified in the current commit， then we should write like this：

> [Scope] foo

If the whole project were affected by this commit, you call simply using "All".

> [Scope] All

### 1.3 Description

 The "Description" segment is used for writing verbose and specific information about the current commit. You can
literally write anything as long as it's good for people to understand the content and purpose of this commit.