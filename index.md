---
layout: single
title: "under_construction.c"
author_profile: true
classes: wide
permalink: /
header:
  overlay_color: "#000000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/header-bg.jpg
---

```c
#include <stdio.h>

/* This site is a placeholder.
   No blog. No portfolio. */

// ─────────────────────
//        ABOUT
// ─────────────────────
void about(void) {
    printf("🧠 Learning C\n");
    printf("🤔 Mostly out of curiosity\n");
    printf("🐞 Debugging one segfault at a time\n");
}

// ─────────────────────
//         NOW
// ─────────────────────
void now(void) {
    printf("🛠️ Building a simple REPL-style tool\n");
    printf("💻 Occasionally compiling successfully first time\n");
    printf("🧘 Becoming a *ptr, malloc(), and free() Zen master\n");
}

// ─────────────────────
//        USES
// ─────────────────────
void uses(void) {
    printf("🐧 OS: Linux\n");
    printf("⌨️ Editor: Neovim\n");
    printf("🔧 Tools: Git, Make, Valgrind\n");
}

// ─────────────────────
//        MAIN
// ─────────────────────
int main(void) {
    about();
    now();
    uses();
    return 1; // Not quite there yet
}
```

