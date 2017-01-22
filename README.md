# Git: The Board Game

The goal is to create a board game for teaching git.

## Requirements

- Must accurately model git
- Must use readily available materials
- Must be usable by students in a classroom

## Equipment

- Hex paper
  - Scale 1/2 inch spacing, letter sized (12 longways)
    - [Downloadable version](https://www.printablepaper.net/preview/hexagon-portrait-letter-2)
- Sticky notes
  - Scale: the small skinny ones (TODO: link)
  - Writable (i.e., not the glossy ones)

## `git add`

Use to add changes in working copy to stage.

Move any number of change tokens from working directory to the staging area.

## `git commit`

Use to commit staged changes to the local repository.

Remove all of the change tokens in the staging area, and then...

- If this is the first commit
  1. Write any number in any hex cell. This is your commit node.
  2. Write "master" on a sticky note and attach it to the new commit node.
  This is the master branch.
  3. Write "HEAD" on a sticky note and attach it to the master branch.
- If this is not the first commit
  1. Write any unused number in any unused hex cell adjacent to the HEAD cell.
  This is the new commit.
  2. Move to the new commit the branch to which HEAD is attached. If HEAD is not
  attached to a branch, move HEAD to the new commit.
