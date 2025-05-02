# What is this?
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

This is a clone of the core ollama integration in home assistant that removes think tags. Home Assistant maintainers might have other ideas about how think tags should be handled, but as a quick fix, this integration simply discards them.

It uses the same domain as the built-in integration, so it will replace it. All of your models and settings _should_ be maintained.

## Installation
### HACS

1. Add this repository to HACS *AS A CUSTOM REPOSITORY*.
2. Search for *Ollama*, and choose install.
3. Reboot Home Assistant and configure from the "Add Integration" flow.