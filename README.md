# Trace-Labs-Search-Party-CTF-Writeup-June-2026
<p align="center">
  <img width="200" height="200" alt="bb0b5a25a8e4fc409329da44a830be8612fcb1f2eba2b977878a411aa614639c" src="https://github.com/user-attachments/assets/8ca662a3-545a-4b5d-961d-1c168b2d1bc7" />
</p>

[Work in Progress]

The Trace Labs Search Party CTF is a non theoretical, gamified effort that allows for the crowdsourcing of contestants to perform a single task: Conduct open source intelligence operations to help find missing persons.

## Summary/Background: 
This CTF focused on identifying information about a target using open-source intelligence (OSINT) techniques. Starting with the information provided in the challenge, I conducted a series of searches across search engines, social media platforms, and other publicly available sources to locate relevant information. This writeup documents the steps I took, the tools I used, the obstacles, I encountered, and the evidence that led me to my final answer. Due to the nature of the work, I'm not allowed to share any of the specific names, images, or related information about the MPs cases themselves. However, I can still go over the techniques used and my thought process as I progressed through the competition/investigation.

For context, all of the work done for this CTF was completed by myself. I was not in a team, but I was accomodated by a coach during the entire time of the competition (as provided by TraceLabs). The CTF only lasted a total of 4 hours. It was a jeapardy-style CTF, but instead of flags being concrete answers that the competition challenge developers know about, the flags are potentially helpful information that law enforcement would be able to use in order to help find the MP (missing person).

Team name: its_just_gman

Ranking: 
103rd, 70 points
<img width="2184" height="750" alt="image" src="https://github.com/user-attachments/assets/5abbb35a-7cf6-4bb9-a509-c81fbf7c5f34" />


## MP (Missing Persons) Challenge:
### Initial Phase
Due to the difficult nature of the challenges, I focused most of my attention and effort on one particular missing persons (MP) case. I started of initially with some simple google dorking techniques (e.g. site:platform.com "Person Name"). I used these techniques to look for any signs of activity on various platforms, including Instagram, Facebook, Youtube, and LinkedIn. 

The following image shows what kinds of information counts as flags and how many points each type of information was worth. 
<img width="757" height="452" alt="image" src="https://github.com/user-attachments/assets/2328f267-8e90-4393-be68-76c03c0efca9" />

My strategy was to focus on employment info and basic subject info, categories in which I felt I would be able to capture flags, while also choosing a category in which the points for each flag was worth a relatively substantial amount. In other words, I wanted to feel like I was earning enough points when it came to actually capturing the flags. 

I had eventually found a facebook post that served as a sort-of baseline of information that I could work with. It was from a missing persons page stating some facts about the MP. Some of the information included:
- Interests
- Childhood/upbringing
- Education
- Employment

Since this was from a social media page however, I would not be able to submit this post by itself for it to count as a flag. Even if it were not a CTF, it would be helpful to provide evidence to back up this information. The first thing I decided to search for was education information. I first used google dorking technique to see if a profile would pop up on LinkedIn. I did not find anything related to him on LinkedIn. I did however find a local news bulletin that published an article on a couple of the recent graduates (class of 2022) that graduated from a local university, one of which happened to include the MP. A similar post found on X (Twitter) also confirmed this, so enough evidence was found to confirm that the MP was in fact a graduate of said university.

### Hours 2 and 3 of the CTF
The missing persons post suggested that the MP worked at a medical center of some kind. As mentioned before, I first used google dorking techniques on LinkedIn to see if a profile would come up. Nothing was found, so I looked through the company LinkedIn page instead. It's possible that the MP was not active or didn't regularly use LinkedIn, so their account would probably not be set up completely. If that was the case, it would also be possible that the account would be under the name "LinkedIn Member" rather than their actual name. 
