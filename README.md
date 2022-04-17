# go-file-dedupe

**DISCLAIMER:
You assume full responsibility when running this program. I am not responsibile for any intentional / accidental data loss.
This software also has no concept of which file is the "original". It may not find your files in order, so it may delete one from the folder you're familiar with it in. If you have a preference for maintaining file location for the "original" file, then you shouldn't use this software.**

## What does this software do?
Recursively search and remove duplicate files from the binary's working directory. Uses sha256 to hash files and detect dupes. 

In personal testing it removed 16470 duplicate files from a 150GB pool (on an HDD) of files in the span of ~30 minutes.

## Example output
![dedupe cli output](dedupe-dialog.png)
