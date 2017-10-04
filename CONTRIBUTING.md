# Getting started for developers

### Forums for interactions with other developers

* [gitter chat](https://gitter.im/mindfulness-at-the-computer/Lobby) - for real-time text chat
* Github - for code reviews and for commenting on issues.

## How to report bugs

TBD: Template for reporting bugs

## Decision process

* Overall design and architecture is determined by SunyataZero (Tord). In other words the project uses a so-called "benevolent dictatorship" structure. (Of course since this is free and open source software, anyone can - and are encouraged - to create a fork and create their own Mindfulness application which meets their needs❣)
* We want discussions about all decisions to be very open in the project and therefore, conversations that have started out as private can be made public without asking the participants (unless of course the conversation has been of a very personal nature)

People:
* Tord

Money:
* People contributing to the project are unpaid

## Contributor responsibility

No responsibility for any financial or other damage.

## How do I get an overview of the project?

* Read about the [tech architecture](tech-architecture.md) for the application
* Read the [advertisement for new people](misc/advertisement-for-devs.md)
* If things are unclear, please ask in the [gitter chat](https://gitter.im/mindfulness-at-the-computer/Lobby)

## What can I do right now?

* Doing code reviews
* Writing automated tests to increase code coverage
* This project is newbie-friendly and has [these issues](https://github.com/SunyataZero/mindfulness-at-the-computer/issues?q=is%3Aissue+is%3Aopen+label%3Afirst-timers-only) specifically for new people
* Check [the issue list](https://github.com/SunyataZero/mindfulness-at-the-computer/issues) to see if there are any issues marked with [help wanted](https://github.com/SunyataZero/mindfulness-at-the-computer/labels/help%20wanted)

## Pull Requests

1. Fork the repo (if you haven't already done so)
2. Clone it to your computer
3. When you're ready to work on an issue, be sure you're on the **master** branch. From there, [create a separate branch](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches) (e.g. issue_32)
4. Make your changes. If you're unsure of some details while you're making edits, you can discuss them on the ticket or in the [Gitter chat room](https://gitter.im/mindfulness-at-the-computer/Lobby).
5. Commit your changes
6. Push the working branch (e.g. issue_32) to your remote fork.
7. Make the pull request (on the [upstream **master** branch](https://github.com/SunyataZero/mindfulness-at-the-computer/tree/master))
    * Do not merge it with the master branch on your fork. That would result in multiple, or unrelated patches being included in a single PR.
8. If any further changes need to be made, comments will be made on the pull request.

It's possible to work on two or more different patches (and therefore multiple branches) at one time, but it's recommended that beginners only work on one patch at a time.

### Syncing ###
Periodically, you'll need the sync your repo with mine (the upstream). GitHub has instructions for doing this

1. [Configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)
    * For step 3 on that page, use https://github.com/SunyataZero/mindfulness-at-the-computer for the URL.
2. [Syncing a Fork](https://help.github.com/articles/syncing-a-fork/)
    * On that page, it shows how to merge the **master** branch (steps 4 & 5 of **Syncing a Fork**).

## Open conversation policy

Unless conversations are clearly of a private nature, we can choose to share them with other team members. The reason for this policy is so that it does not take too long to relay information to others (otherwise the person who wants to relay information would need to wait for an email response from the person she has been in conversation with).


***

### References
* Book "Producing open-source software"
  * http://producingoss.com/en/getting-started.html#developer-guidelines
  * http://producingoss.com/en/social-infrastructure.html
* [Advertisement for new people](misc/advertisement-for-devs.md)