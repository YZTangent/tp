---
layout: page
title: Tan Yuan Zheng's Project Portfolio Page
---

### Project: FinBook
to be added soon

### Overview

to be added soon

### Summary of Contributions

* **Code
  contributed**: [RepoSense link](https://nus-cs2103-ay2223s1.github.io/tp-dashboard/?search=yztangent&breakdown=true)

* **Enhancements implemented**:
    * **Update feature**: Change edit command to add onto tags, plans and notes instead of overwriting them
      * What is does: allow the user to add onto the current tags, plans, and notes of a client more easily 
      * Justification: Often users would want to add tags, plans or notes to their clients as they engage with them. Hence, it makes more sense for the edit comamnd to add onto current tags, plans, and notes, as it would be a huge hassle to have to copy over the client's the current tags, plans, and notes on top of what they plan to add.
      * Highlight:
        * To allow the user to remove tags, plans, and notes that are no longer relevant, the remove feature was added.
        * Any tags, plans or notes that the client already possess are ignored to prevent duplicates.
    * **New feature**: Remove command 
        * What it does: Allows the user to remove tags, plans, and notes from clients.
        * Justification: Lets the user remove unwanted tags, plans, and notes from clients, as the edit command now adds onto current tags, plans and notes without overwriting them.
        * Highlights:
          * The user can remove any amount of tags, plans or notes in any combination.
          * Any tags, plans, or notes passed into the command that is not present on the client will simply be ignored.
    * **Update feature**: Add client to include meeting location attribute, and refactor all meeting related fields into the encapsulating meeting field
      * What is does: allow the user to add meeting location(optional) to the client
      * Justification: Meeting location is an import information for users to capture as well on top of the next meeting date. Hence, this field has been added to be stored as part of a client's attributes in Finbook.
      * Highlight:
        * Meeting location is made optional because there could be instances where a meeting location has not been
        settled among the user and client.
        * Meeting location will be automatically deciphered as online or in-person by Finbook using URL recognition. Any addressed that is passed to Finbook that is a valid URL will be categorised as an online meeting.

* **Contributions to the UG**:
    * Add remove command and its usage details to the UG
    * Update list of prefixes to include meeting location
    * Update edit command to reflect its new behaviour
    * Add labelled diagrams to illustrate the difference between hidden and shown mode and highlight its toggle button
    * Add labelled diagrams to highlight the  toggle button to switch between dark and light mode

* **Contributions to the DG**:
    * Add user stories for the meeting location feature
    * Add user stories for the remove feature
    * Update UML class diagram to include MeetingLocation, Meeting and Note classes

* **Contributions to team-based tasks**:
    * Assign milestone to straggling v1.4 issues
    * **Code Refactorization**: Refactor code for optional attributes in Person class to make use of Java's Optional abstraction
      * What is does: Using the java Optional abstraction allows us to refactor many checks for empty (or null) values for these optional attributes into the attribute class itself
      * Justification: There are many places in the code which requires a check for null values for optional attributes, which is a violation of Don't Repeat Yourself (DRY) principle. By abstracting out all these checks into the attribute class with the use of the Optional abstraction provided by the Java utils library, we are able to closely adhere to good coding principles.

* **Review/mentoring contributions**:
    * Helped to review pull requests from teammates. (E.g. PR Reviewd: [Sort command #88](https://github.com/AY2223S1-CS2103T-T08-4/tp/issues/137))

* **Contributions beyond the project team**:
    * Reported bugs and suggestions for other teams. 
    * Issues: 
      * [Headers not visible on startup #137](https://github.com/AY2223S1-CS2103T-T08-4/tp/issues/137),
      * [Sample input for addtut in the app is invalid due to incorrect time format #149](https://github.com/AY2223S1-CS2103T-T08-4/tp/issues/149),
      * [Example input for Deleting a tutorial command contains a typo #155](https://github.com/AY2223S1-CS2103T-T08-4/tp/issues/155),
      * [Unable to view questions longer than the text box can display #165](https://github.com/AY2223S1-CS2103T-T08-4/tp/issues/165),
      * [Dates from 29th Feb to 31Feb are taken as valid inputs but are parsed as 28th Feb #173](https://github.com/AY2223S1-CS2103T-T08-4/tp/issues/173),
      * [Deprecated commands and data still present #175](https://github.com/AY2223S1-CS2103T-T08-4/tp/issues/175)

    

* **Others**:
  * [PRs by me](https://github.com/AY2223S1-CS2103T-F11-3/tp/pulls?q=is%3Apr+author%3Ayztangent)