## tt06-chip-top

➡️ [View TT06 Microscope Image](https://tinytapeout.github.io/tt06-chip-imaging/#url=data/tt06.json) 
➡️ [View TT06 High Res GDS](https://tinytapeout.github.io/tt06-chip-imaging/#url=data/tt06-highres.json)

GDS and local interconnect (LI) were rendered using [tinytapeout-chip-renders](https://github.com/TinyTapeout/tinytapeout-chip-renders/), at a scale of 1.9, which roughly matches the scale of the microscope image:

```
$ cd tinytapeout-chip-renders/scripts
$ python render.py tt06 --scale 1.9
```

They were then sliced using the [GroupXIV slicer](https://github.com/whitequark/groupXIV).

The high res GDS / LI were rendered with a scale factor of 5.
