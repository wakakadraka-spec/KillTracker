# CHATGPT CHECKLIST

## Architecture
- [ ] Never hardcode game-specific logic into the engine.
- [ ] Every detector is a standalone plugin.
- [ ] Every plugin has metadata.
- [ ] Every module has one responsibility.
- [ ] Engine never directly talks to GUI.

## Performance
- [ ] Never scan Workspace every frame.
- [ ] Cache expensive lookups.
- [ ] Profile detectors.
- [ ] Track detector runtime.

## Logging
- [ ] Everything important gets logged.
- [ ] Every detector explains WHY it fired.
- [ ] Unknown behavior gets reported.

## Code Quality
- [ ] No duplicated code.
- [ ] No global variables.
- [ ] Consistent formatting.
- [ ] Document every public API.

## GUI
- [ ] Every feature debuggable.
- [ ] Everything toggleable.
- [ ] Theme support.

## Detection
- [ ] Confidence score.
- [ ] Detector source.
- [ ] Timestamp.
- [ ] Weapon if known.

## Future
- [ ] Automatic detector prioritization.
- [ ] Game profiling.
- [ ] Detector analytics.
- [ ] Replay support.
