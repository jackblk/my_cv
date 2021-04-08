# Intro
Nice looking, responsive web page CV on both desktop & mobile with auto-generated PDF file, powered by CI/CD pipeline from Github Actions.

## But why?
I would love to write a CV without bothering too much about the design, where I can easily update & share. Oh, and it should be automated because I like to automate stuff.

Web page CV is lovely, responsive for both desktop & mobile, but it is not PDF, which HRs will need. So I built a CI/CD pipeline via Github Actions to build PDF file based on the web page and post it on [Release Page](https://github.com/jackblk/my_cv/releases).

## Guide for forking
Feel free to fork and use my repo.

Since I use [Ngrok](https://ngrok.com/) to tunnel the newest build to convert to PDF, if you fork my repo for the first time, it might not build & release your PDF file correctly.
Go to Secrets of your repo and setup `NGROK_TOKEN` from your account.

## Credits
* Designed by [Xiaoying Riley](https://github.com/xriley/DevResume-Theme). Thank you!
