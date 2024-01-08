# Zuju
## _Zuju Coding Assignment_

## Overview
✨ Home and View Previous Match's Highlights ✨
 [Demo](./previousMatches.gif)

✨ View Upcoming Match + Add event to calendar ✨ 
 [Demo](./upcomingMatches.gif)
 
✨ View Team Detail ✨ 
 [Demo](./teams.gif)
 
 ## Note: 
 This app was implemented to adapt the response of given's APIs. The data is supposed to be downloaded once and will be used in the whole lifetime of the app. It will need to be upgraded if the APIs have pagination.
## Challenging technical issue I faced:
1. A codebase with different coding styles and architectures: This is usually happen when I start to join a project which has been developed for years by several developers. So what we need to do:
- Study the codebase to understand It's functionalities
- Refactor when possible: we won't refactor the whole codebase once but when we're dealing with each part. For example: We're going to work with feature A, we will develop + refactor It, and we won't touch the feature B as long as we touch It
- Create a coding style guideline and make It as mandatory resource for every developer. 
==> What I learn: I would prefer simple implementation rather than complex implementation, don't make thing complexity and don't chase with new technology if you're not ready yet! Cuz in the end of the day, our result is a good product for users and good code for our collegues! Good code is good document, we don't need to add comment if we have clean code.
2. Bug from third party: We usually use third parties inside our application because It will help us to save a lot of time developing. But sometime It's annoying to be facing a bug from the third party. I faced that sometimes and this is one of my experience:
- When I was working at GIANTY, we have a project to capture user's face and apply filter to make the face looks prettier, the project was integrated with [GPUImage](https://github.com/BradLarson/GPUImage) but we faced an issue while resizing the camera (I posted issue [here](https://github.com/BradLarson/GPUImage/issues/2479)) 
- My approach was:
    - I tried myself to debug and find the cause
    - If I couldn't fix it, I will search inside github's repo and google to see if anybody shares the same issue
    - If there's no given solution, I will try to ask for help
    - I will try to implement a workaround or request the stakeholders of the product to adjust the flow if there's no solution which can solve that issue completely

==> What I learnt: 
- Use native's framework as much as possible 
- Only use third party if we can't implement that feature or time is limited



