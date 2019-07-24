# Echo App
An app that repeats what you say until you exit it!

## Requirements
- The app runs on the command line or.
- It's fine to use Ruby or JavaScript.
- When the app runs you are prompted with a phrase to say something
- The output also has information about the date and time formatted as below.
- The app continues to prompt you to say something until you type exit
- When you type exit the app outputs 'Goodbye!' and then ends.

## Example
```
$ ruby echo.rb
Say something:
hello, world
2018-01-09 | 16:26 | You said: 'hello, world'!
Say something:
exit
Goodbye!
```

## Flow
1. Start app in console
2. Prompt user for information
3. Take user information
4. Get current date & time, format, and repeat back what was said
5. Prompt user for more information
6. Exit program when user types "exit"
