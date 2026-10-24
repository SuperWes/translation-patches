# SuperWes Translation Patches

English fan translation patches for **Be-Bop High School** and **Sailor Moon S: Kondo wa Puzzle de Oshioki yo!!** Both releases are **v1.0**.

[Read the project story and see screenshots on SuperWes.com](https://superwes.com/be-bop-high-school-and-sailor-moon-english-translation-patches/).

## Downloads

| Game | System | Version | Download |
| --- | --- | --- | --- |
| Be-Bop High School | Famicom / NES | 1.0 | [Be-Bop-English-v1.0.zip](https://github.com/SuperWes/translation-patches/releases/download/v1.0/Be-Bop-English-v1.0.zip) |
| Sailor Moon S: Kondo wa Puzzle de Oshioki yo!! | Super Famicom / SNES | 1.0 | [Sailor-Moon-Puzzle-English-v1.0.zip](https://github.com/SuperWes/translation-patches/releases/download/v1.0/Sailor-Moon-Puzzle-English-v1.0.zip) |

Each ZIP contains a **BPS translation patch** and instructions. **Game ROMs are not included.**

## What's translated

- **Be-Bop High School:** dialogue and choices, menus, endings, staff credits, and gameplay/navigation signs, with an English font supporting uppercase and lowercase letters. Decorative labels and the original title artwork remain Japanese.
- **Sailor Moon Puzzle:** game text, menus, options, match results, character victory quotes, endings, credits, and the password interface. Passwords use English letters, numbers, and punctuation; uppercase and lowercase are distinct. A password conversion key is included. Japanese logos and voices remain as originally released.

## Applying a patch

1. Download and extract the ZIP for your game.
2. Use a BPS-compatible patcher to apply the `.bps` file to the matching original Japanese ROM listed below.
3. Save the patched game as a separate file. Apply the patch to the original game, not an earlier translation build.
4. Start the patched game from a fresh boot. Older emulator save states can restore the original fonts or graphics.

| Original Japanese game | Required file size | Source CRC32 |
| --- | --- | --- |
| Be-Bop-Highschool - Koukousei Gokuraku Densetsu (Japan) | 262,160 bytes, including the iNES header | `17D50605` |
| Bishoujo Senshi Sailor Moon S: Kondo wa Puzzle de Oshioki yo!! (Japan) | 524,288 bytes, without a copier header | `10F03E3C` |

The README inside each ZIP contains game-specific instructions and additional checksums.

### Polymega

Place the extracted `.bps` file in a folder named `patch` on a USB drive or SD card. In the installed game's Play menu, choose **Select Patch** and select the appropriate file. The installed game must match the revision required by the patch.

[Official Polymega patch instructions](https://polymega.com/pages/frequently-asked-questions).

## About

Translations by **SuperWes**, created with assistance from **OpenAI Codex**. These are unofficial fan translations.

This repository hosts the release ZIPs and their download guide. The [v1.0 release page](https://github.com/SuperWes/translation-patches/releases/tag/v1.0) provides the same downloads as GitHub release assets.
