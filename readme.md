# git submodule helper scripts

## Installation
1. save the files under ~/bin
2. add ~/bin into the PATH (in .bashrc or .zshrc)
3. restart the terminal or source corresponding rc file (e.g. source ~/.bashrc)

## File List

[ap](./ap):
Git push everything: branches, tags, submodules

[gc](./gc):
Git clone with submodules but save bandwidth by shallow the submodules

[gitr](./gitr):
Run commands recursively on each git repo, excluding submodules

[gitrs](./gitrs):
Run commands recursively on each git repo, including submodules

[gu](./gu):
Update each submodule recursively

[pgitr](./pgitr):
Like gitr but runs in parallel

[pgitrs](./pgitrs)
Like gitrs but runs in parallel
