## Introduction

Now, you may be familiar with some of this stuff already, but to be thorough I'll go ahead and
assume little to no previous experience with the Unix command line.

What is the Unix command line? In short, it's a persistent but somewhat archaic user interface that grants access to text-based programs at the heart of modern Unix-based computers. (Both Macs and Linux desktops count as Unix-based.) These days, we use a terminal "emulator," not a real terminal, which replicates the same Unix environment of old within a modern application window.

On Macs, that emulator is the Terminal app. You can open it using your Finder---I think it's in the Utilities folder---or more rapidly using Spotlight (`Command` + `Space` on your keyboard).

## Step 1: Install `xcode`

If you've never use command line utilities before, the first step will be to
install
[xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12&ign-mpt=uo%3D4),
the collection of developer tools available from Apple.

To install xcode, copy `xcode-select --install` into Terminal and press Enter.


## Step 2: Install Package Manager (Homebrew)

Once you have xcode installed, you'll be well served to install a "package
manager," a program that will will itself allow you to download and install
other programs without much fuss. Since there is no standard Mac package
manager, you'll probably need [Homebrew](https://brew.sh/), the "Missing Package
Manager for macOS."

To install Homebrew, paste the following into the Terminal app and press Enter.

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## Step 3: Install git

You're reading this on Github. That works fine. But given that you'll ultimately
want to work with files within your own local filesystem, it makes sense to
transfer these instructions there.

Rather than download them in the standard way (by clicking a download link, for
example), copying and pasting their contents into new files, you'll use git to
clone them onto your machine. Git is a version control system that is useful if
not essential to writing in plain text formats like markdown and latex, and it's
also simply everywhere in development today and therefore useful to know.

(Unrelatedly, its creation is fascinating in its own right. Linus Torvalds,
frustrated with the version control software available to him as he was
developing Linux, decided to created his own. He started on April 3rd, 2005. The
project was released April 7th, just four days later. Beginning as something he
created for his own work, the program has gone on to facilitate the development
of almost every major software platform built within the last twenty years.
Facebook, Twitter, Google, Netflix, and LinkedIn are just some of the companies
and projects listed as Git users on [its website](https://git-scm.com/). There
are undoubtedly more.)

Now that you have Homebrew, installing git is as easy as running the following in Terminal:

`brew install git`

Once git is installed, you'll need to register your name and email. Copy the
following into the terminal, replacing "your name" with... you get the idea.

```
git config --global user.name "Your name"
```

Same with email:

```
git config --global user.email "Your email address"
```

Git should be ready to go.

## Step 4: Download this git repository

To get a copy of this file on your computer, you'll want to clone the whole
repository. A repository is a selection of files that git has been told to watch
for changes. In this case, that includes this file and a folder with a few
screenshots.

Since I created this Github repository, I can tell you what the link to clone
is: `https://github.com/wmhorne/Peter-Learns-Markdown.git`

It's worth knowing how to clone any Github repository, though.

Above and to the right of this or any Github README page (README being
effectively the "front page" of any Github project), you'll see a green button
that says "Clone or download." That button will reveal the same link I just
pasted above. (It's actually the same link you'll find in the browser's url bar,
too, for whatever that's worth.)


![Git clone](images/2020-03-22_14-11.png)

Copy that link. 


## Acquanit yourself with markdown

## Download pandoc

## Download Latex
