# ChromaDepth Studio

Kolekcja animacji generative art pod okulary ChromaDepth — czyste barwy spektralne na czarnym tle (czerwień = blisko, błękit = daleko). Narzędzie do seryjnego produkowania filmików.

**Live:** https://chromadepth-liard.vercel.app

## Strony

- `index.html` — menu / galeria animacji
- `mandala.html` — **Mandala**: symetryczne, morfujące linie (pierścienie, meandry, grzebienie), ekspansja od środka, płynne przejścia między seedami
- `tunel.html` — **Tunel**: lot przez nieskończony neonowy wormhole; kolor = głębia, zmieniające się „rozdziały" kształtów, helisa żeber, pulsująca fala światła

Kolejne animacje dochodzą jako nowe pliki `*.html` + kafelek w menu.

## Uruchomienie

Statyczne pliki bez zależności — wystarczy otworzyć `index.html` w przeglądarce (Chrome/Edge/Firefox). Działa offline.

## Obsługa (wspólna dla animacji)

- 🎲 / klawisz **N** — losowy seed; pole **seed** + **Zastosuj** — powtórka konkretnej sceny (też URL `?seed=...`)
- **rozdzielczość** — 1920×1080 / 1080×1080 / 1080×1920
- **⏺ Nagraj WebM** — 5–60 s w 60 fps, plik pobiera się sam; **PNG** — zapis klatki
- suwaki parametrów (ekspansja/przejście/gęstość w mandali; tempo/skręt/gęstość w tunelu)
- **spacja** — pauza; **☰** — powrót do menu

> Uwaga: podczas nagrywania WebM okno musi być widoczne — ukryta karta wstrzymuje klatki.
