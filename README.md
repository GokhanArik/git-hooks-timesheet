# git-hooks-timesheet
Post-commit git hook that puts the time worked on every commit to a file.

# Usage

Copy post-commit file and put in your project's .git/hooks/ folder.
Make sure it is executable. 

# Commit Message

It recognizes patterns in following formats:

"(StoryNumber).(TaskNumber) - (HoursWorked) Commmit message"
"(EpicNumber).(StoryNumber).(TaskNumber) - (HoursWorked) Commmit message"

For example,

If you worked on task 4.2 for 3 hours, your commit message would be:

"4.2-3 Screenshot bug fixed."

If you worked on task 4.2.3 for 2 hours, your commit message would be:

"4.2.3-2 Screenshot bug fixed."

After a successfull commit, a file named timesheet.txt will be created on your dekstop in following format:

Monday: 3.1 - 1 hours
Monday: 6.4 - 1 hours
Monday: 6.3 - 2 hours
Tuesday: 4.4 - 1 hours





