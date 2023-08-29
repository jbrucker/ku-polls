## Process

The application will be implemented in 4 iterations. Each iteration has a duration of one week. 

At the start of each iteration, the project pland and project requirements are reviewed and updated as necessary, and an iteration plan is created.  A task board and issues are used to record and track work and defects.

## Timeline

| Iteration | Features |
|:---------:|----------|
|     1     | Display a list of poll questions. |
|           | Each poll question is linked to a page that displays the question and a list of choices.|
|           | Visitor can choose a poll question and vote on it. His/her vote is counted toward the total.|
|           | Visitor can see the total votes for each choice on a poll question after voting.|
|           | Every poll has a publication date (start date) and is only visible on or after that date.|
|           | The poll questions and responses are saved in a database.|
|           | Polls can be added or changed using the admin interface. |
|     2     | A poll has an end date. No voting is allowed after the end date.|
|           | Question has methods for `is_published` and `can_vote` with unit tests.|
|           | Improved Navigation: from any page a visitor can return to the polls list screen or view the results without voting.|
|           | The polls index allows visitors to navigate directly to the poll results page.|
|           | Improve formatting of the poll detail page and poll results page. |
|           | If a visitor enters the URL of an unpublished poll, they are redirected to the polls list page.|
|           | Sensitive configuration data is separated from code.|
|           | Automatic running of unit tests. |
|           | Automatic code coverage to measure how well unit tests cover the code.|
|     3     | Add authentication in order to vote. A visitor must first authenticate (log in).|
|           | Unauthenticated visitors cannot vote. In this case, a poll's detail page has a link to login. |
|           | Each visitor is allowed only one vote per poll question. |
|           | A visitor can change his/her vote on a poll during the voting period, and his/her new vote replaces old vote. |
|           | If a user selects a poll he already voted for, the list of choices shows which choice he/she previously selected.|
|           | Add a link to “Login” or “Logout” to the polls index page. |
|     4     | Create data fixtures for initial users and polls data.|
|           | Write installation instructions for the application. |
|           | Add “How to Run” instructions that include using the virtual env.|
|           | Review and cleanup all code.|

### Milestones

| Iteration | Milestone |
|:---------:|-----------|
|     1     | Application displays a list of active polls and allows voting on each poll. |
|           | Application shows total "votes" for each choice in a poll. The results are persistent across restarts. |

## Technology and Tools

* Python programming language to implement the application.
* Django web framework.
* Github for source code repository, issue tracking, and automatic testing.
* Github Wiki for project documents.
* Github Project for backlog, task planning, and task boards iteration work management.
* `vim` for coding.
