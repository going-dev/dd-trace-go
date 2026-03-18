# TODO

- [ ] Modify `NewPropagator` to store a field based on `DD_TRACE_PROPAGATION_BEHAVIOR_EXTRACT`.
- [ ] Check on other places where you need to "register" this env var.
- [ ] Modify `chainedPropagator.Extract()` according to `p.propagationBehaviorExtract` (or whatever the name you choose).

- [ ] Remove and untrack the rfc .md file
