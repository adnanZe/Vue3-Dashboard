# Dashboard Vue 3

### The base project I use

- vue 3
- typescript
- vuetify

!!!Inspirations for ideas, User Stories, Description, Constraints: https://blog.bitsrc.io/15-app-ideas-to-build-and-level-up-your-coding-skills-28612c72a3b1 !!!

## #1 Countdown Timer

### Technologies:

- vue 3
- vuetify

### Description:

We all have important events we look forward to in life, birthdays, anniversaries, and holidays to name a few. Wouldn’t it be nice to have an app that counts down the months, days, hours, minutes, and seconds to an event? Countdown Timer is just that app!

The objective of Countdown Timer is to provide a continuously decrementing display of the he months, days, hours, minutes, and seconds to a user entered event.

### Constraints:

- Use only built-in language functions for your calculations rather than relying on a library or package like MomentJS. This assumes, of course, that the language of your choice has adequate date and time manipulation functions built in.
- You may not use any code generators such as the Counting Down To site. You should develop your own original implementation.

#### User Stories:

- Users can see an event input box containing an event name field, a date field, an optional time, and a ‘Start’ button.
- Users can define the event by entering its name, the date it is scheduled to take place, and an optional time of the event. If the time is omitted it is assumed to be at Midnight on the event date in the local time zone.
- Users can see a warning message if the event name is blank.
- Users can see a warning message if the event date or time is incorrectly entered.
- Users can see a warning message if the time until the event date and time that has been entered would overflow the precision of the countdown timer.
- Users can click on the ‘Start’ button to see the countdown timer start displaying the days, hours, minutes, and seconds until the event takes place.
- Users can see the elements in the countdown timer automatically decrement. For example, when the remaining seconds count reaches 0 the remaining minutes count will decrement by 1 and the seconds will start to countdown from 59. This progression must take place from seconds all the way up to the remaining days position in countdown display.
- User can save the event so that it persists across sessions
- User can see an alert when the event is reached
- User can specify more than one event.
- User can see a countdown timers for each event that has been defined.
