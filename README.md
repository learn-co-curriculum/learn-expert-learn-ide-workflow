# Workflow

## When a user signs up for Learn...

In July 2016 a new on-boarding flow was set up between flatironschool.com and learn.co. Below is what the new flow looks like for the students:

![New On Boarding ](https://s3.amazonaws.com/learn-experts/new-onboarding.png "New On Boarding")

This may look really confusing and you don't have to memorize it, but it's a good resource to have. We find that students sometimes get stuck on-boarding and setting up the Learn IDE, so it's important to know where they should be with setup based on what lesson they're on.

The general workflow for all users joining Learn now looks like the following:

1. User signs up for a course on flatironschool.com with an email address and is forwarded to Learn.
2. On-boarding flow prompts user to download the Learn IDE at the last lesson of the Welcome to Learn track.
3. User clicks to download and is prompted to create a password to go with their email account.
4. User is automatically served the correct binary for their operating system (OS X, Windows, Linux)
5. User installs and launches the Learn IDE
6. User logs into the Learn IDE via the prompt with their email and password (they haven't connected their github yet)
7. Once they've authenticated, they solve their first 'lab' in the welcome track. (This is not a real lab because you cannot make a real PR without a github account)
8. The student leaves the Welcome track and goes to some other track of their choice (free, certificate...)
9. At the first lab on this _non-Welcome track_, the student connects/creates their github account and they now have it linked to Learn and the IDE.

The workflow from this point on is straightforward: to work on a lab, the user is expected to simply use the Open button on Learn. This will automatically:

1. Fork and clone the repo (to their workspace on the Learn IDE server)
2. Open their Learn IDE instance locally
3. Automatically `cd` them into the correct lab directory
4. Automatically open the file tree to that lab directory

At this point the user is ready to open files locally, write code (in the Atom text editor), run tests (using the `learn` command in the Terminal) and submit their work when complete using `learn submit`. This is the familiar Learn workflow.

## Reference links

- [Onboarding Flow in Reference Guide](https://github.com/flatiron-labs/learn-support/blob/master/onboardin-flow.md)
