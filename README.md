# Reever — языковые пакеты

Архивы моделей распознавания речи, которые скачивает установщик Reever по выбору пользователя.
Файлы лежат в [релизах](../../releases); каждый архив установщик проверяет по SHA-256.

| Архив | Что внутри |
|---|---|
| `reever-parakeet-v3-int4-accurate.tar.bz2` | Parakeet TDT 0.6B v3, 4 бита, точный вариант (европейские языки) |
| `reever-parakeet-v3-int4-light.tar.bz2` | Parakeet TDT 0.6B v3, 4 бита, лёгкий вариант |
| `reever-sense-voice-int4-accurate.tar.bz2` | SenseVoice Small, 4 бита, точный вариант (китайский, японский, корейский) |
| `reever-sense-voice-int4-light.tar.bz2` | SenseVoice Small, 4 бита, лёгкий вариант |

## Лицензии

- **NVIDIA Parakeet TDT 0.6B v3** — Creative Commons Attribution 4.0 International (CC BY 4.0).
  Источник: https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3. Изменения: ONNX-конверсия
  sherpa-onnx, квантование весов до 4 бит.
- **SenseVoice Small** — код MIT (Copyright (c) 2025 FunASR); веса — по лицензии модели
  FunAudioLLM («model-license» в карточке модели). Источник:
  https://huggingface.co/FunAudioLLM/SenseVoiceSmall. Изменения: ONNX-конверсия sherpa-onnx,
  квантование весов до 4 бит.
