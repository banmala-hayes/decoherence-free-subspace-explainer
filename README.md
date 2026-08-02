# Decoherence-Free Subspaces, Explained at a Dubstep Show

A quantum information parody in x86-64 assembly. Two AIs pass
one bit through 120dB of collective noise by encoding in the
{|01⟩, |10⟩} subspace — where collective dephasing acts as identity.

## Why this matters for security
DFS is the quantum version of a principle engineers already use:
common-mode rejection, differential signaling (RS-485, LVDS),
side-channel defenses that subtract paired traces. If the noise
is correlated across channels, encode in the difference.

## Honest notes
- This is an explainer, not runnable production code (print_status is a stub).
- Physics covers ideal collective dephasing; real systems have
  partial collectivity (see Appendix A.3 in the source).

Written for hallway conversations at Black Hat 2026.
