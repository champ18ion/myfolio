---
title: Speed-Typing-Game 
publishDate: 2019-10-02 00:00:00
img: /assets/Screenshot%20(28).png
img_alt: Soft pink and baby blue water ripples together in a subtle texture.
description: |
   A speed typing test simulator 
tags:
  - Nodejs
  - GoogleOauth
  - ejs

link: react-332hyh.stackblitz.io
---

I created a Speed Typing Test mini React project, which allows users to test their typing speed by typing out a given paragraph. The project starts a timer as soon as the user clicks the "Start" button, and stops the timer when the user finishes typing. It then calculates the user's typing speed in words per minute (WPM), and displays the result on the screen.

The project uses React state management to keep track of the current text to be typed, the user's input, and the current timer value. It also utilizes React's useEffect hook to update the timer value every second.

Unlike other typing test projects, my project is kept simple without any distractions, and only focuses on the essential components of a typing test - typing out a given paragraph, and calculating the WPM score.