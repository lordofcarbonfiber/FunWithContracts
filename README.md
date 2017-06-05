# Sample Contracts
`Button.se` is a simple contract written in Serpent that acts as a programatic musical chairs.
Users can `press_button` by sending Wei greater than the cutoff threshold, placing them as the current leader, expanding the pot, and reseting the timer. If a certain number of blocks pass with no button presses the current leader can call `claim_treasure` collecting the pot and restarting the game.