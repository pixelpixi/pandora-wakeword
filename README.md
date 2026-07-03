# pandora-wakeword
Custom microWakeWord model for the wake word "Pandora" (ESP32-S3 / ESPHome).

Use in ESPHome:

    micro_wake_word:
      models:
        - model: https://raw.githubusercontent.com/pixelpixi/pandora-wakeword/main/pandora.json
          id: pandora
