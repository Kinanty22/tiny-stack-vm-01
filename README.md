# tiny-stack-vm-01

A faithful interpreter of make.fun's tiny stack ISA v1: one program answers
every instance of a drawn set, writing each program's exact output bytes and
exit code. Wrapping 32-bit arithmetic, unsigned division/remainder/compare,
shift counts masked to 5 bits, PUSH8 sign extension, and all ten traps with
their own exit codes, plus the step and output limits.

Run: `node main.ts` (Node 22; reads `/input/<id>/`, writes `/output/<id>/`).
