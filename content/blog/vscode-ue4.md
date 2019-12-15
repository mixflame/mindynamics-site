---
title: "Unreal Engine 4 VSCode Fixes"
date: 2019-12-13T09:34:39.595500-07:00
---

While working with VS Code in UE4 I ran into a few problems. Here are the solutions.

Problem: VSCode cannot find headers

Solution: File > Refresh Visual Studio Code Project


Problem: Cannot compile code for the editor (for example placing a component on a custom actor)

Solution: Close UE4 and build using "<Project>Editor Win64 Development Build", relaunch UE4

Hope this helps!