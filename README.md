## Hacky Home assistant support for Xiaomi vacuum STYJ02YM

_Original code by [@nqkdev](https://github.com/nqkdev/home-assistant-vacuum-styj02ym), forked to [@KrzysztofHajdamowicz](https://github.com/KrzysztofHajdamowicz/home-assistant-vacuum-styj02ym) and then by myself._  
_I have added some additional files customized for my usage._
_I have no Python or HA integration writing knowledge, just maintaining this for my own purpose. Use on your own risk._


### This is for STYJ02YM (apparently EU version) working with my firmware version 3.5.8_0021 

#### Install

- Install it with HACS
- Add the configuration to configuration.yaml, example:

#### Usage

Add to `configuration.yaml`:

```yaml
vacuum:
  - platform: miio2
    host: 192.168.68.105
    token: !secret vacuum
    name: Mi hihi
```
