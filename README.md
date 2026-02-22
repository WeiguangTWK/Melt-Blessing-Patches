# Why it exist?
In the very beginning, We (NekoHyper) directly uses the prebuilt blob from [Pzqqt's Github Release](https://github.com/Pzqqt/android_kernel_xiaomi_marble/releases), but since Melt 3.9 Pzqqt no longer posts AK3 archive in Github, so in the throught of ZeroTrust as NekoHyper always hold, we choose to build our own one.

As time goes on, the idea gap (we have different view on KCompressd, KShrink_lruvecd and KShrink_slabd but after all respect above everything) between Melt and Melt-Blessing became bigger then we began to implement our own changes. At first we just revert some commits over the latest source code, but now new feature added (ZBlock) and its time to start our own repo

# What the difference
Check code

# Which one is better
It depends, but the so called "advantages" compared to Melt are acutally quite small so you have control :)

# CREDITS
[Pzqqt](https://github.com/Pzqqt/android_kernel_xiaomi_marble): The dev of Melt, the best teacher for GKI beginners, whitout him, Melt-Blessing won't even exist

[asto18089](https://github.com/asto18089): One of Pandora Kernel Devs, TREMENDOUSLY SKILLED developer. He informed me many points that can be only noticed by experienced Linux dev

[nakixii](https://github.com/nakixii): One of Pandora Kernel Devs, he gives many critical view and guide on some tech problem

HAMJTY: One of Pandora Kernel Devs, he also gives many critical view and guide on some tech problem
