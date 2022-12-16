## Overview

This is a technical writing and editing project as part of your interview.

This project is designed to take between 1 - 2 hours.
Please take the time to carefully review the [writing style guide](../styling-guide-snippet.md).

## Instructions

Create a new GitHub repository with the following content (See [content](#content)) as the first commit. Make a branch and open a PR to edit the text for clarity, and include any questions about the content's meaning, as if you were editing a colleague’s work. 

 **Any changes that you think will improve the text and explain the concepts better are welcome**. If anything in the text doesn’t match your opinion on a best practice, feel free to correct the meaning of the text. The result should be a document that you, as a technical writer, would be comfortable sharing with end-users.


Construct your PR to teach the author:
- Make atomic commits.
- Write your commit messages to show your rationale for edits.
- Please construct your commits, commit messages, and PR description as you would for an actual PR as if you were collaborating with a team.
- It is best to edit the files on your local machine and push with the `git` command or a desktop Git application rather than editing directly on the GitHub.com website.

Edit the text so that it is easy to read:
- Correct errors.
- Put the text in active voice and present tense.
- Address the reader as you, not we.
- Phrase statements as positive rather than negative.
- Make the language simple and plain. 
- Avoid euphemisms.
- Structure the text so it has a logical flow. 

Once you're finished with your edits, send the PR link to the HashiCorp recruiter.

**NOTE**: DO NOT FORK THE PROJECT. MAKE A COPY OF ALL FILES, CREATE YOUR OWN FRESH REPOSITORY AND SUBMIT A PULL REQUEST TOWARDS YOUR OWN PROJECT. DO NOT MERGE THE PULL REQUEST.

---

## Content

### What is the difference between push, pull, and fetch?
*** 

### `git push` - 
Git push sends the changes and commits made in your local branch to a remote repository on GitHub. This allows other collaborators to access your changes and pull or fetch them.  
<br> 

**KEEP IN MIND** : `Git push` will fail if the remote branch has diverged from your local branch. Before you execute Git push, you need to ensure that your local branch is synchronized with the most current version of the remote branch by using `git pull` OR `git fetch` AND git merge.
 

### `git pull` - 
This action does two things for you:  
1. Fetch changes/commits made to the remote repository.
2. Automatically merge these changes to your local copy.  

**KEEP IN MIND**: `Git pull` will automatically fetch and merge into your branch from the local repository. If you want to review any changes prior to merging, we recommend you execute `git fetch` instead.


### `git fetch` - 
This command adds the changes made in the remote repository to your local branch without committing them. Unlike `git pull`, `git fetch` allows you to review changes made to the remote repository without automatically merging them. `Git fetch` will not automatically add changes to your local branch.  
<br> 
> Still confused? Follow [this link](https://docs.github.com/en/get-started/quickstart/github-glossary) to the GitHub glossary for further definitions of common terms used in GitHub. 
