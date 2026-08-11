# Normalise error messages across handlers

Profiling showed the resolver repeating identical lookups within a single request. Adds a small per-request memo.

Change #2 of 5 on branch `pr/20260811-130203-2-normalise-error-messages-across-handlers`.
