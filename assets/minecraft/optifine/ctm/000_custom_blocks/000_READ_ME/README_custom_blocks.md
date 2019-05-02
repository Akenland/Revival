This part of the pack includes custom blocks!


# Requirements to see custom blocks
- Minecraft 1.13+
- OptiFine
- CTM enabled


# Instructions for placing blocks
To use these blocks in-game, take any of the following blocks:
- barrel
- blast_furnace
- dispenser
- dropper
- enchanting_table
- furnace
- smoker

Rename the block (using an anvil, or any NBT/tile entity editor) to "revival:name_of_custom_block".

For example, if you want to use black stone bricks, put any block above (like a furnace) into an anvil, enter "revival:black_stone_bricks" as the name, and then place the newly-named furnace. It will have the custom texture.


# Instructions for adding blocks
Use the custom_template.properties file as a starting point. Just add your block name to the file, where specified.

The file is a standard OptiFine CTM file, and fully supports random textures and CTM, which is documented here: https://github.com/sp614x/optifine/blob/master/OptiFineDoc/doc/ctm.properties

Put the file, along with your new texture (named 0.png), in its own folder. While not required, please name the folder and file the same as your block name.


# Caveats
Players viewing the custom blocks, who do not meet the requirements above, will simply see the "base block" that you renamed. For example, if you renamed a furnace, players without the pack/optifine will just see a normal furnace.

The block will retain the functionality and GUI of the "base block". So a renamed furnace will still function like a normal furnace.