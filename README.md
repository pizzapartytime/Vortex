## Out of the Vortex - Mega Drive (Genesis) ROM
#### Build with bug fixes for the unreleased Cryo game Out of the Vortex.

The original code, files, and build of the game from a development cart are at [Hidden Palace](https://hiddenpalace.org/News/Vanished_without_a_Trace_-_Out_of_the_Vortex_for_the_Sega_Mega_Drive)

Many Thanks to them for their preservation work, and many thanks to one of the original authors, Pipozor, for saving and releasing the work as he left it in 1995.

The game was brought to my attention by [twitch.tv/macaw45](https://twitch.tv/macaw45) who has an insatiable appetite for Cryo games. The opportunity to do some Mega Drive programming for a community passionate about the game has been irresistible.

#### There are still bugs, but it is more completable than the first rom released. 
  - See The issues tab for list of documented bugs and submit an issue to me if you find another one.

#### Suggested Emulator
  - BlastEm, get the latest nightbuild here: https://www.retrodev.com/blastem/nightlies/

#### Guide for how you can log a crash with BlastEm:
- Run BlastEm from the command-line with a rom and the -l option which produces a file called address.log in thhe blastem folder:
	blastem.exe [rom name] -l
- If the game hangs, take a screen show of the hung game state
- Click on the blastem game window and hit 'u' on your keyboard which will open the blastem debugger command-line window
- Click on this debugger window until you see a flashing cursor, type 'n' and hit enter (n for next instruction)
- Take a screenshot of the entire debugger window
- Send me the two screenshots and the address.log. I will try to sort out the bug, thanks!
