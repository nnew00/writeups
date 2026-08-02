---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: '{{ .Date }}'
draft: true
# CTF metadata
categories: ["pwn"]          # pwn | web | crypto | rev | forensics | misc
tags: ["heap", "glibc"]
event: ""                    # e.g. "picoCTF 2026"
difficulty: ""               # easy | medium | hard
points:                      # challenge points, optional
math: false                  # set true for KaTeX (crypto writeups)
summary: "One-line hook shown in list + search."
---
