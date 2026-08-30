# Verba

[![CI](https://github.com/Sam-DarkBall-Mods/Verba/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Verba/actions/workflows/ci.yml)

Verba adds the 9K333 shoulder fired air defence launcher. It includes the 9M336
missile, its magazine, an infrared sensor configuration and the weapon model.

## Requirements

- Arma 3 2.22 or newer

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The existing weapon, magazine and ammunition classes are unchanged. The PBO
continues to use the `verba` prefix.

## License

Code and configs use GPL-2.0-or-later. Original models, textures, animations and
audio use APL-SA. See [LICENSES.md](LICENSES.md).
