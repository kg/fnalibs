This is fnalibs, an archive containing the native libraries used by FNA.

These are the folders included:

- x86: 32-bit Windows
- x64: 64-bit Windows
- lib64: Linux (64-bit only)

The library dependency list is as follows:

- SDL3, used as the platform layer
- FNA3D, used in the Graphics namespace
- FAudio, used in the Audio/Media namespaces
- libtheorafile, only used for VideoPlayer

For Linux, the minimum OS requirement is glibc 2.28.
