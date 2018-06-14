# Conditionals And Optionals

This project will help you practice the skills and concepts you learned related to logical comparison operators, Boolean operators, and Optionals in Swift. 

Unlike the previous two projects, this project is all done in playgrounds. Follow the instructions below:

### Download the Playground

1. Download the playground for this project by clicking [here](https://github.com/LambdaSchool/ConditionalsAndOptionals/archive/master.zip). 
2. Unzip the downloaded file.
3. Open the included ConditionalsAndOptionals.playground file using Xcode

### Do the Excercises

This project consists of multiple pages. You can see all the pages by choosing View->Navigators->Show Navigators in the View menu in Xcode.

1. Complete all the excercises on the first page.
2. Go to the next page by clicking the "Next" link at the bottom of the playground, or by selecting it in the files navigator on the left side.
3. Repeat until you've completed all pages in the playground.

### Bonus

If you finish and want another challenge try the following:

1. Open your Flashlight project from day 1.
2. Modify the project so that when the "Turn Flashlight On" button is clicked, the screen turns bright if the current time is between the hours of 8 AM and 10 PM. If the the current time is between the hours of 10 PM and 8 AM (night time), make the screen gray instead.

Hint: You can get the current hour (in 24-hour time) using the following snippet of code. Note that `hour` here is an `Int?`.

```
let calendar = Calendar(identifier: .gregorian)
let currentDate = Date()
let hour = calendar.dateComponents([.hour], from: currentDate).hour
```

> This code includes syntax and concepts we haven't covered yet. It's OK for you to copy and paste it to use it now. You'll learn enough to understand it later.

### Submit

Zip up the ConditionalsAndOptionals.playground file after you've finished all the excercises. Submit the zipped playground file to your project manager (PM).
