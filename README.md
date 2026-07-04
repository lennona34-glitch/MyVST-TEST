# MyVST-TEST

MyVST-TEST is a small Windows VST3 testing host. Drop a `.vst3` plugin bundle, or a folder containing VST3 plugins, onto the window to load them. A single discovered plugin opens immediately; batch drops and folder scans load quietly so you can choose which editor to show. The most recently loaded plugin becomes the active audio/MIDI target.


## Use

- Drag a `.vst3` bundle onto the main window to load and open it.
- Drag a folder, such as `C:\Program Files\Common Files\VST3`, to scan it recursively without opening every editor at once.
- Use **Open...** to select a plugin bundle or folder.
- Use **Common VST3** to scan the standard all-users VST3 folder.
- Double-click a loaded plugin row to show its editor and make it active.
- Use the on-screen MIDI keyboard or any enabled MIDI input to test synths.
- Open **Audio/MIDI...** to change the audio driver, sample rate, buffer size, and MIDI devices.

This is intentionally a compact tester rather than a full DAW: one plugin is active for audio/MIDI processing at a time, but multiple editor windows can stay open.
