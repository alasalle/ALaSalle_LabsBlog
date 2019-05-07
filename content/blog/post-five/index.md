---
title: Lambda Labs Week 9 Journal 5
date: "2019-05-05T15:34:57.974Z"
description: Labs Sprint 5
---



## Part 1 - Individual Accomplishments


project github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/

github contribution graph: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pulse

github handle: https://github.com/alasalle

During this sprint, I focused on fixing bugs, cleaning up some of the files and folders, and helping the team style the project. There were no major challenges outside of solving the merge conflicts after cleaning up the files and folders. I still have some tweaks I want to make with refetching some queries, but the bugs are largely solved and we're getting close to having the styles the way we want them.


### Tasks Pulled


  - Ticket 1:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/67
    - Trello: https://trello.com/c/Dm4y2OKT/127-project-list

  - Ticket 2: 
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/68
    - Trello: https://trello.com/c/YY5P21JI/128-review-list

  - Ticket 3:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/59
    - Trello: https://trello.com/c/ETJkOlqF/101-style-hamburger-menu

  - Ticket 4:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/65
    - Trello: https://trello.com/c/XNeWwqjb/118-password-change-on-thirdparty

  - Ticket 5:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/65
    - Trello: https://trello.com/c/wN8RiXg8/112-clean-up-folders-and-links

  - Ticket 6:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/65
    - Trello: https://trello.com/c/CvQVPTYX/121-edit-project-bug

    - Ticket 7:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/65
    - Trello: https://trello.com/c/Ga2L5pxE/116-review-card-bug-while-editing

    - Ticket 8:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/65
    - Trello: https://trello.com/c/MzK5oAQS/117-setting-profile-image-bug

    - Ticket 9:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/65
    - Trello: https://trello.com/c/JKQDQ2F4/113-createproject-error

    - Ticket 10:
    - Github: https://github.com/Lambda-School-Labs/labspt2-rate-my-diy/pull/60
    - Trello: https://trello.com/c/0gzjiolB/120-create-project-error-when-click-finalize



###Detailed Analysis


The majority of my work this sprint was in pull request 65, where I went over and fixed bugs, went over a few wonky bits of functionality, and cleaned up the files and folders. Surprisingly, one of the biggest challenges (besides the merge conflicts) in this pull request was just getting the the navigation to recognize when a native signed up user was signed in after I had to change it so the ID that firebase provides on sign-up is added to firebaseID in the database for native users instead of in thirdPartyID. Because of this different information, I had to add a conditional query to check whether the signed in user is a native or third party user and then display the logged in navigation. After I did this, the nav still recognized third party users, but no longer recognized native users. It took me a long time to think of refetching the native user query right after creating a new native user.


## Part 2 - Milestone Reflections


### Weekly Question

We're actually just getting to the point where I'm starting to see the parts of polishing that are going to be challenging. I'm seeing a lot of tweaks that I really want to make, and I'm trying to keep in mind where we need to balance aspirations with our time limit. We do have an extra sprint, so we have a bit of time to go a little beyond MVP. Right now, I'm seeing a lot of queries that can be optimized (and a lot of ways I originally wrote those queries and mutations that maybe could have been smoother and more efficiently placed), refetched, and prefetched. The bugs, thankfully, do not seem to be too much of a problem. I'm sure I'll find a few minor/slightly wonky ones I overlooked, but I'm very close to being happy on the bug front. The styling is getting there too. I will need to make some instances of the project (like on the profile page) less complicated than the project card component for styling purposes and just as a point of good sense. Testing is the other thing we're going to have to focus more on. We're beyond setting up and are into polishing in all aspects of the project except testing.
