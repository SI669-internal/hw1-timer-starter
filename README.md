# HW 1: Countdown timer
## SI 669 Fall 2020

Create a webpage that features a 10 second countdown timer. The page should have one button that allows the user to start/restart the timer. Whenever the button is clicked, it should start a new countdown. If there was an active countdown, it should be cancelled. See the demo video (Links to an external site.) for an example of what your page should do when it’s complete.

You will use GitHub Classroom to create your copy of the starter repository. GH Classroom will make a repo for you that is your own private repo that only you and the course instructors can access. You MUST use this repo to push your solution to the homework. Be sure to push before the deadline to get full credit. Do NOT push after the deadline if you don’t intend to accept a late penalty. The last commit timestamp on your repo will be used to determine if your work is on time or late.

Notes:

The timer should only start when “Restart” is clicked the first time.
When “Restart” is clicked, it should restart the timer. You will have to figure out how to clear (or cancel) an active timer. You can find information about how to do this online.
If the timer gets all the way down to zero, the page should display “Timer Done!”
Note that the display changes each second. This means you will *not* be setting the timer to 10 seconds and letting it run. Consider: If the display changes every second, how often do events need to fire? How will you know when the timer is actually done?
Grading
25 pts: Clicking the button makes some sort of visible change on the page
25 pts: Clicking the button starts a timer that expires after 10 seconds and displays “Timer Done!” when it expires (may or may not change the display every second)
20 pts: Timer counts down every second (display changes every second)
20 pts: Timer is restarted when button is clicked and a timer is active (starts counting down from 10 seconds again)
10 pts: Restarting while a timer is active cancels the original timer. Only one timer can be active at any one time.

Extra credit (Up to 10 points):

Add the capability for the user to set the number of seconds to any integer. The UI needs to be clear enough that the grader can figure out how to do this. The number of points awarded will be based on the quality and elegance of the solution. A basic solution that works but maybe doesn’t cover all test cases or look all that nice will get around 5 points. You still need to meet all of the original assignment requirements as well, and it needs to be easy for the grader to assess that all original requirements were met. You can add brief, simple instructions as the README for your repo if you think it's needed for explaining how to run your solution.
