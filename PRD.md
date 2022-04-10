# PRODUCT REQUIREMENT DOCUMENT

## `Background` 

YouTube's primary sources of revenue is Advertisements. While the focused revenue model benefits the users (owner), frequent in-feed video ads can  be a factor in dwindled user experience.

The "in-feed ads" on the video streaming platform are:

 -  Skippable in-stream ads
 -  Non-skippable in-stream ads
 -  In-feed video ads
 -  Bumper ads
 -  Outstream ads
 -  Masthead ads

While In-feed video, Bumper and outstream ads appear in either the search page or during the video playback in the form of a banner or a short message, *Skippable in-stream and Non- skippable in-stream ads* can be place in the beginning, during or in the end of the playback, which affects the overall viewing experience directly. 

> Initially, the in-stream ads could be skipped anytime and were limited to a couple in about 1 hour playback. However, over the time the frequency has been changed to > 1 ad in every 10 min. In certain cases a user can be forced to watch 12 cascaded (double - 24 ads) ads during a *single playback* of 60 min, the overall experience receives a significant amount of damage. 



---


 ## `Goal`


While the platform proffers the premium subscription model for ad-free viewing experience, however, majority of the users prefers to stay on the basic version. 

```
Our objective is to improve overall viewing experience by offering end-user some flexibility of going Ad-Free for a relatively
shorter period of time. 
```

### Strategic Fit

---

## `Scope`

### Technical Assumptions

 1. The user interation is with smartphone device.. 
 2. Platform is accesses via Crome browser, i.e; *m.youtube.com* is accessed. 



### User Personas

Although the user base on YouTube can be classified on various grounds and based on various different parameters, the audience is divided in 4 broad sections:

- **Casual viewers**: There main objective is to have entertaintment. The tags varies over a large area.
- **Skill developers**: The university/school students who wants to build a skill (ex: programming language) and/or professionals who are seeking a career switch.
- **DIY enthusiasts**: Users who are interested and invested in *Do-It-Yourself* videos. Users engagement can/may vary from cooking receipies to craftsmanship. 
- **Current affairs & trend followers**: They want to watch a live video of a current event or listen to news / analysis about an event.


>Average run-time for the skill development and DIY content is longer than that of other categories. The proposed solution is conceptualized keeping **Skill developers** & **DIY enthusiasts** in the epicenter.

### Pain Points 


Since the average runtime of the highlighted content genre is substantially larger than that of other categories, it is assumable that viewers take break(s) in between. However, the overall user-experience reduces:

 1. when user have to watch multiple ads during the same video.
2. when user have to pause the video for longer than 60 min and upon resuming a new ad is forced upon.
3. when user have to pause the video for longer than 60 min and has to reload the video with a forced ad.
4. when user have to switch between videos for connected content and have to watch ads upon switch. 



**User Story** | **Requirement** | **Priority**
-----------|-------------|---------
 As an end-user, I want to be able to watch a video uninterrupted.| The platform must allow the user an option to go ad-free just for a given video | Must have
 As an end-user, I should be able to resume my videos, after a long duration, from the point where I paused it.| The platform must ask the user to resume the video after a long pause without imposing new ad| Must have
 As an end-user, I do not want to see ads again when I switch back from another video to the ongoing playback. | The platform must provide and ad-free time period where content switching is permissible.| Must have
 As an end-user, I would like to get option to skip ads irrespective of the nature of ad.| The platform should provide an option to skip (tim- bound) Non- skippable in-stream ads| Optional
 
---
## `Viable Solutions`

Based on the user stories and requirements, following feature(s) are devised so that a user will be able to choose whether to:

- Enjoy the whole video without any ad(s)

  - This feature not time-based. The user can start a video and watch it at his/her convenience with no-ad(s) for that particular video.
  - Irrespective of the amount and duration of in-between pauses.
  - valid for a single run-time.

- Get an option to skip ads with advance notification of upcoming ad.

  - For a running video, the system notifies the viewer 30 seconds before an upcoming ad. 
  - Thus giving the user ample amount of time to decide whether to watch it or skip it.

- Get an ad-free time bracket. 

  - Allows a user to go ad-free for a certain amount of time.
  - The time can range from 60 min to 600 min.
  - The user can select a particular timeframe as well [1030 - 1515]

The above feature can be availed by the user in the form of 

 > ### 1. Limited Ad-free experience for a Cost.


   The user can avail the proposed features by paying a certain defined amount.


 |  **Pros** | **Cons** |                                         
 |  :----- |    :---- |                                           
 | Simple pricing structure |     Extra financial burden on users|                         
 | Wide payment options including Google play card | 
 | Easy to acquire | 
  
 

 > ### 2. Limited Ad-free experience for Survey(s) Participation.


  The users can fill survey forms and participate in voting surveys to earn ad-free time. 

|  **Pros** | **Cons** |
| :------- | :---- |
| No extra financial burden on the user | Long surveys can be time-consuming. |
|Easy to fill surveys. | videos of long runtime will incur multiple surveys/polls |
|Pollings offered in regional language | No flat ad-free credit method.|
||The amount of ad-free time or skip-passes collected will vary based on the survey and polls.|




 > ### 3. Limited Ad-free experience for Ad(s) Accrued in future videos.
  
  
  The user can chose to go ad-free at for a given time and accrue all the ads over the future video(s).  

  | **Pros** | **Cons** | 
 | :------ | :-------- |
 | Easy to comprehend process | Ads are not been removed or skipped, its just delayed |
 | No upfront cost for the user | limit over the permissible accrual of ads |
 | handy in case of urgency | not suitable for long duration videos, as a single video might fill the accrual threshold of ads |  




After analysing implementation medium against each other, `Limited Ad-free experience for a Cost` seems to be the best suited option. The simplicity of the structure and pricing method certainly outshines amongst all other and thus is to be implemented.   


---

## `Success Criteria`

## `Follow up tasks`

Upon submission of the above Product Requirement Document, following actions are required to be taken:

 1. Communicate the requirement with the stakeholders and validate the completeness.
    - The PRD must satisfy the stakeholders' need along with the corresponding performance, environmental and non-functional requirement metrics. 
    - `Requirement Tracing` shall be employed in event of any available voids.
 
 2. Refine, Analyze and Defragment Requirements.
 3. Validate Requirements
    - Each and every requirement(s) listed or further derived shall be verified and validated to ensure the accuracy. Our derivations must meet the overall objective.

4. Move to System Engineering.
   - Upon successfull validation, move the requirement to the production. 
