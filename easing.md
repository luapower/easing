---
project:    easing
tagline:    easing functions in Lua
category:   Animation
---

## `local easing = require'easing'`

Robert Penner's [easing functions].

## `easing.<formula>(current_time - start_time, 0, 1, fixed_duration) -> value in 0..1`

The formulas map input `d` to output `r`, where `d` is in `0 .. t` and `r` is in `b + 0 .. c`.

Some formulas take additional parameters (see code).


[easing functions]: http://www.robertpenner.com/easing/
