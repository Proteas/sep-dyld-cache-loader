# `SEP` Firmware Loader for `IDA`
`IDA` loader for `SEP` firmware with `dyld` cache support.<br/>

1. Install lief version 0.14.1 `pip install lief==0.14.1`
2. Place `sep-fw-dyld-cache-loader.py` into `IDA`'s loader plugin dir.
3. Load the decrypted `SEP` firmware.

# Notes
1. Tested with `IDA` 8.x
2. Sample firmware: [sep-firmware.d37.RELEASE.im4p](https://theapplewiki.com/wiki/Keys:DawnD_21D50_(iPhone15,5))
3. ![Load Results](./img/showcase-1.png)
