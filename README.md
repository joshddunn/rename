# rename

A simple script that sleeps until you take a screen shot or screen recording. Then that screenshot gets renamed to something easier to deal with.

Will convert 
`Screen Shot 2020-02-04 at 12.50.10 AM.png` -> `screen_shot_1580777410.png`
`Screen Recording 2020-02-04 at 12.50.10 AM.mov` -> `screen_recording_1580777410.mov`

## install and usage

1. `git clone https://github.com/joshddunn/rename.git`
2. `cd rename`
3. `./rename start` will begin a daemon process
3. `./rename stop` will kill the daemon process
