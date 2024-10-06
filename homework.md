# Homework

This is a repeat of [Exercise 1](exercise-1.md), but with a few changes.

It's bit unusual compared to the other homework you've done, because here you'll be _merging_ the pull requests, instead of _showing the unmerged_ pull requests to a mentor.

---

# Homework: making changes to make to the `tiny-web-page`

## Fork and clone

Start by making a _new_ fork of https://github.com/HackYourFuture-CPH/module-Git-2-exercises into your own account, giving it a new name (for example, `hyf-git-2-homework`).

Then, clone that fork (from your account) to your laptop.

Open `tiny-web-page/index.html` in your browser, to see how the web page looks at the moment.

## Prepare the pull requests

For each of the 10 changes separately:

1. Start on `main`.
2. Create a new branch to represent this specific change.
3. Make the edits required (inside the `tiny-web-page` directory)
   and commit.
4. Push your branch (to your fork).
5. Make a pull request from your new branch, making sure that
   the "base" is set to `main` **of your fork**. (The "base" of a pull request means "where you would like it to merged into").

Prepare the pull requests, but don't merge them yet.

## Merge the pull requests

Go through the 10 pull requests in order. For each one, if it's mergeable, then just merge it.

But, if it's _not_ mergeable (i.e. if the pull request says "This branch has conflicts that must be resolved"):

1. Resolve the merge conflict. You can do this from the GitHub web page, or from the command line, or probably from your IDE (e.g. Visual Studio Code). The pull request web page shows help on how to do this.
2. Add a comment to the pull request explaining:
3. Why the conflict happened (which things conflicted?)
4. How you chose how to resolve the conflict. i.e. why did you choose to keep "A", or keep "B", or combine the two?
5. Once the conflict is resolved, merge the pull request.

At the end of the homework, you should have 10 closed pull requests in your fork. Instead of submitting a pull request into the team channel for review, just submit a link to your forked repository.

## Note to mentors when reviewing homework

This one is somewhat inevitably messy :-/

What we can look for:

- Do each of the 10 branches (pre merge) look OK?
- Do each of the conflict resolutions look OK? (Especially, no committed `<<<<<<>>>>>>`)
- Do the PRs have helpful titles / branch names?
- Do the PR comments (explaining the resolved conflicts) seem right?
- Does the final web page (on `main`) look OK, and like it contains
  all / as-many-as-possible of the 10 changes?
