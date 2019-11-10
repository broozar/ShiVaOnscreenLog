# ShiVaOnscreenLog
Logs your ShiVa messages to an onscreen HUD

This simple AIModel+HUD allows you to log information to an onscreen console. Very useful for testing applications on (mobile) devices where getting hold of actual .log files is rather tricky.

Onscreen Log HUD - comes with a simple AI and HUD. Useful as debugging tool for devices where you do not have immediate access to the shiva log text files.

Link both in your Game Editor Module and you are good to go!

```
user.sendEvent (application.getCurrentUser(), "onscreenLog", "onLog", "yourstring")
user.sendEvent (application.getCurrentUser(), "onscreenLog", "onLog", yournumber)
```
