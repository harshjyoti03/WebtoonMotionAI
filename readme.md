# WebtoonMotionAI

WebtoonMotionAI is a Python-based pipeline that converts webtoon/manhwa panels into a motion-comic style video.

## Features

- Extracts and processes webtoon panels
- Generates narration audio using TTS
- Synchronizes audio with panel transitions
- Creates scrolling motion effects
- Produces cinematic MP4 outputs
- Supports panel-based storytelling workflows

## Project Structure

```
audio/          # Generated narration audio
chunks/         # Scroll chunks and intermediate images
clips/          # Individual video clips
image_audio/    # Audio mapped to panels
panels/         # Source webtoon panels
script.json     # Dialogue and narration script
```

## Outputs

- `chapter_final.mp4` – Final motion comic
- `exp1_pause_scroll.mp4` – Pause-scroll experiment
- `exp1_synced.mp4` – Audio synchronized version
- `scroll_test.mp4` – Scroll effect test

## Workflow

1. Load webtoon panels
2. Generate narration audio
3. Create panel clips
4. Synchronize audio and visuals
5. Render final video

## Future Improvements

- OCR-based dialogue extraction
- Automatic subtitle generation
- Character voice assignment
- AI camera movements
- Background music and sound effects
