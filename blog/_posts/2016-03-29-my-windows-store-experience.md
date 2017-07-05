---
layout: post
title: "My Windows Store Experience"
date: 2016-03-29 8:55:00 -0500
categories: blog
blog: true
snippet: "Fighting games are a genre that I had never sampled before, so I was excited today to try the newly-released Killer Instinct on PC. The downside? I would have to download it from the dreaded Windows Store, a platform that has been ridiculed for attempting to impose console-like exlusivity and restrictions on PC games."
---

<img id="review-content-header" src="{{ site.github.url }}/blog/images/my-windows-store-experience/win10.jpg">

Fighting games are a genre that I had never sampled before, so I was excited today to try the newly-released *Killer Instinct* on PC. The downside? I would have to download it from the dreaded Windows Store, a platform that has been ridiculed for attempting to impose console-like exlusivity and restrictions on PC games. I figured that I would give the young platform a chance with this Free game, since I had no intent of spending money there any time soon. Unfortunately, I was soon disappointed.

*Killer Instinct* ran fine on my PC, and I didn't experience any technical issues myself, but I am not in the SLI/144hz minority that has been the most vocal about the Windows Store. The graphics options menu was very lackluster, and I noticed the lack of an exclusive fullscreen mode present in all Windows Store apps. I was also greeted almost immediately with a barrage of XBOX login prompts and notifications which made me just a tad frustrated. I tried the game and didn't much enjoy it, so I proceeded to attempt an uninstallation, and this is where problems began to arise.

I uninstalled the game perfectly normally, but I decided to check and make sure it was gone from the E:\WindowsApps installation directory as I had read a post earlier commenting that the apps are not actually removed fully from your system by uninstalling. I then noticed that many of my programs were now flinging errors at my face, claiming that they could not actually *access* the contents of the WindowsApps folder on my E:\ drive. I was confused by this, so I decided to try and unlock the folder.

<p style="height: 163px;"><img id="customwrap" src="{{ site.github.url }}/blog/images/my-windows-store-experience/Capture.PNG" style="position: absolute; margin-left: -176px; left: 50%;"></p>

When I attempted to open the folder, this error box decided to grace me with its presence. At this point I was becoming rather angry that Windows decides to create a folder that you have no control over on **your computer**. I opened the Properties dialog of the folder and decided to see if I could give myself permissions somehow. While I was successful in setting myself as the owner, permissions were not able to be saved. I also attempted a similar result using an Elevated PowerShell, and it was neither able to access the permissions of the folder nor remove it.

I decided to boot into my Linux partition and remove it forcefully (it's an empty folder for crying out loud), but before I did I decided to see what Microsoft Live Chat had to say on the matter. After a long-winded exposition that I was asked to repeat one time too many, the (very kind) answer tech provided me with [this link][1], hoping that it would solve my problem. Hilariously, the only person who actually managed to resolve the issue did so by using Linux as I had planned to do as a last resort.

This is ridiculous on Microsoft's part; even if it is only an empty folder it symbolizes something greater, that we no longer own our Windows installations, our Windows installations own us.

[1]: http://answers.microsoft.com/en-us/windows/forum/windows_10-files/unable-to-delete-windowsapps-folders-created-after/82f44cad-233a-4a05-8f1a-788b2887da2d
