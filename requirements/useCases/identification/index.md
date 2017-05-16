<link rel="stylesheet" href="{{baseUrl}}/css/textbook.css">

<div class="website-content">

#### Identifying use cases for a system

<div id="main">

A use case is an interaction between a system and its _actors_.

**Actors in Use Cases**

An actor is a role played by a user.  An actor can be a human or another system. Actors are not part of the system; they reside outside the system.

For example, consider the software system: LearnSys (a fictitious
<popover effect="fade" placement="right" content="Learning Management System">
    LMS
</popover>
).

<tip-box>

Some of its actors would be: Guest, Student, Staff, Admin, ExamSys (an exam management system), LibSys (a library management system).

</tip-box>

A use case can involve multiple actors.

<tip-box>

```
Software System: LearnSys
Use case:  UC01 conduct survey
Actors: Staff, Student
```

</tip-box>

An actor can be involved in many use cases.

<tip-box>

```
Software System: LearnSys
Actor: Staff
Use cases: UC01 conduct survey, UC02 Set Up Course Schedule, UC03 Email Class, ...
```

</tip-box>

A single person/system can play many roles.

<tip-box>

```
Software System: LearnSys
Person: a student
Actors (or Roles): Student, Guest, Tutor
```

</tip-box>

Many persons/systems can play a single role.

<tip-box>

```
Software System: LearnSys
Actor(or role) : Student
Persons that can play this role : undergraduate student, graduate student, a staff member doing a part-time course, exchange student.
```
</tip-box>

{some guidance on identifying actors and use cases}

Use cases can be specified at _various levels of detail_.

<tip-box>

Consider the three use cases given below for the LearnSys system.

<ol type="a">
  <li>Conduct a survey</li>
  <li>Take the survey</li>
  <li>Answer survey question</li>
</ol>

Clearly, (a) is at a higher level than (b) and (b) is at a higher level than (c). While modeling user-system interactions, start with high level use cases and progressively work toward lower level use cases. It is also important to be mindful at which level of details you are working on and not to mix use cases of different levels.

</tip-box>

{some guidance on using diagrams vs other means}


<!-- extras ------------------------------------------------------------------------------------ -->

<panel header=":paperclip: Extras" expandable type="seamless" expanded>

  <panel header=":mortar_board: Learning Outcomes" expandable type="seamless">
    <include src="exercises.md" />
  </panel>

  <panel header=":package: Resources" expandable type="seamless">
    <include src="resources.md" />
  </panel>

</panel>

</div>

</div>
