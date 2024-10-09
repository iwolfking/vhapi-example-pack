# Gear Enchantments
Same format as gear_enchantments.json in the_vault config folder. Supports adding new entries and modifying existing ones.

# Handheld Models
For each gear type: axe, wand, sword, focus, shield, include a folder and then include a file with the same format as seen in the examples. The namespace of the ID *must* be custom_transmogs to work properly. You will also need to include a texture and model (optional) in custom_transmogs/textures/item/gear/<gear> and custom_transmogs/models/item/gear/<gear> as well that match the id given. Should support custom gear pieces that have been registered using the API as well.

# Gear Model Rolls
This is only for vanilla transmog model rolls. For custom gear pieces, include in "custom/model_rolls" folder instead. Entries will be added alongside existing ones, no support for removal or moving rarities at this time.

# Shield Models
Same as Handheld Models but if you have no model file, it will use a shield model instead. In vanilla VH, this is for shields only.
