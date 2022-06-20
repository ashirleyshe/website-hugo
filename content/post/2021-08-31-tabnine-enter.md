---
title:       "Tabnine: avoid selecting the suggestion when changing to new line"
subtitle:    ""
description: ""
date:        2021-08-31
author:      "Shirley Hsu"
image:       ""
tags:        ["vscode", "tabnine"]
categories:  ["Tech" ]
---

## Problem

[Tabnine](https://www.tabnine.com/) 是一個自動補齊程式碼的 plugin，但常常不能精準預測我什麼時候要換行。
![enter](https://user-images.githubusercontent.com/15422817/84587748-a34fd900-ae2a-11ea-936b-1007651af768.gif)

## Solution

VS code Settings → Editor → Accept Suggestion On Enter: off

選建議只能先用 `tab` 了。
