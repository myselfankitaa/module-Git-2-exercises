# Exercise: making changes to make to the `tiny-web-page`

_The purpose of this exercise is to make lots of changes at once
in a very uncoordinated way, to see how it can go wrong. Then
we can talk about what happened, how to fix it, and how to avoid it
in the first place._

Start by making a fork of https://github.com/HackYourFuture-CPH/module-Git-2-exercises into your own account. Then, clone that fork
(from your account) to your laptop.

Open `tiny-web-page/index.html` in your browser, to see how the web page looks at the moment.

## The story

The page looks great, but the team has been asked to make some changes to make it even better!

Here are the 10 changes:

1. The background should be more blue. Let's change it to `rgb(30, 30, 55)`.
2. The background logo should be more transparent. Please set it to `opacity: 0.06`.
3. Please change the words "consisting of" to "made up of".
4. Change the first list to an *un*ordered list (`<ul>`).
5. Please reword "just 3 files" to "just three files".
6. Please change the background colour to green.
7. Add a CSS rule to indent the two lists, using `padding-left: 3em`.
8. Instead of calling it "tiny web page", let's instead say "small web page" (only in `index.html`; don't worry about the directory / repository names).
9. Wrap everything inside the body inside a `<div>`. Make sure to indent the file nicely.
10. Please fix the spelling mistake: "in the first plaice" should say "in the first place".

## What to do

For each of the 10 changes separately:

1. Start on `main`.
2. Create a new branch to represent this specific change.
3. Make the edits required (inside the `tiny-web-page` directory)
   and commit.
4. Push your branch (to your fork).
5. Make a pull request from your new branch, **making sure that
   the "base" is set to `HackYourFuture-CPH/module-Git-2-exercises` `main`**. (The "base" of a pull request means "where you would like it to merged into").

Prepare the pull requests, but don't merge them yet.

By the end of this, we should have 10 open pull requests
in https://github.com/HackYourFuture-CPH/module-Git-2-exercises/pulls, each one representing one of the tasks.
