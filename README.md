# dora-openarm-dummy-camera

A [dora-rs](https://dora-rs.ai/) node that mimics camera for testing.

## Options

| CLI flag | Environment variable | Default | Description |
|---|---|---|---|
| `--encoding` | `ENCODING` | `jpeg` | Output encoding (`jpeg`, `jpg`, `jpe`, `bmp`, `webp`, `png`, `rgb8`, `yuv420`) |
| `--image-width` | `IMAGE_WIDTH` | `960` | Width of the output image in pixels |
| `--image-height` | `IMAGE_HEIGHT` | `600` | Height of the output image in pixels |
| `--jpeg-quality` | `JPEG_QUALITY` | `95` | JPEG quality (0–100) |
| `--pattern` | `PATTERN` | `random` | Image pattern to output (`random`, `ball`) |

### Patterns

- **random** – each frame is filled with random RGB noise.
- **ball** – a white ball bounces around a black background across frames.

## License

Licensed under the Apache License 2.0. See [LICENSE](LICENSE) for details.

Copyright 2026 Enactic, Inc.

## Code of Conduct

All participation in the OpenArm project is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).
