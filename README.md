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

**Level**: User-Goal

**Success Guarantees**: The new note is created.

**Main Success Scenario**

1. User request system to create new note.
2. System provide user an area to enter new note (title, body, tags are optional).
3. User can write new note and set title, body and tags.
4. System automaticly save the note as user change it.

**Extensions**

* 4a. Disk is full:
	* 4a1. System prompt disk full to user
	* 4a2. System freeze inputs until disk will be free.

**Priority**
* high



### UC-2: Edit previous notes

**Level**: User-Goal

**Success Guarantees**: The user has changed the selected note.

**Preconditions**
* User has written at least one note.

**Main Success Scenario**
1. The user select previous note and request the system to edit it.
2. The system provide user an area to change the note.
3. User can change the note fields (title, body and tags).
4. System automaticly save the note as user change it.

**Extensions**

* 4a. Disk is full:
	* 4a1. System prompt disk full to user
	* 4a2. System freeze inputs until disk will be free.

**Priority**
* high



