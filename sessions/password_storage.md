---
layout: page
title: Password Storage
video_src: https://www.youtube-nocookie.com/embed/xZ5cxxllgP8
---

In this session we'll discuss methods of securely storing passwords and what to watch out for.

What you'll learn
-----------------

- Use Bcrypt (or Scrypt)
- Goals for password security
- Never use a bare hash (e.g. MD5, SHA1)
	- They're too fast
- If you can't use those, use PBKDF2 and slow it way down
