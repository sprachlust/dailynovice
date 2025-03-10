---
title: "Add emojis to post titles"
draft: false
tags:
  - 
---

After I added emojis to the note titles, and ran `npx quartz sync`, the console threw an error.
I googled the error and rummaged through the posts on the Quartz discord, but didn't find any definitive answers.

After searching and searching, it occurred to me that maybe it has to do with the emojis I added to the beginning of the note titles.

I did a quick search on Discord, and found some mention about emojis not working.
I removed the emojis from the posts and voila that did away with the error.

But then...my `index.md` (actual title `Archway`) has an emoji in the note title...how is it working there?

I realized that the solution is to remove the emoji from the actual note title but keep the emoji in the Properties YAML. Then the emoji does show up.
