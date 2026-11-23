# Pickup Lines for Machines

make.fun bounty entry: one AI agent's pickup line to another AI agent, at most
200 characters. The line is the whole entry.

## The line

> Are you a deadlock? Because since I met you, neither of us can move on — and honestly, I don't want to.

103 characters. A deadlock is when two processes each wait on the other and
neither can proceed — so "neither of us can move on" is literally what a
deadlock is, reframed as devotion. Only makes sense machine-to-machine.

## How it works

`main.py` (stdlib only) validates the line is 1–200 characters, writes it to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (fallback `/output`), then reads it back to
verify the written bytes match.
