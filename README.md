Daftar
======

A Simple note-taking application.

* Mailing list: daftar-dev@googlegroups.com
* Daftar page on Github: http://daftar-dev.github.io/daftar
* clone Daftar repo: `git clone git@github.com:daftar-dev/daftar.git`

## Use Case
![UseCaseDiagram](usecase.png)

### Use Case Template
```
USE CASE N: FULLY DRESSED USE CASE TEMPLATE <NAME>
<the name should be the goal as a short active verb phrase>
Context of use: <a longer statement of the goal, if needed, its normal occurrence con-
ditions>
Scope: <design scope, what system is being considered black-box under design>
Level: <one of: Summary, User-goal, Subfunction>
Primary Actor: <a role name for the primary actor, or description>
Stakeholders & Interests: <list of stakeholders and key interests in the use case>
Precondition: <what we expect is already the state of the world>
Minimal Guarantees: <how the interests are protected under all exits>
Success Guarantees: <the state of the world if goal succeeds>
Trigger: <what starts the use case, may be time event>
Main Success Scenario:
<put here the steps of the scenario from trigger to goal delivery, and any cleanup
after>
<step #> <action description>
Extensions
<put here there extensions, one at a time, each referring to the step of the main sce-
nario>
<step altered> <condition>: <action or sub-use case>
<step altered> <condition>: <action or sub-use case>
Technology and Data Variations List
<put here the variations that will cause eventual bifurcation in the scenario>
<step or variation # > <list of variations>
<step or variation # > <list of variations>
Related Information
<whatever your project needs for additional information>
```

### UC-N: Name

**Description**

**Primary Actor**

**Preconditions**

**Postconditions**

**Main Success Scenario**

**Extensions**

**Priority**



### UC-1: Create new note

**Description**

**Primary Actor**

**Preconditions**
* User is toplevel application window.

**Postconditions**
* User have created new note.

**Main Success Scenario**

1. User request system to create new note.
2. System provide user to enter new note (title, body, tags are optional).
3. User can write new note and set title, body and tags.
4. System automaticly save the note as user change it.

**Extensions**

**Priority**
* high



### UC-2: Edit previous notes

**Description**
کاربر باید بتواند یادداشت‌های قبلی‌اش را در یک فهرست که بر اساس نام یا تاریخ مرتب شده‌اند مشاهده کند و به دلخواه بتواند یکی از یادداشت‌ها را انتخاب کند و محتوای آن را تغییر دهد.

**Preconditions**
* User have written 

**Postconditions**
* کاربر در صفحهٔ اصلی نرم‌افزار است.
* کاربر یادداشت‌اش را تغییر داده و ذخیره کرده است.

**Main Success Scenario**
1. کاربر در صفحهٔ اصلی فهرست یادداشت‌های قبلی‌اش را بر اساس تاریخ و محتوا مرتب می‌کند.
2. کاربر یادداشت مورد نظرش را انتخاب می‌کند و آن را باز می‌کند.
3. 

**Extensions**

**Priority**
