# Cornell’s Version of MIT’s “Missing Semester” :D

## The basic idea

I think it would be really cool for Cornell to have its own version of MIT’s [Missing Semester of Your CS Education](https://missing.csail.mit.edu/).

The idea would be to create some kind of practical, unofficial “in-between” course (we could call it, say, CS 2999, CS 3001, or something similar) that students could “take” after the introductory 2000-level CS classes but before getting too deep into the 3000-level classes.

This could be hosted on a canvas page, maybe a wesbite with a cornell domain?

There are a lot of tools that CS students are suddenly expected to know how to use, even though nobody ever really teaches them all in one place. Here are two personal examples:

1. **$\LaTeX$**

   When I took CS 2800, I never used $\LaTeX$. Instead, I would write my proofs with pencil and paper, take a picture, and submit it to Gradescope. Then, in CS 4820, the syllabus stated that all homework had to be typeset, with the only further instruction being a very small pointer to some external $\LaTeX$ references at the very bottom of the [course resources page](https://www.cs.cornell.edu/courses/cs4820/2025fa/resources/#sec-typesetting).

   This is not meant to be construed as a “dig” at the professor. Prof. Chattopadhyay is an amazing algorithms professor, and his job is to teach algorithms, not $\LaTeX$! Unfortunately, my unfamiliarity with $\LaTeX$ was a major bottleneck for me that semester, and I had to dedicate a *lot* of time to learning $\LaTeX$ syntax when I could have been learning the course material.

   One workaround that many of my classmates and I used was to write our final solutions on paper, take a picture, and upload it to an LLM with the prompt, “Please turn this into $\LaTeX$ code.” This *mostly* worked, but it was still far from perfect. Often, the LLM would hallucinate not only symbols I had never written, but entire sentences I had never written. Catching these errors required an additional, in-depth review of the produced document beyond the usual double-checking I would do before submitting my work.

   To be quite honest, I did not do very well in algorithms, and I am *not* blaming that on the professor or on my unfamiliarity with $\LaTeX$, as the class is notoriously difficult on its own. All I am saying is that students could benefit greatly from having more time to dedicate to learning the course material rather than learning $\LaTeX$.

2. **Git**

   Git is one of those topics that feels like it is tossed somewhere between CS 3110 and CS 3410. In CS 3410, I mainly needed a relatively basic understanding of Git to pull homework repositories, make changes, and submit my work. In CS 3110, however, the final group project required a much broader understanding of good Git practices and the technical details needed to collaborate smoothly.

   Suddenly, it was not enough to know how to run `git pull`, `git commit`, and `git push`. We needed to understand branches, merge conflicts, pull requests, remotes, and how to coordinate multiple people making changes to the same repository. We also needed to know what to do when something went wrong, such as accidentally working on the wrong branch, creating a confusing commit history, overwriting someone else’s changes, or ending up with a merge conflict right before a deadline.

   Once again, this is not a criticism of either course. CS 3110 is supposed to teach functional programming, and CS 3410 is supposed to teach computer systems. Neither course has enough time to stop and teach Git from the ground up. However, that means students can enter a major group project with wildly different levels of Git experience. One person may already be comfortable with branches and pull requests, while another may have only ever cloned a repository and pushed directly to `main`.

   This can create a weird situation in which the difficulty of a group project comes not only from the actual programming, but also from trying to figure out how to collaborate without breaking the repository. Students often end up learning Git through trial and error while simultaneously trying to complete a major assignment.

   A dedicated introduction to Git would give students the chance to make mistakes in a low-stakes environment. They could intentionally create and resolve merge conflicts, practice working with branches, review each other’s pull requests, recover deleted work, and learn how to inspect a repository’s history before they are expected to use these skills on an important project.


An interactive (a feature that the Missing Smeester notibly lacks: interactibility) Cornell version of the Missing Semester could bring all of that together and teach the practical skills that make Cornell's 3000+ classes much smoother.



## Possible main chapters

### 1. Git

The goal should be to help students *understand what Git is actually doing and the abstractions behind it* so that they can reason through unfamiliar situations instead of copying commands and hoping they work. It would be especially helpful if the examples were based on situations Cornell students actually run into, particularly group projects and Cornell GitHub repositories. One cool idea could be be a “Git disaster lab” where students are given a deliberately broken or confusing repository and have to figure out what happened and recover the work.

### 2. $\LaTeX$

A possible "project" could be creating a multi-file $\LaTeX$ document with questions, solutions, linked lemmas, figures, citations, and a bibliography.

### 3. Other potential miscellaneous Practical CS Tools

This could be a collection of smaller topics that are extremely useful but do not always fit naturally into another Cornell class.

Possible topics:

#### Github actions
I find this suuuuuuuuper helpful in my own personal development 

#### Basic Docker
This is also used in CS 3410, but students are simply told to run a docker command instead of understanding what it is actually doing, which always feels unsatisfactory to me.

#### Command line stuff

always helpful

#### Conclusion / Cornell CS Course Map

One thing that I think would be especially cool is ending the course with a full, detailed prerequisite graph of Cornell CS courses that includes this course itself.

The current [Cornell CS course catalog](https://catalog.cornell.edu/courses/cs/) has the official prerequisite information, but it is not very visually helpful.

There is also Cornell Engineering’s [Computer Science flowchart](https://www.duffield.cornell.edu/advising/choose-your-academic-pathway/engineering-major-flowcharts/), but it is mainly Engineering-specific, and the version currently linked is labeled for 2025.

Adrian also made a more 3410-based informal course map [here](https://cornell.app.box.com/s/gj82dik1cfttcry6o8zvvejln49svq2v/file/2214766072469), which is closer to the kind of thing I am imagining.

I think Cornell could make a much more general, Bowers-focused version that works for students across different colleges.

It could be color-coded by area, such as systems, PL, ML, graphics, etc.

An interactive version would be especially cool. You could click on a course and see its description, prerequisites, the semesters in which it is usually offered, the requirements it satisfies, etc.

This is definiely more of a side-quest / different project than our original idea but still something I think is cool.


