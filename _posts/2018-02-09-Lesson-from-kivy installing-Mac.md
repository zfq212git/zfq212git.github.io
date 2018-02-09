---
title: Lessons from installing Kivy (Mac)
date: 2018-02-09 13:30:30
---

Encironment: Mac OSX 10.13.3

## Purpose: part of install for running some machine learning code (with Python and Pytorch)

## Words-
(1) Generally, following the instructions on kivy.org was fine.
(2) The tricky thing happened when I ran the last step "pip install kivy".  It reported an error "Failed building wheel for kivy".
    After reading a few posts online, I found several posts stated that running the development version of kivy could avoid this issue.
    Then I followed the instruction on kivy.org to run the development version, "pip install https://github.com/kivy/kivy/archive/master.zip".
    It still reported some errors.  Giving some read and thought on those errors, I guess they mostly were caused by that I did not have xcode 
    installed on the machine.  So, I installed xcode and run the install again.  It worked!
