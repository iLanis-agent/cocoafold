# Cocoafold 1.0 TEST
Native Android Double Choco congruent-half partition puzzle. Android8+ (min26), target35. Package com.gg007.cocoafold.

## Rules
Double Choco: divide every cell into blocks by fencing grid edges. Each block contains one connected light area and one connected dark area of the same size and shape. Rotations and reflections count. A printed number gives the count of ONE color in its block, half the total. Multiple numbers in a block must agree; blocks with no number are allowed. Colors and numbers never change. No internal fence may split cells still connected around it. Tap thin internal edges to add/remove fences. Undo/reset/next/levels and saved cocoa palette/color marks. Twelve unique 4x3 printed-color layouts and unique partitions.

## Download and status
https://mega.co.nz/#!hVMllApI!nLJf3_N4PKYIIUaWpiAriKczeZyprAp8kAtIjc_qRNY
APK SHA256 96619bca872c39fc4f9ff19633f4807070ca437cd83473d7fb34c0885ae805a3; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Independent connected-set BFS and pivot-transform oracle agrees with production union-find regions and canonical normalized shape transforms on all 1,572,864 fence boards across12levels,49,140 possible region masks and120,000 invalid/random states. Each puzzle has exactly one partition; all12color layouts and solution partitions are distinct. Actual archived connected-subset exact-cover generator reproduces levels.json and archived Java exhaustive tests pass. Solve lock, bounds, solve/undo/replay/reset pass. Drawing-adapter actual edge taps, ignored cell centers, undo/reset/next/levels/menu/settings/privacy and saved palette/color marks/completion checks pass. Actual game/solved/menu/settings/privacy/levels drawing pixels inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live803-entry registry,126 recovered partial READMEs and semantic review of all152 prior studio cards found no Double Choco match. Cedarclone shades two matching shapes inside predefined rooms; Brewbranch links circles into equal-color groups around gray anchors. Cocoafold instead partitions fixed printed colors into paired connected congruent halves with half-area clues. Known Double Choco genre from Nikoli, not a global invention; recovered corpus is partial. Rules https://www.nikoli.co.jp/en/puzzles/double_choco/ https://www.theguardian.com/science/2020/apr/06/can-you-solve-it-double-chocolate https://www.atlasobscura.com/articles/double-choco-nikoli-puzzle https://www.cross-plus-a.com/html/cros7dbch.htm https://wpcunofficial.miraheze.org/wiki/Double_Choco .

## Build
JDK17 and AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds generated printed colors/numbers/partitions. javac -d /tmp/cocoa-test src/com/gg007/cocoafold/Board.java BoardTest.java and java -cp /tmp/cocoa-test com.gg007.cocoafold.BoardTest. bash build.sh creates an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Cocoafold runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Cocoa palette, color marks and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/4531pppeupw3-cocoafold-source-archive, including exact cumulative153-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/cocoafold holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November7,2026.
