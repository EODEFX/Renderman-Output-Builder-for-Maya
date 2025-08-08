<p>This is a MEL script to add a customized Output builder for Renderman for Maya. This version was made for Renderman 21 and Maya 2017.
<p>The script doesn't currently work with LPE Object Groups; I haven't worked out how to write out every LPE to work with them.
<p>I also plan on rewriting this script using python and the ability to edit existing channels/outputs without having to open the Advanced Renderman Controls.
<p>The "Emissive Materials" checkbox allows you to build outputs that don't contain the influence of materials that utilize the Glow attribute. If you are using additive compositing with multiple Light Groups this will prevent glowing materials from unwanted multiplication. You can then create a light with 0.0 intensity, give it a unique Light Group, turn back on "Emissive Materials", and you now have a Light Group that is only the glowing materials in a shot.

