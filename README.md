# Postman
Input data
Product link: https://radio-shop.megaplan.by/
Link to API documentation: https://radio-shop.megaplan.by/api/v3/docs

Employee 1: Exploratory1@1.1 / Exploratory1@1.1

Employee 2: Exploratory2@1.1 / Exploratory2@1.1

What should be done:
Automate via API the following script

1. Log in as employee 1.
Add test for: response code

2. Create a task. Responsible for the task: Employee 2.
Add tests for: response code, task name, task owner, task status

3. Write a description of the task. Any text
Add tests for: response code, task description

4. Log in as Employee 2.
Add tests for: response code

5. Accept the task set by Employee 1.
Add tests for: response code, task status

6. Complete the assigned task.
Add tests for: response code, task status

7. Write a comment on the task. Any text
Add tests for: response code, comment

8. Log in as Employee 1
Add test for: response code

9. Accept the task
Add tests for: response code, task status

10. Delete task
Add tests for: response code, presence of text in response code

Result: Export the collection and send it as a .json file

Hints:
1. The necessary Ids of employees can be peeped on the UI
2. The Tasks module uses API methods. Therefore, you have 2 options to get the necessary methods: follow the documentation or pull them out of the console, Network tab. The second option is much easier in my opinion.

Acceptance Criteria:
The collection runs, executes the entire script, all specified tests are implemented
