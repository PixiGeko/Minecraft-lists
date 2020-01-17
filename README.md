# General informations
Author : PixiGeko </br>
Original idea by Awhikax, from [DataWorld Discord server](https://discord.gg/3gXea6q ).

# How to extract files
1. Download server.jar of the desired version (from [official site]([https://www.minecraft.net/](https://www.minecraft.net/)) to avoid malware). </br>You can also find it in this [github repository](https://github.com/PixiGeko/Minecraft-lists/tree/master/versions/list)
2. Open a bash or command prompt in the directory where server.jar is located
3. run `java -cp server.jar net.minecraft.data.Main --all` (make sure you have Java installed)
  
This will generate the "basic" data files ( = green rectangles in the diagrams below).</br>
"Special" data files ( = red rectangles with rounded corners in the diagrams below) are generated by a personal program.

<i>server.jar download link can be found here : [version_manifest.json](https://launchermeta.mojang.com/mc/game/version_manifest.json) or directly in this [github repository](https://github.com/PixiGeko/Minecraft-lists/blob/master/versions/version_manifest.json) (might not be up-to-date)</i>

# Files generation

## Data files

### From 18w01a to 18w49a
![](https://github.com/PixiGeko/images/blob/master/images/Minecraft%20Datas/extractOld.png)

### Since 18w50a
![](https://github.com/PixiGeko/images/blob/master/images/Minecraft%20Datas/extractNew.png)

## Version files
![](https://github.com/PixiGeko/images/blob/master/images/Minecraft%20Datas/manifest.png)

# Data types
<i>Some descriptions may not be accurate.</i>

| <b>File</b>  | <b>Description</b> |
| ------------- | ------------- |
| activity.txt | Villager activities | 
| biome.txt | Biome IDs | 
| biome_source_type.txt | Biome types (buffets) | 
| block.txt | Block IDs | 
| block_entity_type.txt | Block entities IDs | 
| block_placer_type.txt |  |
| block_state_provider_type.txt |  |
| carver.txt | Cave types | 
| chunk_generator_type.txt | Map generation types | 
| chunk_status.txt | Chunk generation steps (?) | 
| commands.txt | Commands | 
| custom_stats.txt | Stats | 
| decorator.txt |  | 
| dimension_type.txt | Dimension IDs | 
| enchantment.txt | Enchantment IDs | 
| entity_type.txt | Entity IDs | 
| feature.txt | Structures list (trees, lakes, ores, "normal" structures) | 
| fluid.txt | Fluid IDs | 
| foliage_placer_type.txt | Foliage types |
| item.txt | Item IDs | 
| memory_module_type.txt | PNJ memory informations  | 
| menu.txt | GUI types | 
| mob_effect.txt | Mob effect IDs | 
| motive.txt | Paintings list | 
| particle_type.txt | Particle IDs | 
| point_of_interest_type.txt | Important places in villages  | 
| potion.txt | Potion IDs | 
| recipe_serializer.txt | Craft types | 
| recipe_type.txt | Recipe types | 
| rule_test.txt |  | 
| schedule.txt |  | 
| sensor_type.txt | Villager interactions with environment | 
| sound_event.txt | Sound IDs | 
| stat_type.txt | Stat types | 
| structure_feature.txt | "Normal" structures | 
| structure_piece.txt | Structure pieces | 
| structure_pool_element.txt |  | 
| structure_processor.txt |  | 
| surface_builder.txt |  |
| tree_decorator_type | Tree decorations | 
| villager_profession.txt | Villager professions | 
| villager_type.txt | Villager types (biomes) | 