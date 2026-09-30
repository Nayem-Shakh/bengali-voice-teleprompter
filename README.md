# VoiceFlow Teleprompter — Bengali Edition

A standalone Android-friendly web teleprompter with Bengali speech-following.

## Important
This is a self-contained implementation inspired by the matching behavior of the MIT-licensed jlecomte/voice-activated-teleprompter project. It is not a byte-for-byte modified copy of that repository.

### Use
1. Host these files on an HTTPS site (GitHub Pages is ideal).
2. Open the site in current Chrome on Android.
3. Paste a Bengali script with **Edit**.
4. Select **বাংলা (Bangladesh)**.
5. Tap **Follow voice** and grant microphone permission.
6. Put the phone behind your physical teleprompter glass.
7. Use a Bluetooth/HID foot pedal: Space = start/stop; arrows = seek.

### Important limitation
The app uses the browser's Web Speech API. Bengali availability and recognition quality are determined by the browser/Android speech-recognition service. This version cannot guarantee Bengali recognition on every Android device.

### Features
- Bengali (Bangladesh/India), English, Hindi, Urdu language choices
- Voice-following with fuzzy word matching
- Mirror mode
- Fullscreen
- Editable local script
- Inline [hints] ignored by matching
- Foot-pedal/keyboard controls
- LocalStorage script persistence
- PWA shell
- Screen wake-lock when supported

MIT-licensed upstream project: https://github.com/jlecomte/voice-activated-teleprompter
