# A02 Tutorial

This tutorial explains how to set up **Git**, WebStorm, and **GitHub** on Windows and use them together. [2][6]

## Part 1: Directions on Using WebStorm

### Step 1: Create an account

1. Go to https://github.com/signup [1].
2. Enter your email, a password, and a username, then verify your email.

### Step 2: Install the version control software

1. Download the Windows installer from https://git-scm.com/downloads [2].
2. Run it and click Next through the screens to accept the defaults, then click Install.

### Step 3: Set your identity

Open **Git** Bash and enter these two lines with your own name and email:

```
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

### Step 4: Install WebStorm

1. Download the Windows .exe installer from https://www.jetbrains.com/webstorm/download [3].
2. Run it, tick "Create Desktop Shortcut", and click Next, then Install.
3. Students can get a free license at https://www.jetbrains.com/community/education/ [4].

### Step 5: Connect WebStorm to your account

1. In WebStorm, open Settings, then Version Control, then **GitHub**.
2. Click +, log in through the browser, and click "Authorize JetBrains". [5]

### Step 6: Create the online storage folder

A **repository** is a project folder that **Git** tracks.

1. Go to https://github.com/new [1].
2. Name the **repository** `A02` (capital A), set it to Public, and tick "Add a README file".
3. Click Create.

### Step 7: Make a local copy

To **clone** is to download a full copy of the online **repository** to your computer.

1. On the WebStorm welcome screen, click **Clone** **Repository**.
2. Paste `https://github.com/ybv2-yash/A02` and click **Clone**. Click Trust Project if asked. [5]

### Step 8: Save your changes as a snapshot

A saved snapshot is called a **commit**, and it needs a clear message.

1. Edit `README.md` and press Ctrl+S.
2. Open the **Commit** window (Alt+0), tick the file, and type a message such as `Feature: added workflow for using github`.
3. Click **Commit**. [5]

### Step 9: Upload your snapshots

To **push** is to send your saved snapshots to the online **repository**.

1. Open the **Git** menu and choose **Push** (Ctrl+Shift+K).
2. Click **Push**, then refresh your page on the website to confirm the change is there. [5]

### Step 10: Download changes

1. Use the **Git** menu and choose **Fetch** to check for new changes without changing your files.
2. Choose **Pull** to download the changes and bring them into your files. [5]

### Step 11: Work on a separate line of work

1. Click the **branch** name (`main`) in the bottom right and choose New **Branch**.
2. Make your changes, then switch back to `main`, open the **Git** menu, and choose **Merge** to bring the new **branch** in. This is called a **merge**.
3. If two versions changed the same lines, you get a **merge conflict**. Click **Merge** in the Conflicts window, choose the lines to keep, click Apply, and make a new **commit**. [5]

## Part 2: Glossary

- **Branch** - A separate line of development inside a **repository** that lets you try changes without affecting the main version. [2]
- **Clone** - To download a complete copy of a **remote** **repository** to your own computer. [2]
- **Commit** - A saved snapshot of your changes in the **repository**, stored with a short message describing the change. [2]
- **Fetch** - Downloading new information from a **remote** **repository** without changing your working files. [2]
- **GIT** - A free version control system that tracks changes to files over time and lets many people work on the same project. [2]
- **Github** - A website that hosts **Git** projects online so people can store, share, and work together on them. [6]
- **Merge** - Combining the changes from one **branch** into another. [2]
- **Merge Conflict** - A problem that happens when two versions of a file changed the same lines, so **Git** cannot decide which to keep and asks the user to choose. [2]
- **Push** - Uploading your saved snapshots from your computer to a **remote** **repository**. [2]
- **Pull** - Downloading changes from a **remote** **repository** and then combining them into your files. It is a **fetch** followed by a **merge**. [2]
- **Remote** - A version of your **repository** stored somewhere else, such as on **Github**. [2]
- **Repository** - A project folder that **Git** tracks. It holds your files and the full history of every change. [2]

## References

[1] **GitHub**. (n.d.). Sign up and create a new **repository**. https://github.com/signup and https://github.com/new

[2] **Git**. (n.d.). **Git** downloads and Pro **Git** book. https://git-scm.com/downloads and https://git-scm.com/book/en/v2

[3] JetBrains. (n.d.). Download WebStorm. https://www.jetbrains.com/webstorm/download

[4] JetBrains. (n.d.). Free educational licenses. https://www.jetbrains.com/community/education/

[5] JetBrains. (n.d.). WebStorm help: **Git** integration. https://www.jetbrains.com/help/webstorm/using-git-integration.html

[6] **GitHub** Docs. (n.d.). Hello World. https://docs.github.com/en/get-started/start-your-journey/hello-world