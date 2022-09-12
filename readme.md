**DFPlayer Mini Library Test Modifications**

This version of the DFPlayer Mini library has been modified to include a method to indicate whether the Player is playing a track.

The method is called isPlaying() and returns a Boolean value, True if playing or False if not.

**\*\* Test Code only \*\***

The best way to use this version of the library is to download and place it in the same directory as your program. Change the #include to read:

#include "./DFRobotDFPlayerMini.h"

This way, you are not interfering with any other installation of the library and you can easily revert your code if there is a problem.

Did I mention that your use of this code is at your own risk, as I do not yet have a DFPlayer Mini to test against, I cannot warrant that this code is suitable for any use or purpose.