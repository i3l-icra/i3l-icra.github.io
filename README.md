# Supplementary research website

Static supplementary materials for I3L.

Preview with `python3 -m http.server 8765 --bind 127.0.0.1`.
The site includes the paper, walkthrough video, autonomous rollouts, interactive
figures, and articulated hardware models. Takeover episodes synchronize the recorded
robot joints with an illustrative JoyLo+ pose inset. The inset follows the robot
camera and upper-body orientation, with framing fitted to the current pose.
The robot panel is visible below the video on phones as well as on desktop.

Code and dataset buttons remain unavailable during anonymous review. Canonical
and social links use this review site, with no-index and no-referrer metadata.
Third-party library licenses are included alongside the bundled libraries.

Private, cookie-free analytics record page views and interactions. Browser Do Not
Track, Global Privacy Control, and `?analytics=off` disable measurement.

The device explorer has R1 Pro / Franka buttons in the upper-right corner and a
matching robot inset in the lower-right corner. The inset follows the joint
sliders and orbit controls. R1 Pro uses the inverse of the takeover mapping;
Franka uses CAD assembly offsets and aligned joint axes, with its stationary
mounting bracket as the root. Controls stay inside the shared CAD/Panda joint
limits. Zoom, Fit view, and Auto-rotate are inside the viewer at lower left.
The Panda model source, modifications, and Apache-2.0 license are documented in
`static/models/franka-NOTICE.txt` and `static/models/franka-LICENSE.txt`.
