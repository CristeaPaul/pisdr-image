<p align="center">
    <h1 align="center">PiSDR</h1>
    <p align="center">The SDR Linux Distro for Raspberry Pi</p>
    <p align="center"><strong><a href="https://pisdr.luigifreitas.me/index">Download and Documentation</a></strong></p>
</p>

### Known Issues

#### Global [#9](https://github.com/luigifreitas/pisdr-image/issues/9)
| Status | Text |
|:-----------|:---------------------------------------------------|
| *Behavior:* | Image can't be decompressed on macOS. |
| *Affected:* | All |
| *Fix:* | Try to decompress the file with [The Unarchiver](https://theunarchiver.com/) instead. |

#### LimeSuite [#6](https://github.com/luigifreitas/pisdr-image/issues/6)
| Status | Text |
|:-----------|:---------------------------------------------------|
| *Behavior:* | Message `Illegal instruction` is thrown on startup. |
| *Affected:* | RPi 1, 2 and 3. |
| *Fix:* | Recompile the LimeSuite. |
