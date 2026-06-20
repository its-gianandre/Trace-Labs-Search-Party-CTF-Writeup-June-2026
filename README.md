# Trace-Labs-Search-Party-CTF-Writeup-June-2026
<p align="center">
  <img width="200" height="200" alt="bb0b5a25a8e4fc409329da44a830be8612fcb1f2eba2b977878a411aa614639c" src="https://github.com/user-attachments/assets/8ca662a3-545a-4b5d-961d-1c168b2d1bc7" />
</p>

### [Work in Progress]

The Trace Labs Search Party CTF is a non theoretical, gamified effort that allows for the crowdsourcing of contestants to perform a single task: Conduct open source intelligence operations to help find missing persons.

## Summary/Background: 
This CTF focused on identifying information about a target using open-source intelligence (OSINT) techniques. Starting with the information provided in the challenge, I conducted a series of searches across search engines, social media platforms, and other publicly available sources to locate relevant information. This writeup documents the steps I took, the tools I used, the obstacles, I encountered, and the evidence that led me to my final answer. Due to the nature of the work, I'm not allowed to share any of the specific names, images, or related information about the MPs cases themselves. However, I can still go over the techniques used and my thought process as I progressed through the competition/investigation.

For context, all of the work done for this CTF was completed by myself. I was not in a team, but I was accomodated by a coach during the entire time of the competition (as provided by TraceLabs). The CTF only lasted a total of 4 hours. It was a jeapardy-style CTF, but instead of flags being concrete answers that the competition challenge developers know about, the flags are potentially helpful information that law enforcement would be able to use in order to help find the MP (missing person).

Team name: its_just_gman

Ranking: 
103rd, 70 points
<img width="2184" height="750" alt="image" src="https://github.com/user-attachments/assets/5abbb35a-7cf6-4bb9-a509-c81fbf7c5f34" />


## MP (Missing Persons) Challenge:
### Initial Phase (Hour 1)
Due to the difficult nature of the challenges, I focused most of my attention and effort on one particular missing persons (MP) case. I started of initially with some simple google dorking techniques (e.g. site:platform.com "Person Name"). I used these techniques to look for any signs of activity on various platforms, including Instagram, Facebook, Youtube, and LinkedIn. 

The following image shows what kinds of information counts as flags and how many points each type of information was worth. 

<img width="757" height="452" alt="image" src="https://github.com/user-attachments/assets/2328f267-8e90-4393-be68-76c03c0efca9" />

We were given pictures of the MP, where they were last seen, when they were last seen, a short biography, demographics, unique identifiers, the scenario that played out before they went missing, and for this particular MP, we had a phone number and email address. 

My strategy was to focus on employment info and basic subject info, categories in which I felt I would be able to capture flags, while also choosing a category in which the points for each flag was worth a relatively substantial amount. In other words, I wanted to feel like I was earning enough points when it came to actually capturing the flags.

Going back to the actual search, I tried some simple email lookup and phone number lookup tools. Unfortunately the only thing that returned was a soundcloud account under the email. 

I had eventually found a facebook post that served as a sort-of baseline of information that I could work with. It was from a missing persons page stating some facts about the MP. Some of the information included:
- Interests
- Childhood/upbringing
- Education
- Employment

Since this was from a social media page however, I would not be able to submit this post by itself for it to count as a flag. Even if it were not a CTF, it would be helpful to provide evidence to back up this information. The first thing I decided to search for was education information. I first used google dorking technique to see if a profile would pop up on LinkedIn. I did not find anything related to him on LinkedIn. I did however find a local news bulletin that published an article on a couple of the recent graduates (class of 2022) that graduated from a local university, one of which happened to include the MP. A similar post found on X (Twitter) also confirmed this, so enough evidence was found to confirm that the MP was in fact a graduate of said university.

### Hours 2 and 3 of the CTF
The missing persons post suggested that the MP worked at a medical center of some kind. As mentioned before, I first used google dorking techniques on LinkedIn to see if a profile would come up. Nothing was found, so I looked through the company LinkedIn page instead. It's possible that the MP was not active or didn't regularly use LinkedIn, so their account would probably not be set up completely. If that was the case, it would also be possible that the account would be under the name "LinkedIn Member" rather than their actual name. Needless to say, I did not find any profiles of the MP on LinkedIn to confirm their employment. Unfortunately, the only information regarding an employee database was blocked by a paywall, so any information regarding employment was not confirmed.

### First Flag
I shifted directions and looked at potential sports groups that the MP was a part of, since the original facebook post mentioned that they were involved in hockey since their childhood. I again used google dorking techniques to find basic information on the MP. The results returned some old but potentially useful information: team roster information from two separate hockey teams in their youth. Although this may not yield as super useful information, the information found could serve as the following: 

- Age cohort estimation - teammates are usually within a narrow age range, helping establish likely graduation years and social circles.
- Geographic information - membership of the team in said location helps corroborate residence during a specific period.
- Associates and contacts - teammates, coaches, managers, and parents can be come potential sources of information in missing-person investigation
- Timeline construction - confirms participation in a specific organization during a specific season
- Nickname and identity verification - rosters sometimes contain alternate spellings, initials, or jersy numbers that help correlate records across platforms

### Last hour of the CTF
I decided to get some last-minute flags by looking up some information on family. This was fairly simple. Because of the nature of missing persons posts, many family members will step up and speak out about the situation. I was able to find a couple of family members related to the MP through a comment on an existing missing person's post on Facebook. The following family members were found:
- Grandmother of the MP
- Granddaughter of the grandmother (potentially the MP's cousin)

## Conclusion
This CTF was my first opportunity to apply OSINT techniques in a real-world situation. Unlike traditional CTFs that have predefined answers, this competition required participants to gather information that could potententially assist law enforcement and investigators, making the process far more open-ended and challenging.

Throughout the four-hour event, I learned the importance of developing investigative leads from small pieces of information and validating findings through multiple independent sources whenever possible. While I was unable to confirm every lead I pursued, I successfully identified and documented several pieces of information related to the mising person's education, sports participation, and family connections. More importantly, I gained experience building timelines, corroborating information, and assessing the reliability of publicly available sources.

One of the biggest challenges I encountered was dealing with incomplete information and dead ends. Many searches produced little or no useful information, requiring me to continously adapt my approach and pursue alternative avenues of investigation. This reinforced the importance of flexibility and persistence during OSINT investigations. 

If I were to participate again, I would spend more time prepareing a structured workflow for evidence collection and note-taking. I would also become more familiar with additional OSINT tools and techniques that could help accelerate the investigation process under strict time contraints.

Although my final score of 70 points and placement of 103rd may not appear exceptional compared to more experienced competitors, the event provided valuable practical experience and highlighted areas where I can continue improving OSINT and investigative skills. Most importantly, the competition demonstrated how OSINt can contribute to real-world humanitarian efforts by supporting investigations into missing-person cases.

## Tools Used:
- Google Search
- Microsoft Edge
- Google Dorking
- LinkedIn
- Facebook
- X (Twitter)
- SpokeO (Name, email and phone number lookup)
- Public news articles
- Team roster databases

## Lessons Learned:
- Validate information using multiple independent sources whenever possible.
- Dead ends are a normal part of OSINT investigations.
- Family members and community organizations often provide valuable investigative leads.
- Time management is critical in short-duration OSINT competitions.
- Maintaining organized notes can significantly improve investigative efficiency.
