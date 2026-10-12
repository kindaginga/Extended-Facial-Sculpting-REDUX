# Extended Facial Sculpting REDUX

A Fallout 4 mod. Extended and additional facial sculpts for the face editor (Plastic Surgery and LooksMenu), as two plain-text data files per sex, with an optional single-side set for the eyebrows, mouth sides and mouth corners.

Released on Nexus Mods by [kindaginga](https://www.nexusmods.com/profile/kindaginga/mods).

## Layout

| Folder | What it is |
|---|---|
| `normal/` | The default sculpt set, `female/` and `male/`, each with the bone regions file and the UI remapping file |
| `sside/` | The same plus the single-side sculpts |
| `fomod/` | The installer: configuration, sex, and the LooksMenu List Sculpt Fix as a recommended option |
| `docs/` | `Sculpt_Format.txt`, the format of the two data files |

The two files go to `Data\meshes\actors\character\characterassets`.

The LooksMenu List Sculpt Fix that the installer offers (`looksmenu_fix\Interface\LooksMenu.swf`, LooksMenu's interface file with the one call that makes list picks editable) is not in this repository, because that file is expired6978's; it ships only in the mod archive on Nexus Mods.

## Notes

- Male extended sculpts use new IDs in this version. Presets made with the original mod or Scrithel's edition keep their look under the EFS Preset Converter plugin.
- Do extended sculpting outside the pre-war mirror (`slm 14`), which gives Nate and Nora the same list.

## License

All rights reserved. See `LICENSE`. LooksMenu is by expired6978.
