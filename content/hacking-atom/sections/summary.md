---
title: Summary
---
### Summary

If you finished this chapter, you should be an Atom-hacking master. We've discussed how you should work with CoffeeScript, and how to put it to good use in creating packages. You should also be able to do this in your own created theme now.

Even when something goes wrong, you should be able to debug this easily. But also fewer things should go wrong, because you are capable of writing great specs for Atom.

In the next chapter, we’ll go into more of a deep dive on individual internal APIs and systems of Atom, even looking at some Atom source to see how things are really getting done.
atom --version
Atom    : 1.8.0
Electron: 0.36.8
Chrome  : 47.0.2526.110
Node    : 5.1.1
%USERPROFILE%\.atom-backup
~/.atom/packages or ~/.atom/dev/packages
apm links
/Users/octocat/.atom/dev/packages (0)
└── (no links)
/Users/octocat/.atom/packages (1)
└── color-picker -> /Users/octocat/github/color-picker
See apm links --help and apm unlink --help for more information on these commands.
apm unlink --all to easily unlink all packages and themes
settings-view:open	
ctrl-,

cmd-shift-p (macOS) or ctrl-shift-p (Linux/Windows) in Atom.
-shift-p (macOS) or ctrl-shift-p (Linux/Windows) in Atom.
https://travis-ci.org/atom/whitespace.svg?branch=master
 "name": "keybinding-resolver",
  "main": "./lib/main",
  "version": "0.38.1",
  "description": "Show what commands a keybinding resolves to",
  "license": "MIT",
  "repository": "https://github.com/atom/keybinding-resolver",
  "engines": {
    "atom": ">0.79.0"
  },
  "dependencies": {
    "etch": "0.9.0",
    "fs-plus": "^3.0.0",
    "temp": "^0.8.1"
  },
  "devDependencies": {
    "standard": "^10.0.3"
  },
  "standard": {
    "env": {
      "atomtest": true,
      "browser": true,
      "jasmine": true,
      "node": true
    },
    "globals": [
      "atom"
    ]
  }
}
enter escape backspace delete tab home end pageup pagedown left right up down space
