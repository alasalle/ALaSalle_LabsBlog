---
title: Lambda Labs Week 7 Journal 4
date: "2019-04-29T15:55:55.974Z"
description: Labs 4 has been all about sticking with the grind.
---



## Part 1 - Individual Accomplishments


project github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/

github contribution graph: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pulse

github handle: https://github.com/alasalle

During this sprint, I mostly played catch up from the last sprint. Whereas last sprint I laid the foundation for functionality, this sprint involved me taking part in fully setting it up. The majority of my work was in setting up the Review and Project cards to be fully functional with all of the mutations I wrote during the last sprint. I also worked on solving authentication bugs.



### Tasks Pulled


  - Ticket 1:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/52
    - Trello: https://trello.com/c/UvLehJkR/15-review-modal-window

  - Ticket 2: 
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/55
    - Trello: https://trello.com/c/o4RLwvsN/97-authentication-bugs

  - Ticket 3:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/52
    - Trello: https://trello.com/c/gC5i02lO/31-review-list-page-not-empty

  - Ticket 4:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/52
    - Trello: https://trello.com/c/LE8hoWqV/94-create-create-review-component-mutation

  - Ticket 5:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/50
    - Trello: https://trello.com/c/XVY3ZekX/9-create-edit-project-page

  - Ticket 6:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/52
    - Trello: https://trello.com/c/8tv2uBfp/7-project-list



###Detailed Analysis


The majority of my back end work is in github pull request 52 and 50. I completed 5 tickets with 52 and one big one with 50. These pull requests comprise all of the basic functionality outside of searching capabilities for our project. I'll go over a few details for pull request 50 because it had one of the trickier issues to solve. That issue was how to retrieve, display, and save the steps and pictures of any project. We chose to save the steps and pictures as an array in json. Display was fairly simple; I just parsed the json back into an array, stored it in state, mapped over the array, displayed an image for array objects with the type value of "img" and a div for those with a type value of "text," and added a blank array object to the end so users could add to the array. To add a step and save was a little trickier. I had to take in the index of the step that the user was adding/changing, map over the steps array and change the body of the step with the same index, and then add another empty step object for the user. To save, I added a finalize function that precedes submit so the steps array could be cleaned up and turned into json and add a timestamp.


## Part 2 - Milestone Reflections


### Weekly Question

Sadly, we did not really tackle presentation during this sprint. We were all still pretty swamped with completing functionality. I'm proud of the work we did though; We lost 2 team members and another team member got a new job that pulled him away from dedicating much extra time to the project. We also had a difficult project and a brand new stack. I feel that we've performed admirably. I look forward to finally getting to presentation and bug fixing.

