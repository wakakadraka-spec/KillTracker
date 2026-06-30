# KillTracker Philosophy

The framework exists to observe combat events.

It is not built around specific games.

It is not built around specific weapons.

It is not built around a single detection method.

Everything is modular.

Everything is replaceable.

Everything is observable.

Every subsystem should have one responsibility.

The engine coordinates.

Detectors detect.

The GUI displays.

The logger records.

The profiler measures.

Adding detector #100 should require creating only one new module.

The engine should never need modification for new detectors.

Every detector contributes confidence.

The engine decides.

The GUI only visualizes.

Maintainability is more important than speed of development.

Readable code is preferred over clever code.

Every commit should leave the repository in a better state than before.
