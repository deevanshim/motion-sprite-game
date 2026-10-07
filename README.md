# motion-sprite-game

A motion-controlled balance game. A Raspberry Pi Pico with an MPU-6050 motion sensor is attached to a lightweight object. Tilting the object controls a balance bar in a Pygame game on the laptop. Players can also type a prompt to generate a custom character sprite with an image-generation API, with a library of pre-made sprites as a fallback.

## Project structure

- `firmware/` - MicroPython code that runs on the Pico
- `frontend/` - game, sensor input and UI (Pygame)
- `backend/` - AI image API calls, threading and fallback sprites
- `assets/` - backup and generated sprites
- `docs/` - wiring diagram and event setup guide

## Status

Work in progress.