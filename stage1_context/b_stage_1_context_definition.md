[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| Habitica    | Mobile app/web app that turns productivity and habit tracking into a roleplaying game. Users create their own characaters, earn XP for completing tasks, and lose health for failing habits. It also features social elements like parties, guilds and challenges to keep users engaged.      | [Habitica official website](https://habitica.com) |
|            |                                             |                                     |


## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method

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
| Application aesthetics | 1            | 1        | 1        | Implement a minimal, intuitive design with more appealing colors and "game" art |
| Creating an item with a very high price causes the app to crash   | 1            | 2        | 2        | Perhaps a good way to tackle the problem would be to create an upper boundary on the price to stop the app from crashing + adding an apropriate error message                    |
| Always refresh the Party chat             | 2             | 3         | 3         | The chat server should be constantly listening for new messages and update the UI automatically without the need to refresh the page                       |
| You can only create challenges with other users, not tasks.          | 3             | 4         | 3         |  Implement this feature                                            |
| Not at all intuitive (we have to select a filter to see the completed tasks)           | 4             | 4         | 4         | Perhaps making the completed tasks appear at the end of the list (with the not competed tasks above them) would be a more intuitive way for the user to aknowledge completed tasks                 |



---
### - Cognitive Walkthrough

#### Method
To conduct our Cognitive Walkthrough we took the following approach:
1. Identify the tasks nuclear to the system - As a group, we determined which tasks were essencial for the system's purpose, focusing on those users would perform most frequently or that were critical to their sucess.
2. Break the tasks identified into executable steps: For each identified task, we documented the individual steps a user must take to complete it.
3. Evaluate each step using 2 key questions - We assessed each action by asking:
	* "Will the user know what to do at this step?"
	* "If the user does the right thing, will they know that they did the right thing and are making progress towards their goal?"
4. Document all findings in a structured format - We recorded all observations in a table, making note of the answers to the above questions.

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
| 1      | Go to the to-dos or dailies tab   | Yes                                        | This step is quite intuitive for new users       | Yes                                                                                 |  By going to the correct tab the user will see a proper space to create a new task     | Yes                       | -------------             |     |
| 2      | Click on the +   | Yes                                         | This step is quite intuitive for new users       | Yes                                                                                  | By executing this action a pop up to create a new task will be shown       | Yes                       |-------------             |     |               |     |
| 3      | Fill in the fields   | Yes                                         | This step is quite intuitive for new users       | Yes                                                                                  | When this step is executed there is no direct feedback that the goal of creating a new task is closer to being met. However it is still intuitive that we are getting closer to the end objective.        | Yes                       | Making the "create task" button active only when all fields have been filled             |     |              |     |
| 4    | Click create        | Yes                                         | This step is quite intuitive for new users      | Yes                                                                                  | -------------| Yes                       | -------------             |     |               |     |
|




Task: Complete a task

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Go to to-dos tab   | Yes                                        | This step is quite intuitive for new users       | Yes                                                                                 |   By going to the correct tab the user will see a proper space where all their tasks will be listed    | Yes                       |       -------------|        |     |
| 2      | Click on the dot next to the previously created task   | Yes                                         |   This step is quite intuitive for new users    | No                                                                                 |By completing this step the task will simply disappear if the filter to show the completed tasks is not active. For this reason new users will not be able to confirm if the task has been perceived as completed in the application, just disappeard or simply was deleted.       | Yes                       | Make the completed tasks appear at the end of the list with a diffent color or with lower opacity values.              |     |
| 


Task: Create task with other users - MATHILDIS MUDA ISTO PLS

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Go to Teams tab   | [IDK]                                        | The teams tab is not clearly identified in the mobile app (it appears as 3 lines - like a menu icon)       | [IDK]                                                                              |By clicking on this icon the user will be brought to the menu page which has a lot of non-relationed information to the task they are trying to complete. This makes it harder for new users to understand if they are in the correct place.        | Yes                       | Implement a separate tab for social matters.              |     |
| 2      | Create or join a team   | No                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | Click Create Challenge   | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 4    | Fill in the requested        | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |
| 5    | Click Add Challenge Task        | Yes                                         |       | Yes                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |
|


## B.1c. Overall Analysis

### Competitor analysis summary
#### Main findings
* **Gamification is highly engaging** - Habitica effectively motivates users with XP, leaderboards, and rewards, making study and task management more fun.
* **Social & collaborative features enhance engagement** – The ability to form "Parties" is a strong point that fosters collaboration.
* **Task creation is flexible but can feel overwhelming** – Some users find Habitica’s customization options too complex initially.
* **Feedback mechanisms (XP, streaks) drive consistency** – Users appreciate clear progress indicators.

### How this informs our design
* **Keep gamification but simplify the UI** for easier onboarding.
* **Ensuring academic incentives** (not just XP, but meaningful study rewards)
* **Offering strong colaboration tools** (study groups, shared challenges) whilst addressing privacy matters.

### HCI SWOT analysis

| **SWOT Element** | **HCI Focus**  | **Example in UX/UI**  |
|-----------------|---------------|-----------------------|
| **Strengths**   | **Gamification** | After completing a task, a certain amount of XP is given towards the user's avatar experience. |
|                 |               | Coins are accumulated by completing tasks, which we can spend on items to place on our avatar. |
|                 |               | The task creation part works fine (that's the main purpose of the app). |
|                 |               | The system works well, as if it were a game. |
| **Weaknesses**  | **Information**  | At first, when we create an account and enter the app, many pop-ups appear with a lot of information, and the app is still very confusing to use. |
|                 | **Intuitiveness** | In the tasks section, after creating and completing one, we have to open a tab and select a filter to see the tasks we have already completed. |
|                 | **Organization**  | The app itself is too disorganized. At the bottom, there are many tabs, some of which don't even make sense for the purpose of the application. |
| **Opportunities** | **Platform for teachers** | Create an interface for teachers, where they can create classes and add students. Within these classes, add tasks that students have to complete. |
| **Threats**     | **Task sharing** | In the competing app, it’s possible to create a channel and tasks with other users. |

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
