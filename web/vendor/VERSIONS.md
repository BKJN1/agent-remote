# Vendored front-end files

Downloaded from the official npm registry (https://registry.npmjs.org) on 2026-10-28.
Each tarball's sha512 was compared with the `dist.integrity` value published by the
registry before the files were extracted. Source maps are not shipped.

| Package | Version | License | Tarball integrity (registry `dist.integrity`) |
|---|---|---|---|
| `@xterm/xterm` | 6.0.0 | MIT | `sha512-TQwDdQGtwwDt+2cgKDLn0IRaSxYu1tSUjgKarSDkUM0ZNiSRXFpjxEsvc/Zgc5kq5omJ+V0a8/kIM2WD3sMOYg==` |
| `@xterm/addon-fit` | 0.11.0 | MIT | `sha512-jYcgT6xtVYhnhgxh3QgYDnnNMYTcf8ElbxxFzX0IZo+vabQqSPAjC3c1wJrKB5E19VwQei89QCiZZP86DCPF7g==` |

## Files and sha256

| File | Origin | sha256 |
|---|---|---|
| `xterm.js` | `@xterm/xterm@6.0.0` `package/lib/xterm.js` | `14903579ff54664cd72f8e8699e6961a6272c21863ec1c3b118cdc8af5d4a972` |
| `xterm.css` | `@xterm/xterm@6.0.0` `package/css/xterm.css` | `854a7c0fb70e8b1a083c16797ab827299fb18744f5ad34f227b48337e33293c6` |
| `addon-fit.js` | `@xterm/addon-fit@0.11.0` `package/lib/addon-fit.js` | `ba3ea256ce0620a0992a197d6c9baea64823fc93d8da07a9e366ca9943c18527` |
| `LICENSE-xterm` | `@xterm/xterm@6.0.0` `package/LICENSE` | (license text) |

Verify: `sha256sum xterm.js xterm.css addon-fit.js`.

## Fonts (SIL Open Font License 1.1)

Taken from the official npm packages `@fontsource/jetbrains-mono@5.3.0` (terminal, numbers) and `@fontsource/onest@5.3.1` (interface)
(registry `dist.integrity` compared with the downloaded tarballs on 2026-10-29). Only the `latin` and `cyrillic`
subsets of the listed weights are bundled. Licence texts: `fonts/LICENSE-*.txt`.

| File | sha256 |
|---|---|
| `fonts/jetbrains-mono-cyrillic-400-normal.woff2` | `522f5827308102a9c0ea7860b5a11306043610ecf03d150ba32056a06e8c56e2` |
| `fonts/jetbrains-mono-cyrillic-500-normal.woff2` | `26c9ed511def1f0fd3d1b5fe6d5c0c594d9ef8dd2435d2ff240ea265a416b6e4` |
| `fonts/jetbrains-mono-cyrillic-700-normal.woff2` | `6251ef44d6390a4f0622432eb852864af90dd1b8310d153c3c6d235e0c412570` |
| `fonts/jetbrains-mono-latin-400-normal.woff2` | `14425ba9c695763c1547f48a206b7aa60350a33ae23de09f0407877f3fcd89eb` |
| `fonts/jetbrains-mono-latin-500-normal.woff2` | `cb182feeed4d798ff6961d3c79f7026279448fca0676438aaecb21f3fc39553a` |
| `fonts/jetbrains-mono-latin-700-normal.woff2` | `d0d4e818808f2a0ba39b2b09d1989366f63494e295f003c7ef436697378507e8` |
| `fonts/onest-cyrillic-400-normal.woff2` | `51adb4c8c5dc00b8a1974b32754665e5cc7522de621fdd3cb233e6834d98b480` |
| `fonts/onest-cyrillic-500-normal.woff2` | `a345dcbda6c18991c6efeebce60452eae57c29d5f659e0a1d8b615fb49808c49` |
| `fonts/onest-cyrillic-600-normal.woff2` | `73984d20ad8db2d013e42e345c3d9cf92192677f3a3b12e57b15d767ccf9f957` |
| `fonts/onest-cyrillic-700-normal.woff2` | `0fcb8fa2565065c753c08d487b8208914323cd40a92c05e1306ea74953ddaa5e` |
| `fonts/onest-latin-400-normal.woff2` | `93dfb945d217bb541c46e5cdef85bb86095009522fcede783215827e7ca14439` |
| `fonts/onest-latin-500-normal.woff2` | `83c1e1616618edcbcf5aa77155d4e4aa3b84d772df33fb4f2f10fba919d863f3` |
| `fonts/onest-latin-600-normal.woff2` | `a56e6d2dcc2d24fe160cbc8c08adbca5a9da776237460704f6f24e1b5f7cba36` |
| `fonts/onest-latin-700-normal.woff2` | `d48e1aee8027a82b7b156b734ff2efa1e8839e4365a305f0323f5e0b41a230fb` |
