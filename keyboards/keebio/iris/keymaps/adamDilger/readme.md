# adamDilger iris keymap


## Set defaults

```sh
qmk config user.keyboard=keebio/iris/rev2
qmk config user.keymap=adamDilger
```

## Flash

```sh
# if the above defaults are set:
qmk compile
qmk flash

# otherwise
qmk compile -kb keebio/iris/rev2 -km adamDilger
qmk flash -kb keebio/iris/rev2 -km adamDilger
```

