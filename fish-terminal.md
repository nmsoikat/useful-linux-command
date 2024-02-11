Step 1: Add the Fish Shell Repository
`sudo apt-add-repository ppa:fish-shell/release-3`

Step 2: Update and Upgrade Repository Packages
`sudo apt-get update && sudo apt-get upgrade`

Step 3: Install Fish Shell
`sudo apt-get install fish`

Step 4: Set Fish Shell as the Default Shell
`sudo chsh -s /usr/local/bin/fish`

If above command not work.
`chsh -s $(which fish)`
Back to bash terminal
`chsh -s $(which bash)`