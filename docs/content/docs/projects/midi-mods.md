---
title: "MIDI mods"
---

# MIDI mods



## MIDI start/stop filter

The [Midiboy](https://blokas.io/midiboy/) is an Arduino-compatible board for MIDI prototyping. This sketch is a hack of the
MIDI monitor that will block the MIDI start/stop/continue messages. MIDI clock events still pass through. This will let you
sync the modulators to the BPM of other MIDI devices, but skip the Typhon's internal sequencer. This is great if you want to
use an external sequencer but still keep your effects synced to the beat.

https://github.com/PatrickLang/Midimon/tree/filter-midi-transport
