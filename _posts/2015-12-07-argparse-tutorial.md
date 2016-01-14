---
layout: post
title: "Tutorial On argparse"
date: 2015-12-07
---
I have been trying to write this tutorial for a long time and now it is here. I have tried to omit extra basics to argparse .This tutorial focus on creating subcommands. like a git add <filename>,git status ,git push --all and so..<br>
To learn basics of argparse ,please go to python official documentation. <br> 
<table>
<tr><td>
<h2>Basics</h2>
<img src="../../../../../images/1.PNG"><br>
arguments can be passed to scripts command line or can be provided as list in parse_args()
</td></tr>
<tr><td>
<h2>Optional Arguments</h2>
<img src="../../../../../images/2.PNG">
</td></tr>
<tr><td>
<h2>Subcommands</h2>
<br>To make things easy , think a command like a tree having levels and branches.
<img src="../../../../../images/3.PNG">
<br>Let's try to see the help of our new subcommand
<img src="../../../../../images/5.PNG">
<br>Let's try using our new subcommand
<img src="../../../../../images/6.PNG">
</td></tr>
</table>
Thank you everyone for going through this tutorial. I hope this helps you as it helped me.
