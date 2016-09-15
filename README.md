# Workflow 

## Whe a user signs up for Learn...


In July 2015 a new on-boarding flow was set up between flatironschool.com and learn.co. Below is what the new flow looks like for the students:

![New On Boarding ](https://s3.amazonaws.com/learn-experts/new-onboarding.png "New On Boarding")

The general workflow for all users joining Learn now looks like the following:

1. User signs up for Learn, first creating a GitHub account
2. Onboarding flow (available at: https://learn.co/ide) prompts user to download the Learn IDE
3. User clicks to download; is automatically served the correct binary for their operating system (OS X or Windows)
4. User launches the Learn IDE
5. User authenticates by entering their auth token available at: http://learn.co/ile/token
6. Once they've authenticated, they are ready to start solving labs using the Learn IDE

The workflow from this point forward is straightforward: to work on a lab, the user is expected to simply use the Open button on Learn. This will automatically:

1. Fork and clone the repo (to their workspace on the Learn IDE server)
2. Open their Learn IDE instance locally
3. Automatically `cd` them into the correct lab directory
4. Automatically open the file tree to that lab directory

At this point the user is ready to open files locally, write code (in the Atom text editor), run tests (using the `learn` command in the Terminal) and submit their work when complete using `learn submit`. This is the familiar Learn workflow.

## Reference links

**DO NOT give students the link learn.co/ide**

If a user has not used the IDE before, they must go through the welcome track to setup an account. To do this, they simply need to go to http://flatironschool.com and pick a free course. This will get them in the proper flow to download, install, and authenticate the Learn IDE.

If the student is already [authenticate](https://github.com/flatiron-labs/learn-support/blob/master/onboardin-flow.md#student-cannot-download-the-learn-ide), they can download the Learn IDE for their OS with one of these links:

OSX: http://learn.co/ide/osx_download

Windows: http://learn.co/ide/windows_download

Linux: http://learn.co/ide/linux_download

We now have a 'Learn IDE information and troubleshooting tips' section in our [help center!](https://learn.co/help-center)

## Provision an Account

Sometimes a students account is not properly set-up OR the student has been off-line for so long that they're Learn IDE account was wiped. When this happens, you can try to provision their account:

- Have student fully quit the Learn IDE (do not use the X, use the File->Exit or Atom->Quit)
- Go to: https://learn.co/ide/provision
- Enter a github name if they've already auth'ed OR an email address if they haven't
  - If the student is having the `learn-ide-user` issue, make sure to check the corresponding box
- **Wait 5 minutes**
- Have student try and open their Learn IDE again



<p class='util--hide'>View <a href='https://learn.co/lessons/learn-expert-learn-ide-workflow'>Learn Expert Learn IDE Workflow</a> on Learn.co and start learning to code for free.</p>
