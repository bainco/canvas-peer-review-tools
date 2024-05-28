# canvas-peer-review-tools

This repo is the result of my efforts to integrate Peer Review of Programming Assignments in a large-format introduction to computer science course.

Our goal was to show that programming, like writing an essay, isn't a process that ends right when it works, but instead is a process of testing, feedback, review, and revisions. To achieve this goal, we aimed to mostly take advantage of Canvas LMS's built-in Peer Review tools.

Unfortunately, not all went to plan so we had to design some specialized tools to fix those problems.

* While Canvas **happens** to support previewing `.py` files in its preview window, when assigned as a peer review **it prevents students from downloading the submission** which means they can't actually download it to their computer and run it like a regular computer program.
* In order to make it a "graded" peer review, Canvas insisted I needed to assign rubric items points. Well, my goal was _participation_ in the Peer Feedback process, so I made all rubric selections equal in terms of points (i.e. someone's feedback doesn't affect your grade).
* Turns out...when you do this, Canvas actually _incorrectly displays_ the selections on the rubric to the person who you gave feedback. It'll show the correct number of points, _but it shows category selections wrong_!!!
* If someone didn't submit the assignment that's being peer-reviewed, they don't automatically get assigned a peer's submission to review
* That's fine...but it doesn't say that when you generate the assignments, so I mistakenly assigned those people a peer's submission to review which Canvas then notifies them about...**but won't actually allow them to submit it.**
* As usual, a small number of students took advantage of my lack of specificity in the instructions "leave a comment on each rubric item indicating why you selected that rubric item" and simply wrote one word answers to most of the comments.

You can find all the code I used to solve those problems at in the `ipynb` file with some instructions. You can learn more about the project, completed as part of [Northwestern's Searle Fellows Program](https://searle.northwestern.edu/programs-services/initiatives/searle-fellows.html) by visiting my [project portfolio](https://bainco.github.io).
