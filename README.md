## Uploading an Unreal Project to GitHub 

These are step-by-step instructions for someone new to GitHub.
You don’t need to know coding — just follow the steps carefully once.

##What You’ll Need

Before starting:

Install GitHub Desktop → https://desktop.github.com/

Create a GitHub account (if you don’t have one already)

Make sure you’ve been invited as a collaborator to the project (you’ll get an email from GitHub)

Click the link in the email → click “Accept invitation”

Then you’ll see the repository page open on GitHub.

## Step 1: Open GitHub Desktop

Open GitHub Desktop (blue cat icon).

If prompted, sign in with your GitHub account.

## Step 2: Clone the Empty Repository

In GitHub Desktop, go to the top menu:
→ File → Clone Repository

Select the URL tab.

Paste the repository link (I’ll give you this link).
Example:

https://github.com/yourusername/yourprojectname.git


Choose where to save it (e.g. Documents/UnrealProjects/ProjectName).

Click Clone.

 #You now have a local copy of the GitHub repo (it’s empty right now).

## Step 3: Add Your Unreal Project

Open the folder you just cloned.
(GitHub Desktop will show a button like “Show in Explorer” — click it.)

Copy your entire Unreal project folder into that cloned folder.
Example folder structure:

Documents/
  UnrealProjects/
    MyUnrealRepo/         ← This is the cloned GitHub folder
      Content/
      Config/
      Source/
      MyUnrealProject.uproject

## Step 4: Upload the Files (Commit + Push)

Go back to GitHub Desktop — it will automatically detect all the new files.

At the bottom left, where it says “Summary (required)”, type:

Initial Unreal project upload


Click the blue button “Commit to main”.

Then at the top, click “Push origin” (arrow pointing up).

# This uploads the entire Unreal project to GitHub.
You’ll see all the files appear on the GitHub website after refreshing the page.

##Step 5: Check It Worked

Go back to the repository page on GitHub in your browser.

Refresh the page — you should now see folders like:

Config/
Content/
Source/


That means the upload was successful 

##Notes for Unreal Projects

If you see big folders like Saved/, Intermediate/, or Binaries/, don’t worry — these are automatically ignored by the .gitignore file.

In the future, only commit and push after saving your work in Unreal.

Always pull before starting work, and push after finishing.

 ##Common Mistakes to Avoid
Mistake	What Happens
Uploading a ZIP file	GitHub won’t track updates properly
Forgetting to push	Your changes stay only on your computer
Editing before pulling	Can cause merge conflicts
Deleting .gitignore	Project becomes huge and messy
### Summary
Step	What to Do	Tool
1	Install GitHub Desktop	GitHub website
2	Accept invite to repo	Email → GitHub
3	Clone repo	GitHub Desktop
4	Copy Unreal project into cloned folder	File Explorer
5	Commit & Push	GitHub Desktop




###Step-by-Step Workflow (Every Time You Work - ongoing if we ar weoking on more than one update)
## Before you start work

Open GitHub Desktop.

Click Fetch origin (top bar).

If it says updates are available, click Pull origin.
# This downloads the latest version of the project.

Then open the Unreal project (.uproject file) and start working.

##While you’re working

Save your files regularly in Unreal (Ctrl + S).

Don’t worry about GitHub until you’re finished for the day/session.

Avoid editing the same map or Blueprint at the same time as the other person.

## When you’re finished

Close Unreal (so no files are locked).

Open GitHub Desktop.

You’ll see all your changed files listed.

In the summary box, type a short message describing what you did.
Example:

Updated environment lighting and added new meshes


Click Commit to main (blue button).

Then click Push origin (top bar).
#Your updates are now uploaded for both of us.

# When the other person finishes

Before you open Unreal again, Pull origin to get their latest work.

Unreal will rebuild temporary data if needed (it’s normal).




##Rule	Why
Pull before you start	Ensures you’re up to date
Push when you finish	Shares your work
Don’t edit the same map simultaneously	Prevents overwrites
Close Unreal before pushing	Avoids locked files
Communicate if editing the same Blueprint	Prevents lost changes


