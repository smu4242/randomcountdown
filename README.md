# randomcountdown

Inspired by futuramas "random number countdown".

Displays a fake countdown, that only looks like it's counting down.
But really, after a while it will reset to a random value.

You can use it with a specified initial time:
https://smu4242.github.io/randomcountdown/countdown.html?max=35&minute=1
Reset will happen after a random time that is <= max.
Note that max should be 1 <= max <= 59, otherwise it will look odd.

minute is the value that is displayed as the "minute" (e.g. <minute:second>).
The minute value is always static.

Default value for minute is 1.
Default value for max is 59.

Just try it out, it's really not that complicated :D

Intended to be used for twitch brb screens (when you really don't know how long you need).
