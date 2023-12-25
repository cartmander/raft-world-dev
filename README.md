# Raft Kru Kru World Development


## Objectives
- To allow contributors to "host" the latest changes of a Raft world. 
- Instead of waiting for the original creator to launch the world, you can just get the latest saved files of a world from this repository and paste in your local World directory.
- Doing that will allow any contributors to fetch the latest changes of a World and host in on their own.

## Pre-requisite
- If you're already a contributor, clone the repository to your local by entering this command: 
```
git clone https://github.com/kelvinlegolas3/kru-kru-raft.git
```
- Get the latest changes by entering this command: 
```
git pull
```

## Repository Structure
- Each folder in the root directory of this repository is a World in Raft.

## Pulling the latest changes of a World from this repository to your Raft World
**If you already have the World in your local**
- To know your local World directory, launch the game and then click **Load World**.
- Click **Open World Folder Path**. 
- Go back to the repository, then find the folder name of the world you want to pull from.
- Copy and paste the World folder directory from this repository and replace what's in your local World directory.
- Launch the game and you should be able to see the latest version of the World.

**If you don't have the World in your local yet**
- Copy and paste the World folder directory from this repository to your local World directory.
- Launch the game and you should be able to import the World.

## Pushing the latest changes from your Raft World to this repository
- After making progress to your World, make sure to push your changes to this repository.
- Go to your local World directory.
- Copy and paste the World folder directory from your local World directory and replace what's in your Git repository.
- Commit and push your changes by entering this command: 
```
git add -A
git commit -m "I deleted the whole base guys"
git push
```

**Recommended commit messages**:
- _"Sail moved to middle"_
- _"Snatched all the planks in Storage room"_
- _"Parked the Raft in an Island"_

## Reminders
- Make sure that you're always pulling the changes of this repository before hosting and making any necessary changes.
- Never host the same World in parallel to avoid parallel progress.

-- Cartman
