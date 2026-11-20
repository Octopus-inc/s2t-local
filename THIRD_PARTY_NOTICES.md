# Third-party notices

## Faster-Whisper-XXL / whisper-standalone-win

S2T Local integrates with the external Faster-Whisper-XXL executable maintained by Purfview:

https://github.com/Purfview/whisper-standalone-win

The S2T Local release package does **not** redistribute Faster-Whisper-XXL.
Users obtain it separately from the upstream project.

This separation is intentional until redistribution terms for the standalone
binary and its bundled components are reviewed and documented explicitly.

## FFmpeg

S2T Local can use `ffprobe` / `ffplay` when available. FFmpeg licensing
depends on the build configuration. The FFmpeg project documents LGPL/GPL
requirements here:

https://ffmpeg.org/legal.html

S2T Local does not intentionally bundle an independent FFmpeg distribution in
the v0.1.0 portable package.

## Whisper models and other model assets

Whisper/Faster-Whisper models may be downloaded by the external engine.
Their license and distribution terms are governed by their respective upstream
sources. S2T Local v0.1.0 does not bundle model weights.

## Python runtime dependencies

The Windows portable package is produced with PyInstaller and contains the
Python runtime and Python packages required by S2T Local. Their individual
license notices remain governed by the corresponding upstream projects.
