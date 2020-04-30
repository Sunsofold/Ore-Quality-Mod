A template for Mindustry mods with basic file structure for easy startup while modding.


1.1 Directory Structure

Your project directory should look something like this:

project  
├── mod.json  
├── content  
│   ├── items  
│   ├── blocks  
│   ├── mechs  
│   ├── liquids  
│   ├── units  
│   └── zones  
├── maps  
├── bundles  
├── sounds  
├── schematics  
├── scripts  
├── sprites-override  
└── sprites  

    mod.json (required) metadata file for your mod,
    content/* directories for game Content,
    maps/ directory for Zone maps,
    bundles/ directory for Bundles,
    sounds/ directory for Sound files,
    schematics/ directory for Schematic files,
    scripts/ directory for Scripts,
    sprites-override/ Sprites directory for overriding ingame content,
    sprites/ Sprites directory for your content,

Every platform has a different user application data directory, and this is where your mods should be placed:

    Linux: ~/.local/share/Mindustry/mods/
    Steam: steam/steamapps/common/Mindustry/mods/
    Windows: %appdata%/Mindustry/mods/
    Apple: ~/Library/Application Support/Mindustry/mods/

Note that your filenames should be lowercased and hyphen separated:

    correct: my-custom-block.json
    incorrect: My Custom Block.json



reference materials stolen blatently and witout permission from https://simonwoodburyforget.github.io/mindustry-modding

Original sprites can be obtained at https://github.com/Anuken/Mindustry/tree/master/core/assets-raw/sprites
