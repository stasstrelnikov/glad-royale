# Глад Рояль

Fan reference pack for a Clash Royale-style game about the Glad Valakas streams. The streamer and Supercell are not involved.

The deliverable is `glad_royale_assets.zip` (under 8 MB). The same folders are also unpacked next to the zip.

```
glad_royale_assets.zip
  audio/          original voice clips (MP3, mono, 44.1 kHz, 112 kbps)
  images/         real thumbnails and meme stills for drawing the cast
  generated/      chibi cards, sprites, props, towers, emote stickers
  manifest.json   sources, timestamps, transcripts, character notes
```

## Use it

```bash
unzip glad_royale_assets.zip -d glad_royale
```

Open `manifest.json` before attaching a clip to a card. Each audio entry has the Cyrillic transcript, the speaker, the source URL, and a start–end time. Each image entry has its source URL. Generated art lists the prompt and the reference stills it was drawn from.

Anything that could not be found for real is under `missing`, with what was tried. Those files were not renamed to look like a hit. In particular there is no clean isolated take of «Ля, а шо?» or of the a cappella «Тупо отдыхаю» hook, and no Denchik or tanker voice that is not Glad himself.

## What is real, and what is drawn

Audio is original stream audio and two short donation screams from the CC-BY-4.0 [gadzas-online-open-api](https://github.com/VityaSchel/gadzas-online-open-api) pack. Nothing was re-voiced.

The Glad photos are the public meme avatar (a widely circulated crop, ears often exaggerated), not a photograph of the streamer. Valera uses that same face because he is the same persona. Svetlana and Denchik have no verified photos; their pictures are role designs. Bogdan is Glad's pitched-up voice, drawn as the same adult face in a blue hoodie.

Cards and emote stickers that would not fit under 300 KB were scaled below 1024 px. Sprites are 1024 px tall, with a transparent background.
