# image
A minimal image processing library for [Fireball](https://github.com/fireball-lang/fireball).

## Pixel formats
- **R8** - single component, 1 byte
- **RG8** - two components, 2 bytes
- **RGB8** - three components, 3 bytes
- **RGBA8** - four components, 4 bytes

## File formats
- **BMP** - `RG8` is automatically converted to `RGB8` when writing.
- **QOI** - `R8` and `RG8` are automatically converted to `RGB8` when writing.
