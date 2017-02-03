---
layout: post
title: How to run nested TMux
---

Sometimes, you need/want to run tmux within tmux, but this gets a little dicey because by default, the inner tmux won't get your prefix keys, but luckily there is an easy solution.
Just add the following to your _.tmux.conf_, then to send a command to the inner tmux, you simply do <kbd>C-a a</kbd> (or <kbd>C-b b</kbd>) depending on your prefix:

```

#For Using Nested tmux
bind-key a send-prefix

```
