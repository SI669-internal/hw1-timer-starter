# HW 1: Countdown timer
**SI 669 Fall 2020**

## Video Walkthrough

See the [Demo Video](https://www.loom.com/share/5542240ba94842e19fcf351a045da0f7). 

## Learning Goal
Practice working with asynchrony in JavaScript (and, more specifically, timers) by creating a simple browser-based countdown timer.

## Project Goal
Create a webpage that features a 10 second countdown timer. The page should have one button that allows the user to start/restart the timer. Whenever the button is clicked, it should start a new countdown. If there was an active countdown, it should be cancelled. See the demo video (Links to an external site.) for an example of what your page should do when it’s complete.

## What to Do
1. Accept the GitHub Classroom invitation. (You already did this!)
2. Clone this repo to your local machine.
3. `cd` into the directory that was created when you cloned the repo (it should be called `hw2-hello-<your-github-id>`).
4. Modify `hw1.html` to meet the criteria below. 
5. You only need to push one version of `hw1.html`, even if you do the extra credit. The requirements for the main assignment should still work if you do the extra credit when the timer is set to 10 seconds.
6. Push your final changes to GitHub before the deadline.
7. Create a screencast video and submit the link to Canvas before the deadline.
8. Indicate in your Canvas comments which requirements (including extra credit) you believe you met.

## Notes:
* The timer should only start when “Restart” is clicked the first time.
* When “Restart” is clicked, it should restart the timer. You will have to figure out how to clear (or cancel) an active timer. You can find information about how to do this online.
* If the timer gets all the way down to zero, the page should display “Timer Done!”
* Note that the display changes each second. This means you will *not* be setting the timer to 10 seconds and letting it run. Consider: If the display changes every second, how often do events need to fire? How will you know when the timer is actually done?

## Grading (up to 120 points)
| Requirement  | Points |
| ------------- | ------------- |
| Clicking the button makes some sort of visible change on the page | 30  |
| Clicking the button starts a timer that expires after 10 seconds and displays “Timer Done!” when it expires (may or may not change the display every second) | 30 |
| Timer counts down every second (i.e, display changes every second) | 30 |
| Timer is restarted when button is clicked and a timer is active (starts counting down from 10 seconds again) | 20 |
| Restarting while a timer is active cancels the original timer. Only one timer is active at any one time. | 10 |
| **Total** | **120**


## Extra credit (Up to 4 points):
Add the capability for the user to set the number of seconds to any integer. Refer to the video walkthrough for an example.

| Requirement  | Points |
| ------------- | ------------- |
| UI for setting the countdown timer value is clear | 1  |
| When the timer value is changed and the timer is restarted, the timer starts at the correct value | 1 |
| Timer restarts and expiration continue to work properly as in the main part of the assignment | 2 |
| **Total** | **4**


