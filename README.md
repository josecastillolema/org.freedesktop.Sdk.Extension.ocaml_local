# SDK Extension for OCaml stable

This extension contains various components of the [OCaml](https://ocaml.org/) stable toolchain.

## Debugging

In order to use this extension in flatpak SDK environment you may add all provided tools in your PATH by executing first:
```
source /usr/lib/sdk/ocaml/enable.sh
```

## Development
To use the SDK with your favourite editor:
```
sudo flatpak override --env=FLATPAK_ENABLE_SDK_EXT=* com.visualstudio.code
sudo flatpak override --env=FLATPAK_ENABLE_SDK_EXT=* org.gnu.emacs
```
