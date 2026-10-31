# 3D Graphics & Technical Art Portfolio | CD Projekt Red Scholarship Application

Witaj w moim repozytorium stypendialnym! Znajdziesz tu moje projekty 3D skupione wokół stylizowanego renderowania, proceduralnego tworzenia materiałów oraz przygotowywania zasobów pod kątem gier wideo.

---

## 🐴 Projekt 1: Ethereal Holographic Horse (Procedural Shader Setup)

Zaawansowany shader oparty w pełni na węzłach proceduralnych i mapach nakładanych warstwowo w Blenderze.

### 🛠️ Kwestie Techniczne & Workflow:
* **Proceduralny Noise & Voronoi (4D):** Zastosowanie węzłów *Noise Texture* oraz *Voronoi Texture* w trybie 4D, napędzanych wspólną wartością czasową/zmienną (`Value`), co pozwala płynnie animować strukturę materiału.
* **Mieszanie warstw (Multiply & Bump):** Łączenie tekstury obrazu z proceduralnym wzorem szumu za pomocą węzła *Multiply* oraz generowanie dynamicznej wypukłości siatki za pomocą wejścia *Bump*.
* **Zaawansowana Emisja i Alpha:** Wykorzystanie wysokiej siły świecenia (*Emission Strength: 100.0*) połączonej z kontrolowaną przezroczystością (*Alpha: 0.400*), co nadaje modelowi głębię i efekt holograficzny.
* **Render i Przenośność:** Eksport animacji w wysokiej jakości (H.264, Perceptually Lossless) z pełnym spakowaniem zasobów w pliku `.blend` (rozmiar ~5 MB).

---

## ⚔️ Projekt 2: Stylized Fire-Flow Sword (W trakcie realizacji)

* **Status:** Prace nad shaderem przepływu ognia na ostrzu (PBR Material + Procedural Emissive Flow).
* **Elementy:** Połączone mapy PBR (Base Color, Metallic, Roughness, Normal OpenGL) wzbogacane o animowany moduł emisji światła[cite: 3].

---

## 📂 Jak uruchomić projekty?
1. Pobierz plik `.blend` z repozytorium.
2. Otwórz w programie Blender (wersja 4.x lub nowsza).
3. Wszystkie tekstury i zasoby są spakowane wewnątrz pliku, projekt uruchomi się poprawnie bez utraty ścieżek.
