# Project: Campus Explorer

Universities are big places, and involve a large number of people doing a variety of tasks. The goal of this project is to provide a way to perform some of the tasks required to run the university and to enable effective querying of the metadata from around campus.

This will be a full stack web development project split into four sprints (d0-d3). The first three sprints are server-side development using [Node](https://nodejs.org). The fourth sprint involves client-side development. 

Development will be done with TypeScript and the packages and libraries you use will be strictly limited (for the first three sprints). If you do not know TypeScript, you are encouraged to start investigating the language soon. Its syntax is extremely similar to Java so it should be relatively easy to transition to given your prior experience. It is important to note we will not be explicitly teaching TypeScript in this course; you will be expected to learn it on your own time.

All four sprint deliverables will be marked using an automated test suite. The feedback you will receive from this suite will be limited (though verified learners will also receive staff feedback). To succeed at the project you will need to create your own private test suite to further validate each deliverable. Additional details are available on the [AutoTest](AutoTest.md) page.

## Teams

The vast majority of software is written by development teams. Even within large organizations, 'feature teams' usually comprise of a small set of developers within a larger team context. You have the option of working in pairs for this project, or you may work individually. If you choose to work in pairs, your partner must be in the same learning track as you (i.e. verified learners may only partner with other verified learners).

Your partner selection is ***extremely*** important; be sure to make this choice carefully, as you will be responsible for working as a team for the remainder of the project. You must use the same partner for the duration of the project, no changes will be permitted (unless there are exceptional circumstances). NOTE: d0 is an individual deliverable; partners are only for d1, d2, and d3 (and even then, you do not need to work with a partner if you do not wish to).

## Assessment

Each of the four sprints are worth 25% of the final project grade. Since the project is self-paced, you require a 60% grade on a sprint to move to the next. An overall grade of 60% is required to pass the course.

### Sprint 0

This deliverable is graded slightly differently since it is a black-box testing exercise. Please see the deliverable description for more details.

### Sprint 1, 2, and 3

Two components are assessed for these sprints:

* [AutoTest](AutoTest.md) validation (functional completeness).
* Private test coverage.

The general formula for grading is:

`grade = (((AutoTest * .8) + (Coverage * .2) )`

The best way to maximize your AutoTest and Coverage grades is to:

1. Write your own local tests tests that comprehensively test your code against the project requirements. These tests can be run as often as you want and are the best way to debug your code. In our experience, teams that invest in creating a comprehensive test suite with effective assertions completes the project much more quickly.

1. Invoke AutoTest frequently to ensure you have not introduced regressions into your code. Remember: verified learners can only submit to the private suite once every 12 hours, and audit learners can only submit once every 60 hours. AutoTest will also respond more slowly when there is a high volume of submissions.

Your grade will be the maximum value of all `@ubcbot` invocations for a given deliverable (that the bot has responded to).

#### NOTE: On gaming coverage

Achieving 100% test coverage is often hard in practice. To account for this, we will increase your coverage score by 5% in our marking calculations (to a max of 100). The intent of the coverage component is for you to use white box testing to cover your own code; if you cannot invoke a block of code with your own unit and integration tests, we are unlikely to be able to either with our strictly integration-based test suite. Learning what code is important and can catch faults and what code is completely extraneous is an important skill, if you cannot devise a test case or input that can trigger a block, there is a real chance it is just technical debt adding needless complexity to your code. If we find projects that are artificially gaming the coverage metric by adding code solely designed to increase the total number of lines (to decrease the proportion of uncovered code), we will regrade the coverage score to 0 during the deliverable retrospective.

We will be running [Measure of software similarity (MOSS)](https://theory.stanford.edu/~aiken/moss/) on all deliverable submissions. Any projects that contain code derived from other projects that we have not provided will receive 0% on that deliverable.


