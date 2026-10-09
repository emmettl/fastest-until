# Fastest Until

Pick a computer, send it back in time, and see the last year it would have been the fastest computer in the world.

**Live:** https://emmettl.github.io/fastest-until/

- Compares a computer's speed against every record holder since the Zuse Z3 (1941), through the June 2026 TOP500 list.
- Two ways to count: sustained FP64, the way TOP500 measures, or peak FP32 GPU, the way spec sheets do.
- Includes presets from the Commodore 64 and Game Boy to an H100 and a GB200 rack, a box for typing in any speed, and an in-browser benchmark that measures the device you're on.

Records from 1993 on are TOP500 Linpack Rmax. Earlier figures and all device speeds are rough estimates.

It's a single static `index.html` with no build step.
