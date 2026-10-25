# SuperWes Translation Patches

English fan translation patches for **Be-Bop High School** and **Sailor Moon S: Kondo wa Puzzle de Oshioki yo!!** The latest releases are **Be-Bop v1.0** and **Sailor Moon v1.1**.

[Read the project story and see screenshots on SuperWes.com](https://superwes.com/be-bop-high-school-and-sailor-moon-english-translation-patches/).

## Downloads

| Game | System | Version | Download |
| --- | --- | --- | --- |
| Be-Bop High School | Famicom / NES | 1.0 | [Be-Bop-English-v1.0.zip](https://github.com/SuperWes/translation-patches/releases/download/v1.0/Be-Bop-English-v1.0.zip) |
| Sailor Moon S: Kondo wa Puzzle de Oshioki yo!! | Super Famicom / SNES | 1.1 | [Sailor-Moon-Puzzle-English-v1.1.zip](https://github.com/SuperWes/translation-patches/releases/download/sailor-moon-v1.1/Sailor-Moon-Puzzle-English-v1.1.zip) |

Each ZIP contains a **BPS translation patch** and instructions. **Game ROMs are not included.**

## New in Sailor Moon v1.1

- White SuperWes startup screen with an explicit AI machine-translation disclosure. Release held input, then press and release any Player 1 button to continue; there is no timeout or button prompt.
- Stage results read **STAGE 2 CLEAR**, with the number in the same font as the label. The in-game STAGE label appears above its number; win counters read **W:0**.
- Consistent number fonts and spacing for stage counts, scores, timers, countdowns, and music/sound indices.
- Password data, match rules, and other translation text are unchanged.

Wes successfully playtested v1.1 and reported that it worked fine and seemed better. Reproducible build, BPS application, startup controls, numeric layout, and password checks also pass. See TESTING.txt in the ZIP for coverage and limitations.

[Read the Sailor Moon v1.1 release notes](https://github.com/SuperWes/translation-patches/releases/tag/sailor-moon-v1.1). The [original v1.0 release](https://github.com/SuperWes/translation-patches/releases/tag/v1.0) remains available.

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

This repository hosts patch-only release ZIPs and their download guide. The corresponding GitHub releases provide the same ZIPs as downloadable assets.
