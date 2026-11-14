# Dashboard inspiration

References and ideas to revisit for Project Cydex. These are possibilities, not
committed features or claims of compatibility.

## Tessera: compact Home Assistant touch dashboard

Saved on 2026-11-14.

- [Community example: 4-inch Guition ESP touchscreen running Tessera](https://www.reddit.com/r/homeassistant/s/xmqHaShgKC)
- [Tessera source: MaxGramser/homeassistant_espscreen](https://github.com/MaxGramser/homeassistant_espscreen)
- [Tessera website and documentation](https://tessera-maxgramser.on-forge.com/)

Tessera provides a drag-and-drop dashboard editor for ESP32 touch panels,
including CYD, Guition and Waveshare devices. It is a related project worth
following for dashboard layout and configuration ideas.

The shared screenshots show a compact six-tile office dashboard with light
controls, weather, a temperature graph, household statuses and front-door state.
Ideas to revisit for Cydex:

- Mix controls and readings in a compact grid, with brightness sliders directly
  inside the light tiles.
- Show door state alongside time since the state changed.
- Use a contextual household status tile for laundry, bin collection and open
  doors or windows.
- Pair laundry completion time with the forecast for that time, helping decide
  whether to hang washing outside.
- Remind the user to unload finished laundry if the utility-room door has not
  opened within 30 minutes; clear the reminder when it opens.
- Keep weather compact and show a small temperature trend graph.

The laundry and door behaviors above come from the author's description in the
shared screenshots and include custom cards and Home Assistant automation;
they should not be assumed to be built-in Tessera features. The Reddit short
link could not be fetched when this reference was saved.
