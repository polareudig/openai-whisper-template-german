# OpenAI Whisper Transkription Template (Deutsch)

## Projektbeschreibung
Dieses Projekt stellt ein einfaches deutsches Template bereit, um OpenAI Whisper sowohl mit einer CPU als auch einer GPU nutzen zu können, um Transkriptionen zu erstellen. Es enthält separate Jupyter-Notebooks für die CPU- und GPU-Nutzung, sodass die Transkription von Audio flexibel an die vorhandene Hardware angepasst werden kann.

## Anforderungen
- Python 3.x
- OpenAI Whisper
- ffmpeg
- pytorch
- Jupyter Notebook

## Dateien

### CPU-basierte Transkription
Das `template_whisper_cpu.ipynb`-Notebook enthält die Konfiguration für die Nutzung von OpenAI Whisper über die CPU. Dies eignet sich besonders für Umgebungen ohne dedizierte GPU (cuda-fähige Grafikkarte).

### GPU-basierte Transkription
Das `template_whisper_gpu.ipynb`-Notebook ist für die Nutzung einer GPU optimiert und kann deutlich schnellere Transkriptionszeiten liefern, sofern eine kompatible GPU zur Verfügung steht.

### Test Audio
Im Ordner `audio` findest du eine Test-Audiodatei (`test.mp3`), die für die Transkription verwendet werden kann, um die Funktionalität des Templates zu testen.

### Ausgabe
Die transkribierten Dateien werden im Ordner `output` gespeichert. Dort findest du sowohl die Transkripte, die mit der GPU als auch mit der CPU erstellt wurden.

## Nutzung

1. **Repository klonen**:
   ```bash
   git clone https://github.com/polareudig/openai-whisper-template-german
   cd openai-whisper-template-german

## Lizenz


Dieses Projekt steht unter der Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).
