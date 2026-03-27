# trillia
Welcome! Trillia is a flower-themed expansion pack for the Battle for Wesnoth, a 2003 open-source turn-based RPG that's one of my favorite childhood games (yes, you can play it on a Raspberry Pi!)

## How do I install Trillia?!

Simple!

1. Download the latest stable version of Wesnoth for your OS over at http://wesnoth.org/!
2. Install your copy of Wesnoth and boot it up! I'd recommend doing the tutorial first.
3. Head over to this folder:

**Mac** (superior):
`~/Library/Containers/org.wesnoth.Wesnoth/Data/Library/Application Support/Wesnoth_<version>`

**Windows**:
`Documents\My Games\Wesnoth<version>`

**Linux**:
`~/.local/share/wesnoth/<version>`

**Linux via Flatpak**:
`~/.var/app/org.wesnoth.Wesnoth/data/wesnoth/<version>`

If you're still having trouble finding it, head over to https://wiki.wesnoth.org/Editingwesnoth/ for some additional support.

4. Inside that folder, open up `/data/add-ons/`.
5. Open up your terminal and type `git clone https://github.com/newtontriumphant/trillia/`!
6. After Git finishes up, fully quit and re-open The Battle For Wesnoth.
7. Press `Campaigns`!
8. Scroll down, press `Trillia`, and click `Start Campaign`!

## What does Trillia do?

For now, it's only one scenario, but I plan to expand it to six or seven. The goal of the scenario is to control a game character called Trillia and defeat orcs who are trying to find Trillium flowers for their leader.

## What if I want to play Trillia without downloading Wesnoth?

A 10-minute runthrough of the mod can be found at https://youtu.be/2c_mQeivy6Y/ for your reference!

## How long did this mod take to code?

The code itself was rather light and only took ~1h10m to create, but designing the map and scenario logic took approximately 2 additional hours.

## Will this give me a virus??

No, the full source code is in this repository. Feel free to look through it or ask your LLM of choice to check this for viruses. Literally all this does is add one scenario file and one map to your base game installation.

Thanks for playing Trillia!