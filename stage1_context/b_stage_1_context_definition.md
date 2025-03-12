[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| Habitica    | Mobile app/web app of study gamification        | [[Competitor Analysis AmazonShoes]] |
|            |                                             |                                     |


## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]

For the heuristic evaluation, 3 experts were considered. We started by installing the mobile app of our competitor, Habitica, and using it to understand its strengths and weaknesses. Then we created a table with our competitor's defects and used a scale from 0 to 4 to rate it, where 0 is "I don´t agree that this is a usability problem at all" and 4 is "Usability catastrophe". We also use Nielsen's heuristics. 


#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Catarina** | Marta | Matilde | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Application aesthetics | 1            | 1        | 1        | Something could be done to the button to... |
| Creating an item with a very high price causes the app to crash   | 1            | 2        | 2        | Instead of the app crashing, the price button wouldn't let you pass an x ​​number                    |
| Always refresh the Party chat             | 2             | 3         | 3         | nao sei, ver isto!!!!                     |
| You can't create joint tasks with other users, only challenges            | 3             | 4         | 3         |  Implement joint tasks instead of just challenges                                            |
| Not at all intuitive (we have to select a filter to see the things done)             | 4             | 4         | 4         | nao sei, ver isto!!!!                 |



---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Create a task** | Go to the to-dos or dailies tab     |
|                             | Click on the +  |
|                             | Fill in the fields      |
|                             | Click create           |
|                                          


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **2. Complete a task** | Go to to-dos tab |
|                               | Click on the dot next to the previously created task             |
|                                                         


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **3. Create task with other users** | Go to Teams tab |
|                               | Create or join a team            |
|                               | Click Create Challenge             |
|                               | Fill in the requested fields       | 
|           |         Click Add Challenge Task |
|                              



#### Results

Task: Create a task

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Go to the to-dos or dailies tab   | Yes                                        |       | Yes                                                                                 |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | Click on the +   | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | Fill in the fields   | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 4    | Click create        | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |
|




Task: Complete a task

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Go to to-dos tab   | Yes                                        |       | Yes                                                                                 |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | Click on the dot next to the previously created task   | Yes                                         |       | No                                                                                 |       | [Yes/No]                       | [Suggestion 2]              |     |
| 


Task: Create task with other users

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Go to Teams tab   | Yes                                        |       | Yes                                                                                 |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | Create or join a team   | No                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | Click Create Challenge   | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 4    | Fill in the requested        | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |
| 5    | Click Add Challenge Task        | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |
|


## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                                 |                              |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
