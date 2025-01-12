---
title: Making this website
---
I made this website using Quartz, by Jacky Zhao.  

I'd recommend his [tutorial & documentation](https://quartz.jzhao.xyz/), along with Nicole van der Hoeven's [Text](https://notes.nicolevanderhoeven.com/How+to+publish+Obsidian+notes+with+Quartz+on+GitHub+Pages) & [Video](https://www.youtube.com/watch?v=6s6DT1yN4dw) tutorials.

Some troubleshooting tips that I'd like to clear up, in case someone has similar difficulties:
1. You'll need to install [git](https://git-scm.com/). There are many options on install, but I left them all on their default option.
2. You must put the custom domain URL in the quartz.config.ts file, in the "baseURL".  For example, my line 18 looks like this:
	   `baseUrl: "richardhankins.me",`
3. For Windows, when the instructions reference Terminal, that's either "command prompt", or "Windows Powershell". Powershell is a bit prettier, so I use that.
4. Downloading NodeJS also downloads npm for you, which can save a step.
5. DO NOT PUT YOUR DIRECTORY INTO A CLOUD STORAGE FOLDER. It fundamentally breaks how git & github work. Aka `npx quartz sync` will not work. Github backs up your code anyways.


