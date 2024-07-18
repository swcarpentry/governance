# Minutes for July 4th, 2024

## Attendees
- Martino Sorbaro
- Samantha Ahern
- Valentina Hurtado-McCormick
- Annajiat Alim Rasel

## Agenda
1. Welcome to Annajiat - brief introduction and your role(s) in the Community.
1. Updates from Sam - highlights from her participation in events in the UK.
1. Updates from Valentina - highlights from her participation in Carpentry Connect AU-NZ 2024.
1. Revitalising Git
    1. Valentina's attachment on Australian workshops
    1. whats the policy on a large lesson change when other translated languages are affected?
    1. spanish lesson is not on workbench
    1. approving change to recipes
    1. (for the future) intermediate lesson in incubator
1. Pending tasks from the last meeting's minutes.
1. Survey proposal on episode timing
1. Status of incubator lessons

## Notes
**Action items are indicated with @.**

### Introductions with Annajiat
Introducing each other with Annajiat. Annajiat tries to contribute through multiple roles within the community.

### Updates on events and conferences
Sam: RSECon conference in September. Collaborations workshop didn't get accepted, but there will be a session on the lesson programme. I will also go to Heidelberg to CarpentryConnect. There will be a hackday where we can work on lessons. We will chat with the community on what they'd like to see pulled through. Valentina: it's good to start off introducing what the governance committee is. Also note -- we now have maintainers for the Matlab lesson.

Valentina: Different sessions in the CarpentryConnect Au-Nz. This doesn't happen very often and this was a big one. There were online and in-presence sessions. Most people from universities, with representation from all big universities in Perth. There is an interest in joining efforts because there is a huge need for Trainers in Western Australia and only UWE has Trainers. The other session in the afternoon was about git mostly: people are interested in the changes. We asked what changes are needed and how they should happen.

### Git lesson: discussion of changes
Valentina presents a document prepared by ARDC people, which contains a survey on git and the git lesson. It first shows which kinds of people were in attendance, to ensure they were ready to talk about Git.

A first point that arose is that of the theme: should we use actual examples of code and data in the lesson instead of toy examples? People in the survey preferred a story based on actual data. The LPGC discusses the options briefly, and concludes that *data* is not a good choice, since data are not typically stored in version control systems, and doing so can cause problems. However, we agree that we need to change the Dracula/Wolfman topic. We approve of the proposed change to a recipe-based theme. Martino has prepared a PR from UCL's repository.

A second point of discussion is that of including more about GitHub, collaborating, and branching in the lesson. The Perth discussion, Valentina reports, suggested splitting the lesson in two: one mostly about Git basics, one about GitHub and collaborating. Annajiat: in favour because of time issues in teaching the whole git lesson. Sam: I wouldn't want to lose the Github part in the first lesson, because that's useful already at a basic level, but the ssh part is a pain as it is. Valentina: the two could be connected, and we could have a teaser of GitHub at the end of the Git lesson, which would then be an extended version. Martino: the lesson in the incubator does have branches and more on collaborations so we can start from there. CodeRefinery does have two lessons divided along these lines.

No final decision is taken on these matters due to time issues. However, we will keep analyzing the versions on the incubator.

Finally, Martino points out that large changes cause downstream issues to the maintainers of the Spanish-language versions. This topic will be discussed with the internationalization community.

### Next meeting
The next meeting is scheduled on 12 August, 10 am CEST. Among the topics to be discussed are again the git lesson, and the other lessons in the incubator.