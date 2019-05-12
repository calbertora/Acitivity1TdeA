# Activity1TdeA
First Activity
# NodeJSContinuosEducation
## Assignments from the UVDA NodeJS course

The first assignment of the week is:
   - Show a list of courses
   - Select a course id, and with argv params, set the student's name and id, and it has to save the data on a file.
      - If no args are passed it has to print all the courses.
      - if the course id does not exists, it has to show a message to say so.

Clone the project using the commands:
```
git init
git clone https://github.com/calbertora/Activity1TdeA.git
cd Activity1TdeA
```

Install dependencies:
  ```
  npm install
  ```

To test the first activity:
   - on the node cli write the command:
      ```
      node index
      ```

To test the second activity:
   - on the node cli write the command:
      ```
      node index inscribir -i=1 -n='Mike Tyson' -c=12345
      ```
      - It must create a file with the data.
      - If the id does not exists, then a message wil show

