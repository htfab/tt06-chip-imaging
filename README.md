## tt06-chip-top

➡️ [View TT06 Microscope Image](https://tinytapeout.github.io/tt06-chip-imaging/#url=data/tt06.json)  

GDS and local interconnect (LI) were rendered using [tinytapeout-chip-renders](https://github.com/TinyTapeout/tinytapeout-chip-renders/) at a scale of 5:

```
$ cd tinytapeout-chip-renders/scripts
$ python render.py tt06 --scale 5
```

They were then sliced using the [GroupXIV slicer](https://github.com/whitequark/groupXIV).
