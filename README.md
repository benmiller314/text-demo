# Introduction to GitHub using basic text files

## Where we're going
In this demo, we're going to...

1. Examine the layout and affordances of a GitHub repository
2. Edit a simple text file, and talk about commit messages
3. View the file's history and talk about diffs
4. Edit offline, syncing back and forth between cloud and local
5. Try again with a more complicated file and talk about what happens

For demonstration purposes, I'll lead the way –  though with your input. (In just a bit, I'd like you to practice on your own – but for that, you'll start with another repository. Wait for it. :)


## Where we are

A **repository**, often abbreviated to **repo**, is just a fancy way of saying a _folder_. It's a bunch of files. It can have subfolders inside it. You're looking at a repository right now! (See the files up above this text?)

This text is, itself, coming from a single file inside the repository, with the special name of **README.md**. Anything appearing in the README will show up here, on the repo's landing page.

The file extension, '.md', refers to _Markdown_, a simple syntax for signaling display formats (bold, italic, bullets, headings, etc) in plain text files. As you can see here, GitHub knows how to render markup like `**repo**` in bold and `_folder_` in italics. Follow the link in this sentence for an [overview of Markdown syntax](https://www.markdownguide.org/basic-syntax/) you can use.


## Let's look around

Initial questions to ask of any app:

- How is the space laid out?
- What's given the most prominent visual focus? Secondary focus?
- What features/tools do you have quick access to?

In other words: what functions or actions are _afforded_ by this interface? What does it seem to expect you to be looking for? What does it seem to expect you to do?



## What git does

Git pays attention to _changes in files_ saved within the repo. You can make any changes you'd like, and when you've reached a stopping point, you can **commit** those changes to the repo's history. Once you've done that, you can later travel back to any of those moments in the past. If the file type is simple enough (text or image), you can even see the before-and-after, which git calls **diffs**.

Each commit has a machine-meaningful **hash** associated with it – a long string of letters and numbers, derived from the contents of the files, so each one is essentially unique. But these hashes not very meaningful to humans! So every time you commit, you'll write a short **commit message** summarizing what's changed in that commit – or, perhaps, a reminder of what you want to do next.

It's a good practice to _make these commit messages meaningful_: "draft 12" isn't much more informative than "h6287c", though I suppose both are better than the default: "file changed." We can improve on that, I hope!

## Let's try it on the web first

The markdown syntax also lets you include links, including links to files in the repository. Here comes one now: let's read and  edit [this-is-just-to-say.txt](this-is-just-to-say.txt).


## Then let's open the repo locally, using  GitHub Desktop

To work directly on the GitHub website, you don't need anything but a web browser. But most of the time, you're going to want to work on your own device with a *local copy* of your project. Not only does this allow you to use software beyond simple text files, if the project calls for it; it also gives you a chance to assess and revise in your own space, before pushing something out into the world.

In git-speak, that local copy is called a **clone**: it links files between the **clo**ud and the **ne**ar. There are some good [instructions (including pictures) in the GitHub documentation](https://help.github.com/articles/cloning-a-repository) for how to make a clone. But probably the easiest way to is to work with an app like [GitHub Desktop](https://desktop.github.com/).

Let's try it!

Initial questions to ask of any app:

- How is the space laid out?
- What's given the most prominent visual focus? Secondary focus?
- What features/tools do you have quick access to?

In other words: what functions or actions are _afforded_ by this interface? What does it seem to expect you to be looking for? What does it seem to expect you to do?

Initial questions to ask of GitHub Desktop:
- Where are our files?
- How can we edit them?
- What happens in GitHub Desktop when we do?

### Multiple views of the same file

Let's open the repository in a text editor; I like [Pulsar](https://pulsar-edit.dev/), personally, but [Visual Studio Code](https://code.visualstudio.com/) is also good. And in fact, it might be nice to see the repo in both of these spaces, and to ask our questions of both at the same time:

- How is the space laid out?
- What's given the most prominent visual focus? Secondary focus?
- What features/tools do you have quick access to?

In other words: what functions or actions are _afforded_ by this interface? What does it seem to expect you to be looking for? What does it seem to expect you to do?

Let's go ahead and do it, then! :)

### Saving is not committing

But it is a necessary precursor. Git (and therefore GitHub Desktop) doesn't know about changes until those changes are saved.

Likewise, git _history_ doesn't know about changes until they're committed. And we can't _push_ until we've changed the file's history.

<!-- A good moral, there, or at least a mnemonic: if you want to change history, you've got to commit.  -->

### Back in GH Desktop, what's changed?

What affordances does the software now make more prominent?

## What goes for text goes for anything (step 5)

... more or less. That is, you can version-control any file, and see its history in terms of commit messages. But you can generally only see the diffs with "flat" or lo-fi files: text (though that includes xml, html, css, js, etc files that combine to produce hi-fi effects) and images (jpg, png). For now, GitHub can't show diffs for sound or video files.

And some files you might think of as simple text aren't as simple as they seem.

Let's see what happens if we modify [the .docx file that's also in the repo](This Is Just To Say.docx).


## Done!

Got all that? Now it's [time for you to try](https://github.com/benmiller314/dsam-gh-practice)!
