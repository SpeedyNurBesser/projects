---
layout: post #Do not change.
category: [programming, writing] #One, more categories or no at all.
title:  "A_WritingProgram: Distraction-free writing software"
date:   2024-07-26 10:05:42 +0200
#author: jekyll #Author's nick.
nextPart: _posts/2024-07-31-mcsettings.md #Next part.
prevPart: _posts/2023-12-30-youtubeSearch.md #Previous part.
#og_image: assets/example.png #Open Graph preview image.
og_description: "A_WritingProgram: Distraction-free writing software" #Open Graph description.
---

Computers, browsers on them in particular, are a gateway to endless possibility and thus endless distractions. But since good writing cannot occur in such a distracting world, I in a few days created *A_WritingProgram*, a portable, distraction-free writing software for markdown, which blocks every other app on your computer until you have reached your writing goal (e.g. write 500 words or write for 1 hour).

*A_WritingProgram* is entirely written in Python using its in-build `tkinter` package. I added some quality of life features to tkinter's default text input widget like Undo/Redo, the ability to remove entire words in one button pressing using Ctrl+Backspace / Ctrl+Delete as well as the ability to add markdown sytnax using key combinations like Ctrl+I for *Italic Text*. 

<div class= "sx-center">
  <div class="sx-picture">
      <a href='https://github.com/user-attachments/assets/  b87ed2e6-b3b8-4369-be22-975d3abaacb0' data-lity>
          <img src="https://github.com/user-attachments/assets/ b87ed2e6-b3b8-4369-be22-975d3abaacb0">
      </a>
      <span class="sx-subtitle">A screenshot from the start-up window of A_WritingProgram</span>
  </div>
</div>

<div class="sx-picture sx-center">
    <a href='https://github.com/user-attachments/assets/5450bf89-205f-4219-83b3-c21fe4fcf8dd' data-lity>
        <img src="https://github.com/user-attachments/assets/5450bf89-205f-4219-83b3-c21fe4fcf8dd">
    </a>
    <span class="sx-subtitle">A screenshot from the main text editing window (Note the missing close button in the corner). The bar at the top displays the progress made towards reaching your goal. It's fairly unspectacular, but that's needed for it in order to not be distracting.</span>
</div>

I technically still work on this project, but since adding more features to something claiming to be distraction-free doesn't really work I only really act on incoming bug reports.

<div class='sx-button'>
  <a href='https://github.com/SpeedyNurBesser/A_WritingProgram' class='sx-button__content blue'>
    GitHub Repository
  </a>
</div>

Note, that there are simular programs available online like [FocusWriter](https://gottcode.org/focuswriter/) and [ColdTurkey Writer](https://getcoldturkey.com/writer/).