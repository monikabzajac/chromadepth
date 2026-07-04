# ChromaDepth Mandala Generator

Generator generative art pod okulary ChromaDepth. Animowane, symetryczne mandale z linii w czystych barwach spektralnych (czerwień = blisko, błękit = daleko), na czarnym tle. Narzędzie do seryjnego produkowania filmików.

## Uruchomienie

To jeden samowystarczalny plik — `index.html`. Wystarczy otworzyć go w przeglądarce (Chrome/Edge/Firefox). Działa offline, bez serwera i bez instalacji.

## Obsługa

- 🎲 **Nowa mandala** / klawisz **N** — losowy seed
- pole **seed** + **Zastosuj** — powtórzenie konkretnej mandali (działa też przez URL `?seed=...`)
- **rozdzielczość** — 1920×1080 / 1080×1080 / 1080×1920
- **⏺ Nagraj WebM** — nagrywa 5–60 s (60 fps) i pobiera plik wideo
- **PNG** — zapis pojedynczej klatki
- suwaki: **ekspansja** (tempo rozszerzania), **przejście** (długość crossfade między mandalami), **gęstość** (liczba linii)
- **spacja** — pauza

> Uwaga: podczas nagrywania WebM okno musi być widoczne — ukryta karta wstrzymuje klatki.
