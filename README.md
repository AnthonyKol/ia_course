# ActiveJobSeeking

Final project for the Building AI course

## Summary

The core idea of it is that the user choose a minimum number of interview he would like to have per week. The system will match him automatically with the most relevant job offers and schedule them automatically.


## Background

Overall today we are overloaded in information, and it's the same for a job research. We have now a very high number of job seekers confronted to a very high number of jub offers, and in the end both companies and job seekers get lost in it. It raises issues on both sides :
- Companies loose a lot of time to manage all candidates, plan interviews, etc
- Candidates :
  * get 'lost' in the mass of job offers and they are usely too restrictive in their jo research to very specifc areas with very limited job offers.
  * can get discouraged after a long job research period


## How is it used?

### Job seekers
They would register in the system:
- their resume/CV
- some keywords on the target jobs
- desired work area
- number of interview required per week

The way it works for candidates then is that the system through a matching system will rank the most relevant job offers. They then have 2 options :
  * Go through the job offers them self and ask "manually" for interviews in the system by selecting a time in the company's timetable ==> in that case it has to be approved by the company
  * Let the system plan interviews automatically based on their profil
Of course it can be a mix as explain earlier, the candiate can plan 1 or 2 interviews himself and let the system fill out the rest.

### Companies
They would register in the system : 
- their job offers
- maximum number of interview per week for each job offer
- timetable of available times for interviews

The companies would then just have to let the system plan interviews for them, they would only have to approve interviews asked directly by the candiates.


## Data sources and AI methods
The data would come from governmental job board / any private job boards + job seeker data.

AI methods used :
	- NPL for both job ad and resumes, to correctly confront job needs vs job seekers skills
	- matching neural network to make sure job seekers are matched with the most relevant job postions for them + companies are matched with most relevant job seekers for them
	- automatic interiew scheduler

## Challenges

The system only set up regular interview to keep the job seeker activ in it job research period, but it does not mean that the person doesn't to prepare itself and work on it's resume/interviews. Because in the end the system rely on the companies trust in the candidates that will be automatically assigned to them for interviews.
Of course it works also in the other way around and companies should treat automatic candidates as any other candidates.

## What next?

The system could be improved by including a historic of the whole recruitment process. That way we could analyse how far each candidates goes on each job offer and improve even further the matching neural network.

