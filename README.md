# Emissive-library
Uses core shaders to allow emissive texture support for blocks, items, armor, and more! This is a library for other resourcepack creators to use.

#### Note: Emissive blocks do not work with Sodium. Everything else does.
#### Note 2: As of the 1.21.2 snapshot 24w33a you can create emissive blocks from their models. This resourcepack still supports making emissive blocks from its style. I would recommend using the model method instead of the one provided with this pack since it works with sodium.

### Example pack I made for showcasing the use of this library ([Download](example.com)):
![Example pack showcase (in gallery)](https://cdn.modrinth.com/data/3I2optIw/images/831308a7cafb0cca53f2dede2cd85ae7ac0a5782.png)

# How This Works:
This pack uses core shaders to allow the support of emissive blocks / items / entities / more.
This means that it should work in any version 1.18+.
This pack makes anything with the translucency value of 254 glow. This makes it easy to implement on existing packs.

# For Resource Pack Developers:
Read the how to implement section of this page. Feel free to use this in any pack you create or link this page as a dependency. You can use any content in this pack in your own pack with credit to me. You can use this pack as long as you credit this page in your work. You do not need my permission you just need to credit me.

# How to Implement in Your Packs
All you have to do is change the pixels that you want to be emissive to have a translucent value of 254. You can use Paint .net, GIMP, or any other software to do this.
