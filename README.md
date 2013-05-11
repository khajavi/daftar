Daftar
======

A Simple note-taking application.

* Mailing list: daftar-dev@googlegroups.com
* Daftar page on Github: http://daftar-dev.github.io/daftar
* clone Daftar repo: `git clone git@github.com:daftar-dev/daftar.git`

## Use Case
![UseCaseDiagram](usecase.png)



### UC-N: Name

**Description**

**Primary Actor**

**Preconditions**

**Postconditions**

**Main Success Scenario**

**Extensions**

**Priority**



### UC-1: Create new note

**Scope**

**Level**: User-Goal

**Primary Actor**

**Success Guarantees**: The new is created.

**Main Success Scenario**

1. User request system to create new note.
2. System provide user to an area to enter new note (title, body, tags are optional).
3. User can write new note and set title, body and tags.
4. System automaticly save the note as user change it.

**Extensions**

* 4a. Disk is full:
	* 4a1. System prompt disk full to user
	* 4a2. System freeze inputs until disk will be free.

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
