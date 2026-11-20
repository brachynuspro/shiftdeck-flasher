# ShiftDeck · Instalador web

Página que grava o firmware do ShiftDeck no ESP32-2432S028 (Cheap Yellow Display) pelo navegador, usando [ESP Web Tools](https://esphome.github.io/esp-web-tools/).

Abra a página publicada (GitHub Pages deste repositório) no Chrome ou Edge de um computador e siga os 3 passos.

- **Atualizar**: mantém Wi-Fi, conta do Spotify e calibração (deixe “Erase device” desmarcado).
- **Instalar do zero**: apaga tudo e volta para a configuração inicial.

Este repositório contém só o instalador e o firmware compilado (`firmware/shiftdeck.bin`, imagem única gravada no endereço 0x0). Ele é gerado por `tools/release.sh --publish` no repositório do código.
