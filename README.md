# Legal Patent Assistant — Remainder Desk 1.0

Independent native Windows desk. Not a copy of anyone else's product.

You stake a trouble. You name remainder pieces as separate meanings. You pin found text with a locator. Occupation happens only when a person records a reading: this pin eats, misses, or cannot be called against this piece. Shared words are a hint. They never stamp occupancy. A brief is a handoff to a human. It is not a patent, not advice, and not permission to file.

The hard problem this desk holds is comparison: does this passage occupy that meaning? It refuses to answer that by counting overlapping tokens. Combination across pins is named. Obviousness is not stamped.

## Run

Double-click `Launch Remainder Desk.bat`, or:

```text
py -3 run.py
py -3 -m unittest discover -s tests
```

File → Load demo case walks a factory-belt example: sensing is eaten, motor take-up is eaten, commanding the motor from the measured load is still missed. That last piece is the live remainder.

Runtime cases live under `%LOCALAPPDATA%\LegalPatentAssistant\runtime`.

Code signing and an installer are a release step, not claimed by this build.
