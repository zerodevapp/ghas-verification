# ghas-verification

Throwaway repository used to verify the GitHub Advanced Security rollout end to end:
secret scanning, push protection, delegated bypass routing, Dependabot and code scanning.

## Everything in `fixtures/` is fake

The credentials in this repository are **deliberately non-functional**. They are either
vendor-published documentation examples or structurally valid strings with filler bodies.
None of them authenticate against anything, and none were ever live.

They exist so we can see what a real finding looks like in the Security tab without
exposing a real credential to do it.

## Safe to delete

This repository has no dependents and no history worth keeping. Delete it once the
rollout is signed off.

<!-- rescan trigger 2026-11-25T17:06:06Z -->
