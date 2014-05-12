---
layout: entry
title: Entry 1
category: Category 1
---

# This is a H1

## This is a H2

### This is a H3

Lorem ipsum *dolor* sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis **aute** irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

    EventBus bus = EventBus.create();
    bus.subscribe(MyEvent.class, event -> System.out.println(event.getMessage()));
    bus.post(new MyEvent("Hello World!"));
