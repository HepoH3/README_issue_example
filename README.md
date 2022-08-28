# README_issue_example

This repo is to illustrate issue with cyrillic folder names and README files contained there.

This repo contains three folders: "test", "тест" (russian translation of word "test") and "тест2".  
The first two folders contains identical README.md with simple phrase "# Hello World!". Last one contains READ.md with the same text.
If two clone this repo, you will face zero problems. But if you try to go "тест" folder from browser on github site, you either will stuck in endless page loading or get five hundreds with something error.  
Moreover, if you go to the "тест2" folder you will get there like it would be "test" folder — without any difficulties. But READ.md file will not displayed automaticaly in this folder, because it's not a README.md file.
Additionally, you can't open history in both "тест" and "тест2" folders — even if you fix repo structure in future commits like it was done in "тест2" folder — README.md was renamed to READ.md.
