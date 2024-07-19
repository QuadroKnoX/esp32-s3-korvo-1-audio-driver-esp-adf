Fix for esphome based on this PR: https://github.com/espressif/esp-adf/pull/1113

Use it like this:

```yaml
esp32:
  ...
  framework:
    ...
    components:
      - name: esp32s3korvo1-audio-driver
        source: github://QuadroKnoX/esp32-s3-korvo-1-audio-driver-esp-adf@2.5
        refresh: 0s
```
