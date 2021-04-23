Install this by dropping the content folder into your Pavlov VR modkit.
Next you should move the LaunchPad folder into your UGC or SVR using the ue4 editor's content browser. If you use file explorer for this step it will break.
Then from there add a launchPadStart actor into the world.
it needs to be positioned above the fround at about chest level
Then in the "modes" menu, the one on the right, drag an empty actor into the world where you want the launchpad to go. This also needs to be above the ground at about chest height.
Click on the LaunchPadStart actor that is in your world and on the right there should be a details thing. Look for an "End Point Actor" field then click the little eyedropper icon and select the Empty Actor that you placed earlier.
Next there are a couple of settings you can choose. Those are:
  Launch time, this is the amount of time in seconds for the launch to complete.
  Max Height above, this controls the height of the arc. setting this to 0 will result in a straight line as the launch path. Setting this as 200 will result in the arc going a max of 2 meters above the straight line. This is useful if you want it to go over a wall or you want it to look higher up.
