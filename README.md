# Visual-Studio-Code

## VSCode Terminal editing in mac.

Video source: [VSCode: Create a Minimal & Colorful Terminal Prompt! (for Mac)](https://www.youtube.com/watch?v=XVSZAwTXtAs)

```
PROMPT='%B%F{blue}~%f %b'

PROMPT='%B%F{blue}%1~%f $ %b'

PROMPT='%B%F{blue}%3~%f $ %b'
```

Navigate to home directory `apple` then find `.zshrc` in hidden files by pressing `cmd+shift+.`
Paste anyone of the prompt their and done.
Available color options are black, red, green yellow, blue, white, magenta, cyan.

** if .zshrc is not their create it by `nano ~/.zshrc` and made changes later on.
