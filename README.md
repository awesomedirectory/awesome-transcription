# Awesome Transcription [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of speech-to-text tools — desktop apps, APIs, open-source models, and services for turning audio and video into usable text.

Whisper changed what transcription costs and what it can do. This list covers the local apps built on top of it, the hosted APIs that scale past a laptop, the open-source models underneath, and the editor-first tools that treat the transcript as the timeline.

## Contents

- [Open Source Models & Libraries](#open-source-models--libraries)
- [Desktop Apps](#desktop-apps)
- [Web Apps & Services](#web-apps--services)
- [Speech-to-Text APIs](#speech-to-text-apis)
- [Meeting Recorders & Notetakers](#meeting-recorders--notetakers)
- [Subtitling & Video Editing](#subtitling--video-editing)
- [Benchmarks & Reading](#benchmarks--reading)
- [Contributing](#contributing)

---

## Open Source Models & Libraries
*The models most of this list is built on.*

* [faster-whisper](https://github.com/SYSTRAN/faster-whisper) - Reimplementation of Whisper using CTranslate2, substantially faster with lower memory use.
* [NVIDIA NeMo](https://github.com/NVIDIA/NeMo) - Toolkit including Parakeet and Canary ASR models that top several accuracy leaderboards.
* [Vosk](https://alphacephei.com/vosk/) - Lightweight offline speech recognition supporting many languages on modest hardware.
* [whisper.cpp](https://github.com/ggerganov/whisper.cpp) - Plain C/C++ port of Whisper that runs efficiently on CPU and Apple Silicon.
* [Whisper](https://github.com/openai/whisper) - OpenAI's open-source multilingual speech recognition model, the basis for much of this category.
* [WhisperX](https://github.com/m-bain/whisperX) - Whisper with forced alignment for accurate word-level timestamps and speaker diarization.

## Desktop Apps
*Local-first transcription without uploading your audio anywhere.*

* [Aiko](https://sindresorhus.com/aiko) - Free Mac and iOS transcription app running Whisper entirely on-device.
* [Hello Transcribe](https://www.hellotranscribe.com) - On-device transcription for iOS and macOS with no server round-trip.
* [MacWhisper](https://goodsnooze.gumroad.com/l/macwhisper) - The most widely used Mac Whisper front-end, with batch processing, diarization, and subtitle export.
* [Superwhisper](https://superwhisper.com) - Mac dictation and transcription app focused on voice-driven text input across applications.
* [Vibe](https://thewh1teagle.github.io/vibe/) - Open-source cross-platform transcription app for macOS, Windows, and Linux.

## Web Apps & Services
*Upload a file, get a transcript, no install.*

* [Happy Scribe](https://www.happyscribe.com) - Transcription and subtitling with a human-review tier, aimed at media and research teams.
 * [Longscribe](https://longscribe.com) - Free transcription for long audio, video and podcasts up to 500 MB, with timestamps and TXT, SRT, DOCX or JSON export.
* [Rev](https://www.rev.com) - Long-running service offering both automated and human transcription with accuracy guarantees.
* [Sonix](https://sonix.ai) - Automated transcription with in-browser editing, translation, and publishing workflows.
* [TranscribeAnything](https://transcribeanything.app) - Browser-based transcription in 100+ languages with speaker detection and word-level timestamps. Accepts MP3, WAV, MP4, MOV, WebM and YouTube URLs; exports TXT, SRT, VTT, and JSON. No account required.
* [Trint](https://trint.com) - Transcription platform built around a collaborative editor, used heavily in newsrooms.
* [TurboScribe](https://turboscribe.ai) - High-volume transcription service with generous file-length limits.

## Speech-to-Text APIs
*For putting transcription inside your own product.*

* [AssemblyAI](https://www.assemblyai.com) - Speech-to-text API with diarization, summarization, and content-moderation models.
* [Azure AI Speech](https://azure.microsoft.com/products/ai-services/ai-speech) - Microsoft's speech service with real-time and batch transcription and custom model training.
* [Deepgram](https://deepgram.com) - Low-latency streaming and batch speech-to-text API with domain-tuned models.
* [Google Cloud Speech-to-Text](https://cloud.google.com/speech-to-text) - Managed ASR across a wide language set with streaming support.
* [OpenAI Audio API](https://platform.openai.com/docs/guides/speech-to-text) - Hosted Whisper and successor models via API.
* [Speechmatics](https://www.speechmatics.com) - Enterprise ASR with strong accent and dialect coverage.

## Meeting Recorders & Notetakers
*Transcription attached to calendars and calls.*

* [Fathom](https://fathom.video) - Meeting recorder with free transcription and automatic summaries.
* [Fireflies.ai](https://fireflies.ai) - Meeting notetaker that joins calls, transcribes, and searches across past meetings.
* [Granola](https://www.granola.ai) - Mac notepad that enhances your own typed notes with meeting audio.
* [Otter.ai](https://otter.ai) - Long-established meeting transcription with live captions and shared notes.

## Subtitling & Video Editing
*Where the transcript is the edit surface.*

* [Descript](https://www.descript.com) - Audio and video editor where cutting the transcript cuts the media.
* [Kapwing](https://www.kapwing.com) - Browser video editor with automatic subtitling and translation.
* [Subtitle Edit](https://www.nikse.dk/subtitleedit) - Free, open-source subtitle editor with waveform sync and format conversion.

## Benchmarks & Reading
*How to tell whether any of this is actually accurate.*

* [Artificial Analysis — Speech to Text](https://artificialanalysis.ai/speech-to-text) - Independent accuracy and price comparisons across ASR providers.
* [Open ASR Leaderboard](https://huggingface.co/spaces/hf-audio/open_asr_leaderboard) - Hugging Face leaderboard ranking open speech recognition models by word error rate.
* [Whisper paper](https://arxiv.org/abs/2212.04356) - "Robust Speech Recognition via Large-Scale Weak Supervision," the original Whisper research.

---

## Related Awesome Lists

- [Awesome PR Tools](https://awesomedirectory.github.io/awesome-pr-tools/) - PR software, journalist databases, media monitoring tools, and outreach platforms for founders and comms teams.
- [Awesome Founder Stack](https://awesomedirectory.github.io/awesome-founder-stack/) - Tools, services, and SaaS for startup founders — incorporation, finance, hiring, and growth.
- [Awesome Private Practice](https://awesomedirectory.github.io/awesome-private-practice/) - Practice management, billing, scheduling, documentation, and marketing tools for therapists, counselors, and small clinical practices.
- [Awesome Tech Sales](https://awesomedirectory.github.io/awesome-tech-sales/) - Tools, contact databases, and resources for selling SaaS and infrastructure to engineering, IT, and tech-leadership buyers.
- [Awesome B2B Prospecting](https://awesomedirectory.github.io/awesome-b2b-prospecting/) - Contact databases, enrichment tools, sequencers, and deliverability platforms for B2B sales and growth teams.

## Contributing

Built or found a transcription tool that belongs here? See [contributing.md](contributing.md).

Disclosure: this list is maintained by [Awesome Directory](https://github.com/awesomedirectory), which also builds several of the tools listed. Entries are held to the same criteria regardless of who makes them, and directly competing products are listed alongside.

## License

[CC0 1.0 Universal](LICENSE) — public domain dedication.
