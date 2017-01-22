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

## `git init`
The command `git init` is used to set up a local repository.

In this section we will set up the game board that represents the local git repository. The game board consists of two sheets of paper - one representing the Repository, and the other representing the Staging Area and the Working Directory.

<table>
<tr><td>Repository<br>(hex paper)<br><br></td></tr>
<tr><td>Staging Area<br>
(blank paper)<br>
Working Directory</td></tr>
</table>

### The Repository
The Repository is represented by a sheet of hex paper (in landscape orientation) at the top of the game board. Label this sheet of paper "Repository".

### The Staging Area and The Working Directory
The Staging Area and the Working Directory is represented as a single sheet of blank paper (in landscape orientation). 

1. Draw a line across the middle of the sheet of paper from left to right.
2. Label the top half of this sheet of paper "Staging Area".
3. Label bottom half of this sheet of paper "Working Directory".

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
