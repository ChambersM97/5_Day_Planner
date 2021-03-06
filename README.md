Github Link: https://github.com/ChambersM97/5_Day_Planner
Website Link:  https://chambersm97.github.io/5_Day_Planner/


# 05 Third-Party APIs: Work Day Scheduler

Create a simple calendar application that allows the user to save events for each hour of the day.
This app will run in the browser and
feature dynamically updated HTML and CSS powered by jQuery.

You'll need to use the [Moment.js](https://momentjs.com/) library to work with date and time.
Be sure to read the documentation carefully and concentrate on using Moment.js in the browser.

## User Story

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```
GIVEN I am using a daily planner to create a schedule

1. WHEN I open the planner
THEN the current day is displayed at the top of the calendar
DONE

2. WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
DONE



3. WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future

        1. have a common selector between your different time blocks
        DONE
        2. loop over each one using jQuery
        
        3. connect MomentJS to determine the current time
        4. compare current time to the individual timeblock 
        5. determine if time block is in past, present, or future
        6. change color according to past = grey, current = red, future = green




4. WHEN I click into a timeblock
THEN I can enter an event
DONE?

5. WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage

6. WHEN I refresh the page
THEN the saved events persist
```

The following animation demonstrates the application functionality:

![day planner demo](./Assets/05-third-party-apis-homework-demo.gif)

## Review

You are required to submit the following for review:

<!-- * The URL of the deployed application.  -->

<!-- * The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved. -->
