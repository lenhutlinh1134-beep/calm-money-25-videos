# Production Folder Structure

## 01_IMAGES/ (AI Image Generation)
Each Video_XX folder contains:
- AI_PROMPTS.txt - All 8 scene prompts compiled
- SCENE_01.txt through SCENE_08.txt - Individual scene prompts
- images/ (after generation) - Generated PNG files

## 02_AUDIO/ (Voiceover Generation)
Each Video_XX folder contains:
- VOICEOVER_FULL.txt - Complete voiceover script
- SECTION_01.txt through SECTION_08.txt - Individual sections for voiceover
- TIMING_MAP.txt - Scene-to-audio timing alignment
- audio/ (after generation) - Generated audio files (MP3/WAV)

## Workflow:
1. Extract 8 Scene Prompts from each video script
2. Generate images using Midjourney/Leonardo for each prompt
3. Extract 8 Voiceover sections from each video script
4. Generate voiceovers using ElevenLabs (Adam voice, calm male tone)
5. Edit videos: Sync 8 images + 8 audio sections per video
6. Add transitions, effects, subtitles
7. Upload to YouTube per schedule
