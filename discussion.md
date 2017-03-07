# Discussion Paper: HackYourFuture Curriculum

## Purpose

This write-up presents my thoughts on a possible way forward for the HackYourFuture (henceforth HYF) curriculum and is offered as a ‘seed’ for discussion to the gathering of teachers and mentors scheduled for 9 February 2017.

## HYF Mission

The statement ‘*What do we do?*’ on the [HYF web site](http://www.hackyourfuture.net/#/) and repeated below succinctly describes the mission of the HYF curriculum and is assumed here as a given.

> We teach refugees web-development in our 6-month program.

> We teach our students front- and backend development for the web, making them full-stack developers as they finish our course.

> We do this with our group of experienced developers who closely support our students in their process.

> Besides coding we train our students in project-management, becoming independent coders and teach them about the working culture in Dutch companies.

## Where are we now?

The programme has been running for over well a year now. A curriculum has been established that consist of the following training modules:

1. HTML / CSS (3 weeks)
2. JavaScript (+ GIT, CLI) 1, 2, 3 (3 x 3 weeks)
3. Angular (3 weeks)
4. Node (3 weeks)
5. Database (MySQL, Mongo) (3 weeks)
6. (Graduation) Project (6 weeks)

Total: 27 weeks

## HYF Curriculum as a Scrum Project

In the curriculum scrum is gradually being introduced to students as a modern way to execute projects. It is proposed here to adopt scrum for executing the curriculum itself. This could take the following shape:

- Each individual class is a **product** (the deliverable being a group of trained full-stack developers as they progress through the curriculum).
- Each 3-week module is a **sprint**.
- The desired learnings of a module equate to the sprint's **backlog**.

For each sprint an agreed target backlog should be established, to ensure consistency and predictability for follow-on modules. However, it is left up to the individual teachers how to best deliver the topics on the backlog.

It is proposed to establish measurements of ‘success’ for each sprint, e.g.:

   - Number of home work assignments submitted
   - Number of assignments correct

Trello could be used for maintaining scrum task boards (todo, doing, done). By maintaining these boards for individual classes throughout the curriculum teachers and mentors taking turns can quickly familiarise themselves with what has been taught already and which topics could benefit from additional tutoring for the module at hand.

A HYF scrum team should be formed and roles assigned (Product Owner, Scrum Master). Naturally, teachers and mentors are scrum team members.

The curriculum should be kept evergreen through the scrum process of *inspect and adapt*. Appropriate review meetings and retrospectives to be scheduled as appropriate.

Feedback from alumni?

## The Modules / Sprints

### HTML/CSS

**Current situation:** TBD

**Proposed sitation:** TBD

**Rationale**: TBD

**Module Deliverables:** TBD

### JavaScript

**Current situation:** The current JS modules target mainly ES5. Some ES6 features are touched upon. Follow-on modules default back to ES5, with ES6 mixed in, in an ad-hoc fashion.

**Proposed situation:** Teaching starts with ES5, highlighting it pitfalls, and then all training going forward (JS and follow-on modules) to be consistently based on ES6. Exit `var`.

**Rationale:** ES6 is the latest, widely embraced version of JS and solves many issues present in ES5. Although not yet fully supported in all browsers, ES6 is supported in Chrome and Node as used during training. In production environments transpilers and module loaders enable ES6 in all situations.

**Module Deliverables:**

- Basic ES5 training (var, data types, conditionals, loops, function, scope, hoisting, closures, this, callbacks, etc)
- ES6 training (let, const, fat arrow, spread, rest, destructuring, promises, classes, etc)
- Array functions (forEach, filter, map, find, reduce, etc) over loop iteration for collections
- Error handling (try/catch, Node-style error handling)
- Web APIs (DOM etc), JSON
- Debugging JS in Chrome (breakpoints, single step, step in/over, watch, call stack, scope, etc)
- Clean code principles: naming, DRY

### Angular

**Current situation:** Angular 1.5+ has been selected as target front-end development framework. At present it is taught using ES5 by default.

**Proposed situation:** Continue teaching Angular 1.5+, mentioning Angular 2 as emerging. Switch to use ES6 exclusively.

**Rationale:** Angular provides a complete solution for developing SPA front-ends. Angular 1.5+ is probably still the most used production environment as compared to Angular 2. Furthermore, for Angular 2 we would need to add TypeScript to the curriculum and there is simply no slot left in the curriculum to fit it in (unless we can expand the 6-month programme).

**Module Deliverables**:

- Controllers (ES6 classes over ES5 constructor functions)
- Services (ES6 classes over ES5 constructor functions)
- Components (over directives and `ng-controller`)
- Routing (AngularUI Router v1.x component routing over ngRoute)
- Clean code principles: Single Responsibility Principle
- Basic understanding of John Papa's Angular 1 Style Guide

### Node

**Current situation:** TBD

**Proposed sitation:** TBD

**Rationale**: TBD

**Module Deliverables:**

- RESTful API semantics: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`
- Node built-ins: fs, http, path, etc
- Express
- Node debugging (VSCode?)
- Clean code principles

### Database

**Current situation:** TBD

**Proposed sitation:** TBD

- Decide on one (which?) or both DBs: MongoDB and/or MySQL

**Rationale**: TBD

**Module Deliverables:** TBD

### Project

**Current situation:** TBD

**Proposed sitation:** TBD

**Rationale**: TBD

**Module Deliverables:** TBD


### Curriculum Wish List Backlog Items

The list below represents subjects that are not now covered in the curriculum, but, if time was not was not constrained, could be on the wish list. For example:

- lodash
- Babel
- WebPack
- TypeScript
- Angular 2
- React
- RxJS
- Immutable
- Ionic