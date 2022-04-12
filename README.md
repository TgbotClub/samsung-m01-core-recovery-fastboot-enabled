# samsung-galaxy-m01core-gsi-boot
Script to enable fastbootd on recovery image of Samsung devices launched with Android 10 and above.


## Requirements
`lz4 tar openssl python3`

You can install these packages by executing this command (the script will ask for `sudo` permission):
```bash
./setup.sh
```
## Usage

After cloning this repo, place your `recovery.img` or `recovery.img.lz4` extracted from your stock Samsung firmware in the created directory and execute this command:
```bash
./run.sh
```
## Output

```bash
output
├── fastbootd-recovery.tar
└── recovery.img
```
After `run.sh` is executed, in the generated `output` directory, you will have a file called `fastbootd-recovery.tar` which can be used to flash in AP section of Odin and the patched `recovery.img`





Copy of https://github.com/thongass000/samsung-galaxy-a51-gsi-boot
