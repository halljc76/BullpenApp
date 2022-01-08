## Welcome to the Bullpen!

This application is the standalone version of what will be implemented into the
main application. 

Players using the Bullpen can sign-in to have the capability
to add notes to sessions, identifying performance goals or future aspirations.
The goal for this application is to be a place where players can qualitatively 
reflect on their game preparations.

### Features
- Strikezone Plot annotated with Velocity, Spin (*deprecated* for now)
- Summary Statistics 
- Velocity, Spin vs. Time Graphs
- Notes Display and Interactive Input
- Release Point Graphs (updated with clustering -- hoping to tweak this in the future!)
- Tilt Graphic for Pitch Types (to-come)
- Session-vs.-Session Comparison (to-come)

### Disclaimer
When booting the application up, it may seem to err at the start.
Give it a few seconds, and it *should* work.

If something DOES break, as it inevitably will, it may stem from a query to the DB.
(Truthfully, I could have done these queries much better. That's a task for "future me.")
Hopefully it isn't a file issue... we'll see how that goes.
**BUT**, Ctrl + F in the Script file the string "QUERY" (all caps), and it should take you
to each query, systematically.

### Related Files

This repo has the following files of importance:
- *Script.Rmd*: The code. (The comments should help make sense of it.)
- *TestData.csv*: The sample session. (Change this in the main chunk when implemented!)
- *Notes.csv*: The file that contains any notes made by players, coaches, or us. (Don't change the name. :) )
- *bullpen.sqlite*: The set-up version of the database. If this gets corrupted, just delete it and re-run!