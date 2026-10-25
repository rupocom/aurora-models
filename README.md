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
