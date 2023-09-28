# nls-emu
An attempt at emulating Douglas Engelbart's oN-Line System, or NLS, as famously demonstrated in the 1968 "Mother of All Demos". This project will be using the Dec. (?) 1969 [NLS source code](https://bitsavers.org/pdf/sri/arc/sds-940/NLS_Sources_Part_1_Nov69.pdf), the [Jan. 1972 source code](https://www.computerhistory.org/collections/catalog/102706982), an [SDS 940 emulator](https://github.com/simh/simh), and the [TREE-META compiler-compiler system](https://en.wikipedia.org/wiki/TREE-META) (source/assembly code [here](https://github.com/jimwhite/treemeta)).

# Notes

Some code/documents in the supposed Nov. 1969 NLS source code actually date to Dec. 1969 (see pgs. 84 and 105 of the PDF). Additionally, there are instances of duplicates/revised code being included along with the older code (see pgs. 105 and 107 of the PDF).

# TLTD (Things Left To Do):

Absolutely everything.

In chronological order:
- Clean up and reformat the PDF scans of the source code.
- Check whether the source code contains all necessary code to even begin restoring the system. If not, attempt to restore missing code via [later source code](https://www.computerhistory.org/collections/catalog/102706982).
- Check whether the [TREE-META assembly code](https://github.com/jimwhite/treemeta/blob/master/rulifson-1968/tree-meta.a) is functional/emulatable.
- Get the TREE-META compiler running on the SDS 940 emulator.
- Locate more information on M(achine)O(riented)L(anguage)-940. See pgs. 105-6 in 1969 NLS source code PDF; also see [here](http://bitsavers.trailing-edge.com/pdf/sri/arc/rulifson/MOL940_Preliminary_Specification_For_An_Algol-Like_Machine_Oriented_Language_For_The_SDS_940_Mar68.pdf).
- Get MOL-940/a recreation of it running on the SDS 940 emulator.
- See which parts of the NLS source code are duplicates/later revisions and should be discarded. See [Notes](https://github.com/artech-dvd/nls-emu/edit/main/README.md#notes).
- Figure out a way of emulating the mouse and display that the NLS used.
- Get the NLS system up and running on the SDS 940 emulator.

# Help Needed!
This project's goal will most likely be very difficult, if not impossible, to fully achieve. However, armed with the NLS source code, SDS 940 emulator, and  TREE-META, it might be possible to restore a(n at least partially) working, albeit most likely very limited, version of the oN-Line System.

So, we need any help we can get! If you have any knowledge of OCR, the SDS 940, TREE-MESA, or even the NLS, please let me know at retroperson3782@gmail.com!
