# Twine GitHub collaborative story template 🌈

 An attempt at making a template repo for collaborative ——synchronous or
 not—— writing on Twine. Aim is get this working for people who don't
 know about Git and GitHub as well as those who do. 
 
 Usage is not limited to GitHub, but can also make use of the Twine --as
 well as other-- editors or working
 suites such as Google's.

 ## Welcome 💫

 Here are different ways to make this work. Will keep suggesting and
 refining as we go... 

# Different ways to work

 ## Asynchronously 📖

 Here's one way this could work. This collaboration mode is closer to
 sharing a story on paper or in a written document back and forth. This
 may or may not involve using Git or GitHub.

1 - Someone in a team starts, then exports an HTML story from a Twine editor and
uploads it to a shared folder in a cloud suite such as Google Drive. 

2 - When a team member wants to work on the document, they "borrow it"
by first downloading a local copy, then changing the cloud copy's title (to something descriptive like adding : "On loan
to Sarah", or "At Sarah's", or "In Sarah's hands," --whatever makes sense
for all).

3 - When the team member is done working on the file on their Twine --or other--
editor, they re-export it and upload to Google Drive or (some such) and change back the title to
what it was.

4 - To keep count of who changed what, the story can include a commented
"version history" section in a designated passage. Not sure if Google doc's history versioning might work for HTML
documents as
well, but if it does, it might be pretty hard to read such an HTML document.

5 - When the story is finished, it can be exported and published online
(on Github Pages, [Netlify](https://netlify.com), [Neocities](https://neocities.org), or [Vercel](https://vercel.com), for instance).

## Synchronously

### The simplest way I see for now

Tutorials and forum posts have already been written on this such as :

- [Using GitHub to Collaborate on
  Twine](https://github.com/dashn98/twine--shore-leave/blob/master/how-to/twine-and-collaboration.md#using-github-to-collaborate-on-twine),
  by [Nicole Dash](https://github.com/dashn98);
- [Collaborating on Twine thread on
  Reddit](https://www.reddit.com/r/twinegames/comments/mqbw4g/collaborating_in_twine/);
- [Teamwork with
  twine](https://intfiction.org/t/teamwork-with-twine/54658/2) on [intfiction](https://intfiction.org/);

### A less simple way

This will involve writing a small tutorial to explain the basics of Twee 3
notation and how the Tweego compiler works (a kind of markup that Twine uses to compile to HTML files) in
an environment outside of the familiar Twine editor, as well as basic
knowledge of Git and Github.

Twee 3 files (with `.twee` or `.tw` extensions) can be modified and committed in a fork of this repo used as a
template. They can be modified in the GitHub repo interface itself
——perhaps directly, or copied and pasted from elsewhere, for instance a
common Google Doc—— and committed. If using this repo as a template, the
story will be compiled to html and published automatically via a GitHub
action. To do this, however, the GiHub Pages must be configured in the
repo. Follow [Emilia Lazer-Walker's great tutorial](https://dev.to/lazerwalker/a-modern-developer-s-workflow-for-twine-4imp) for more guidance on this.

### An even less simple way

Another way to go could be for team members with more advanced knowledge
of Git and Github to fork the repo and work
locally on their own code editors, then submit a pull request when
they're done. This would allow working with their editor of choice,
whether Twine or not.

People doing this should preferably have prior
knowledge of how to use code editors such as Visual Studio Code as well
as command line tools. If not,
they need motivation, focus, a high tolerance of discomfort and frustration,
and time to learn.