# Reclass-2015

ReClass 2015

(From dude719)

Cleaned up the code a bit and added some new features. Also got rid of a ton of bugs still crawling around.

New features include:
- Up and down arrow hotkeys to switch nodes
- Delete hotkey to delete selected nodes
- Delete button to delete selected nodes
- Right click quick modify menu
- Hex 64 type
- Insert 2048 bytes
- New icons for some types


(from leveln)

1. [BUG] The enum of types was reorganized in 2015, which breaks importing previous .reclass files. It has been fixed.
2. [FEATURE] Added back hex8/int8 -- Makes the UI look not as nice, but these are used far too often.
3. [FEATURE] The attached solution is also converted for VS2013/15. Won't work in VS2010 (too old!).

Note: [BUG] There is an issue with converting 2010 solutions where icons will not work properly in the resource editor until they are upgraded, and that is too much work. Edit the .rc files manually and it will work fine.


TODO (but will probably never be done):

1. [BUG] Updating DWORDs actually updates the uint32 with an int32 value, so large DWORDs are not accepted. Need to fix this BAD! I have been converting to hex32 and adding the bytes manually.
2. [FEATURE] Need a new data type for bits.