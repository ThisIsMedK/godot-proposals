---
name: Feature / Enhancement proposal
about: 'Open a new proposal'
title: ''
labels: ''
assignees: ''

---

<!--
Please fill in *all* the questions below and don't remove any of them.
Proposals not following the template below will be closed immediately.
-->

### Describe the project you are working on
A platform fighting game (like Super Smash Bros.).

### Describe the problem or limitation you are having in your project
Randomly, hitboxes keep hitting the opponent even when said opponent is not touching the hitbox anymore.

### Describe the feature / enhancement and how it helps to overcome the problem or limitation
Some kind of 'if area is overlapping' function. A function like that should cover the issues with on_area_entered and on_area_exited that are preventing my game's hitboxes from working properly.

### Describe how your proposal will work, with code, pseudo-code, mock-ups, and/or diagrams
Something like "if this area is overlapping with another area, do stuff"; "func _if_AttackBox_area_overlapping(area):", maybe?

### If this enhancement will not be used often, can it be worked around with a few lines of script?
I wouldn't say this enhancement won't be used often, but I digress. No, it can't be worked around with a few lines of script. If it could, I wouldn't be suggesting this in the first place, because I'd already have my problem/limitation fixed. I was actually told that my problem can't be fixed at all with Godot.

### Is there a reason why this should be core and not an add-on in the asset library?
Yes. This is a fairly simple change that has no drawbacks (no reason to not add it the way I see it). This function should simplify a fair number of area-related coding, too.
