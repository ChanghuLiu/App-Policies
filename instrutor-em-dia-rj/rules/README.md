# Ruleset revision policy

`rulesetRevision` is the monotonic production revision for this ruleset.

Never decrease or reuse a published revision. This includes temporary or test
revisions exposed on the production endpoint; the next production revision
must always be greater.
