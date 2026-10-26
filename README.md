# Aurora model library

Compiled player-model resources for Aurora. The catalog lists relative resource paths, byte sizes and SHA-256 hashes. Aurora downloads these files on request and caches them locally for offline use.

## Install through Aurora

Open Visuals > Models > Online model library, refresh, then download the model. Select it from Player model after installation. Use compatible current CS2 player rigs.

## Included pack

2B Nier Automata (AG2), from the locally supplied converted model pack. The supplied asset paths use the nozb1 namespace. Standard CS2 animation graphs and skeletons come from the installed game.

Additional supplied Workshop models: Aositala, Megumin, Yidhari and Nano Girl. Their resources reference AG2 graphs, but their appearance and behavior have not been verified in Aurora. The catalog labels them untested. The original authored simulation data is preserved: Aositala has 18 simulation nodes, Megumin 19, Yidhari 34 and Nano Girl none. This metadata does not prove that cloth simulates correctly in-game.

Older AG1 models and Blender source projects are not listed as ready player models. They require conversion or retargeting first.

Model artwork and associated rights remain with their respective creators and rights holders; no new license is asserted for these supplied assets.


## Skybox

Wallhaven g8x19q is included as a compiled Source 2 skybox pack. Download the [skybox release](https://github.com/rupocom/aurora-models/releases/tag/skybox-wallhaven-g8x19q) for the installable archive and preview. The current Aurora DLL also embeds this preset.

The [skybox catalog](skyboxes/catalog.json) additionally lists Wallhaven, Windowlight, Daybreak, Twin Mischief, Velvet Dusk and Neon Temptress with compiled resource paths and checksums. Copy the selected pack's `materials` folder into `game/csgo` and use its material path in the custom compiled sky setting.

## LynX AG2 additions

Ten player models: Hel, Kuramitsuha, Skadi, Pathfinder, Exusiai, Lappland, Chen Qianyu, Endministrator, Laevatain and Perlica. Each entry includes its full custom resource dependency closure with SHA-256 checksums; stock animation graphs and skeletons are supplied by CS2. All extracted resource CRCs were checked against the supplied archive. Appearance, hitboxes and cloth behavior remain unverified in game. Original artwork remains owned by its creators.

## Authored jiggle simulation candidates

Nicole, Lila Decyrus and Rapi from the supplied LynX AG2 archive are available through the online library. They contain 17, 17 and 7 simulation nodes respectively, including a `jiggle_primary` bone parented to `spine_3`. The original simulation and mesh data are preserved. This is evidence of authored upper-body jiggle support; visible chest motion has not been verified in Aurora. See `physics-audit.json` for the asset audit.

Every custom dependency was checked against the supplied archive CRC and is listed with its byte size and SHA-256 checksum. Stock AG2 animation graphs and skeletons are supplied by the game. The older AG1 Adult Neptune and Nicole resources were excluded because their animation graph dependency is absent from the current game index. The published Nicole entry uses the separate AG2 resource in `agents/models/hmn_ag2/zenless_zone_zero/nico`.
