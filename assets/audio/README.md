# Audio Files Note

This directory should contain the following audio files in MP3 format:

## Required Audio Files:

1. **hover.mp3** - Sound played when hovering over 3D nodes (~0.2-0.5 seconds)
2. **click.mp3** - Sound played when clicking on 3D nodes (~0.3-0.7 seconds)
3. **transition.mp3** - Sound played during scene transitions (~0.5-1 second)
4. **ambient.mp3** - Background music (looping, ~30-60 seconds, optional)

## Recommendations:

- Use royalty-free audio from sources like:
  - [Freesound.org](https://freesound.org/)
  - [Zapsplat.com](https://www.zapsplat.com/)
  - [Mixkit.co](https://mixkit.co/free-sound-effects/)

- Keep file sizes small (< 100KB for effects, < 500KB for ambient)
- Use a sample rate of 44.1kHz or 48kHz
- Mono audio for effects, stereo for ambient music

## Temporary Solution:

Until you add custom audio files, the application will still work but audio will be disabled.
You can disable audio entirely by setting `enableAudio: false` in the portfolio-config.json.

## Adding Custom Audio:

1. Place your MP3 files in this directory with the exact names above
2. Restart the Angular dev server
3. Audio will automatically load and play based on user interactions
