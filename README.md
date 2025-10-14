This project is stored on GitHub so we can both work on the same Unreal Engine files.

You’ll need to use GitHub Desktop to upload (push) and download (pull) changes.

# What You Need

Before starting:

Install Unreal Engine 5.x (same version as this project).

Install GitHub Desktop: https://desktop.github.com/

Create a GitHub account (free).

I will invite you to the project as a collaborator — accept the invite via email.

 # Downloading the Project (Cloning)

Open GitHub Desktop.

Click File → Clone Repository.

Select the URL tab.

Paste this link:

https://github.com/yourusername/yourprojectname.git

Choose a local folder (e.g. Documents/UnrealProjects).

Click Clone.

Once it finishes, open that folder and double-click the .uproject file.

Unreal may ask to rebuild missing files — click Yes.

# Making Changes

Open the project in Unreal.

Make your updates (e.g. blueprints, maps, lighting).

Press Ctrl+S often to save.

When you’re finished working:

Close Unreal before pushing (so it doesn’t lock files).

 # Uploading Your Work (Push Changes)

Open GitHub Desktop.

It will automatically show your recent changes on the left side.

At the bottom left, type a short summary message — for example:

Updated environment lighting and added new props.

Click Commit to main (blue button).

Then click Push origin (top bar) to upload your changes to GitHub.

 # Getting the Latest Version (Pull Changes)

Before starting new work each day:

Open GitHub Desktop.

Click Fetch origin → if new updates exist, click Pull origin.

This downloads the latest version from GitHub.

Once the pull completes, open Unreal normally.

 # Resolving Simple Conflicts

If you both edit the same file (e.g. the same map) at once, Unreal may warn about conflicts.

Always Pull before starting work.

If Unreal says a file is newer, keep the newest version unless you know your edits are missing.

If unsure, tell the other collaborator before overwriting.

 # What NOT to Upload

These folders are automatically ignored (so don’t worry about them):

Saved/

Intermediate/

DerivedDataCache/

Binaries/

These are temporary and will be rebuilt automatically by Unreal.
