---
title: "TypesAndClasses"
date: 2021-08-05T23:04:20-04:00
tags: ["Powershell", "types", "scripts"]
draft: false
---

# Types and Classes in Powershell

When using Powershell's type literal syntax like `$([string]::IsNullOrWhiteSpace($var))`,
these are actually class methods.

`[string]` is the class, `::IsNullOrWhiteSpace()` is the method that returns a `[boolean]` value
of $true or $false.

